# Iris Dataset EDA and Prediction Project

## Overview
This project focuses on Exploratory Data Analysis (EDA) and prediction on the Iris dataset. The Iris dataset is a multivariate dataset introduced by the British statistician and biologist Ronald Fisher in his 1936 paper. The dataset consists of 50 samples from each of three species of Iris flowers (Iris setosa, Iris virginica, and Iris versicolor). Four features were measured from each sample: the lengths and the widths of the sepals and petals.

## Methodology
1. **Exploratory Data Analysis (EDA)**: The Iris dataset was first explored to understand the distribution and relationship of the features. This included visualizations such as histograms, scatter plots, and correlation matrices. The features were found to have different scales, which could impact the performance of certain machine learning algorithms. To address this, a data scaling step was performed.

2. **Model Training**: Three different models were trained on the scaled data:
    - Logistic Regression
    - Decision Tree Classifier
    - K-Nearest Neighbors Classifier

## Results
The models were evaluated using the F1 score, which is a measure of a test's accuracy that considers both the precision and the recall. The Decision Tree Classifier achieved the highest F1 score of 0.978, indicating a very good fit to the data.

## Conclusion
The Decision Tree Classifier was found to be the most effective model for predicting the species of an Iris flower based on the given features. Future work could explore other models or feature engineering techniques to see if performance can be further improved.
