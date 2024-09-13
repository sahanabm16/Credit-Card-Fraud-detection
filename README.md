# Credit Card Fraud Detection
Overview
This repository contains a Jupyter notebook that demonstrates the process of detecting credit card fraud using various machine learning techniques. The dataset used is a publicly available credit card fraud dataset, and the goal is to identify fraudulent transactions effectively while minimizing false positives.

Features
Data Preprocessing: Steps for handling missing data, scaling features, and balancing the dataset.
Exploratory Data Analysis (EDA): Visualizations and statistical analysis of the dataset to understand patterns and distributions.
Modeling: Several machine learning models are used, including:
Logistic Regression
Decision Trees
Random Forests
Support Vector Machines
Neural Networks
Evaluation Metrics: The models are evaluated using metrics such as accuracy, precision, recall, F1 score, and ROC-AUC.
Dataset
The dataset used in this notebook is a highly imbalanced dataset with a majority of non-fraudulent transactions. It can be found here. The key features include:

Time: The elapsed time since the first transaction.
Amount: The transaction amount.
V1-V28: The result of a PCA transformation on the original features to reduce dimensionality.
Class: The target variable, where 1 indicates fraud and 0 indicates a legitimate transaction.


Results
The notebook compares the performance of various models on the credit card fraud detection task. The final results show the best-performing model and insights on how different approaches handle class imbalance and predictive accuracy.

Future Improvements
Hyperparameter tuning for improved performance.
Experimenting with different oversampling and undersampling techniques.
Applying advanced anomaly detection techniques such as autoencoders.
