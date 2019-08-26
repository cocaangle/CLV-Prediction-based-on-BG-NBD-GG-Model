# CLV-Prediction-based-on-BG-NBD-GG-Model

The dataset sourced from UCI public machine learning repository: http://archive.ics.uci.edu/ml/machine- learning-databases/00352 (http://archive.ics.uci.edu/ml/machine-learning- databases/00352). It is the transaction data for online retailing.

In the JupyterNotebook, I use lifetime package in python to explore the distribution of customers’ frequency and recency, then build BG/NBD model to explore customer intimacy for the brand and make predictions for their purchase frequency( in certain period of time)); also, build GG model to explore the customer purchase power( the average value per purchase for this customer); combine with result of BG/NBD and GG to predict customer value in a period of time in future.
