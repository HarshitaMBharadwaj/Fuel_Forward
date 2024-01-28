# Predicting Automobile Fuel Efficiency with Linear Regression

## Introduction
The project aims to predict the fuel efficiency of automobiles using linear regression modeling techniques. It utilizes the Auto MPG dataset, which contains various attributes of different car models, including their MPG (miles per gallon) as the target variable.

## Overview
This report presents the results of a regression analysis performed on the dataset to predict the miles per gallon (mpg) of cars based on various features. The analysis includes data preprocessing, model training, evaluation, and interpretation of results.

## 1. Data
- Loaded the Auto MPG dataset and explored its characteristics.
- Explored data distributions, correlations, and relationships through visualizations.
- Checked for null values and handled them either by dropping or imputing.
- Identified the target variable (MPG) and selected relevant features for modeling.
- Encoded categorical features as necessary, such as converting categorical variables to one-hot encoding.
- Scaled or normalized features to ensure consistency in model training.
- Split the dataset into training and testing sets, maintaining an 80/20 ratio to ensure reproducibility using a random seed.
- Standardization was applied to the independent variables using Z-score normalization.

## 2. Model
- Utilized the LinearRegression model from the scikit-learn library.
- Trained the model using the training data to learn the relationships between features and the target variable.
- Inspected the model artifacts, including coefficients and intercepts, to understand the line of best fit.
- Interpreted the coefficients to determine which features contribute most to the predictive ability of the model.

## 3. Evaluation
- Made predictions for the test set using the trained linear regression model.
- Evaluation metrics used:
  - R-squared (R2) Score: 0.80
  - Mean Squared Error (MSE): 14.65
  - Root Mean Squared Error (RMSE): 3.83
- Interpretation of results involved assessing how well the model performed in predicting automobile fuel efficiency based on the evaluation metrics.

## Conclusion
The linear regression model demonstrated effectiveness in predicting automobile fuel efficiency based on the Auto MPG dataset. By analyzing coefficients and evaluation metrics, insights were gained into the significant features influencing MPG prediction. Further optimizations and feature engineering could enhance the model's predictive performance.
