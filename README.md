# House Price Prediction
Machine Learning project for predicting house prices using Python and Scikit-learn
## Overview

This project predicts California house prices using machine learning models.

The objective was to build a complete machine learning pipeline, starting from data exploration and ending with model evaluation and comparison.

## Dataset

California Housing Dataset from Scikit-learn.

Features include:

* Median Income
* House Age
* Average Rooms
* Average Bedrooms
* Population
* Average Occupancy
* Latitude
* Longitude

Target Variable:

* Median House Value

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn

## Workflow

1. Data Loading
2. Exploratory Data Analysis (EDA)
3. Correlation Analysis
4. Train-Test Split
5. Linear Regression Model
6. Random Forest Model
7. Model Evaluation

## Model Performance

### Linear Regression

* MAE: 0.533
* RMSE: 0.746
* R²: 0.576

### Random Forest Regressor

* MAE: 0.328
* RMSE: 0.505
* R²: 0.805

## Key Findings

* Median Income was the strongest predictor of house prices.
* Random Forest significantly outperformed Linear Regression.
* Nonlinear models captured housing price patterns more effectively.

## Future Improvements

* Hyperparameter tuning
* Feature engineering
* Gradient Boosting
* XGBoost
* Cross-validation

## Author

Akshat Das
