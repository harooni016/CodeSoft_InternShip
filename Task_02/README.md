# Movie Rating Prediction Project

## Project Overview
This project involves predicting movie ratings based on various features. The project includes data cleaning, exploratory data analysis (EDA), and building a prediction model. The data cleaning process involves dropping missing values Name and Year columns. The EDA provides insights into all features. The prediction models used include linear regression, random forest, and XGBoost.

## Dataset
The dataset used in this project is from [Kaggal](https://www.kaggle.com/) It provides information on various features of movies and their ratings.

## Files
- `IMDb Movies India.csv`: The dataset.
- `Movie_ Rating_ Prediction.ipynb`: Jupyter notebook for building the prediction models.

## Requirements
- Python 3.7+
- Jupyter Notebook
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, xgboost

## Usage
1. Clone this repository.
2. Install the required libraries.
3. Run `movie_EDA.ipynb` for exploratory data analysis.
4. Run `Movie_ Rating_ Prediction.ipynb` to build and evaluate the prediction models.

## Results
The results of the EDA provide insights into all features of the dataset. The prediction models (linear regression, random forest, and XGBoost) all achieve the same Mean_Squared_Error(1.8) R2 score(1.0).
