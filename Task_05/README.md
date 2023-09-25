# Credit Card Fraud Detection Project

## Overview
This project focuses on Exploratory Data Analysis (EDA) and fraud detection on the 'creditcard.csv' dataset. The dataset contains transactions made by credit cards, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

## Dataset
The Credit Card Fraud Detection dataset used in this Project from [Download Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud/download?datasetVersionNumber=3).

## Methodology
1. **Exploratory Data Analysis (EDA)**: The 'creditcard.csv' dataset was first explored to understand the distribution and relationship of the features. This included visualizations such as histograms, scatter plots, and correlation matrices.

2. **Model Training**: Two different models were trained on the data:
    - Logistic Regression
    - Random Forest Classifier

## Results
The models were evaluated using different metrics including the F1 score, which is a measure of a test's accuracy that considers both the precision and the recall. The Random Forest Classifier achieved the highest F1 score of 0.807, indicating a very good fit to the data.

## Conclusion
The Random Forest Classifier was found to be the most effective model for detecting fraudulent transactions in the given credit card data. Future work could explore other models or feature engineering techniques to see if performance can be further improved.
