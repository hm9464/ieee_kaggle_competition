# Kaggle IEEE CIS Fraud Detection Competition

Link to competition: https://www.kaggle.com/c/ieee-fraud-detection

This is my submission for the IEEE CIS Fraud Detection Competition run by Kaggle. THis competition involved being able to accurately predict the likelihood of fraud of a particular transaction based on various aspects of the transaction including item, amount, time of day, method of payment, etc.

I approached this competition by first exploring the data (Notebook 1: EDA), to understand the various intricacies of the data and how I could potentially engineer some features. Then, I applied various algorithms and vaildiated the models on a subset of data to determine the best base model to use. I ended up going with the XGBoost algorithm which scored the highest.

I tuned the model using gridsearch to optimize the parameters used. The issue I ran into was that my laptop was not powerful enough to run hundreds of iterations over the entire dataset (it would have taken weeks!) so instead I ran it on 10% of the data, randomly sampled.

My best model ended up with a score of 92.24% on the test set provided by Kaggle. Feel free to explore all notebooks and results, which I have commtted to this repository. 