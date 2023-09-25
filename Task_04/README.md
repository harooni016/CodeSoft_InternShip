# Sales Prediction Project

## Overview
This project focuses on Exploratory Data Analysis (EDA) and sales prediction on the 'advertising.csv' dataset. The dataset contains information about money spent on advertisement through different channels like TV, Radio and Newspaper.

## Methodology
1. **Exploratory Data Analysis (EDA)**: The dataset was first explored to understand the distribution and relationship of the features. This included visualizations such as histograms, scatter plots, and correlation matrices. The features were found to have different scales, which could impact the performance of certain machine learning algorithms. To address this, a MinMax Scaling was performed. The features were scaled to have a mean of 0 and a standard deviation of 1. This is an important preprocessing step for many machine learning algorithms as it allows them to not be biased towards variables with higher magnitude.

2. **Model Training**: Two different models were trained on the scaled data:
    - Linear Regression
    - Polynomial Regression (degree 2)

## Results
The models were evaluated using the R2 score, which is a statistical measure that represents the proportion of the variance for a dependent variable that's explained by an independent variable or variables in a regression model. 

The Polynomial Regression model achieved the highest R2 score of 0.937, indicating a very good fit to the data. A complexity analysis was also performed to compare the R2 and Mean Squared Error (MSE) for different degrees of the polynomial. The degree 2 polynomial was found to be the best trade-off between model complexity and performance.

## Conclusion
The Polynomial Regression model (degree 2) was found to be the most effective model for predicting sales based on the given advertising spend data. Future work could explore other models or feature engineering techniques to see if performance can be further improved.
