---------------- Housing Price Prediction using Linear Regression--------------------

----------------- Project Overview

This project focuses on predicting house prices using Multiple Linear Regression.
The model analyzes various housing features such as area, number of bedrooms, bathrooms, stories, parking availability, and furnishing status to estimate the final property price.

The goal of this project is to understand how different features influence house prices and build an accurate predictive model.

---------------------------- Problem Statement--------------------------

To develop a machine learning regression model that predicts house prices based on multiple property-related features.

------------------------------ Technologies Used----------------------------------

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

-------------------------------- Dataset Information------------------------------------

Dataset Name: Housing.csv

Target Variable: price

Features Used:

Area

Bedrooms

Bathrooms

Stories

Parking

Main Road

Guest Room

Basement

Hot Water Heating

Air Conditioning

Preferred Area

Furnishing Status

-------------------------- Project Workflow--------------------------------------
1️. Data Preprocessing

Loaded dataset using Pandas

Checked for missing values

Removed duplicate records

Converted categorical variables using One-Hot Encoding

Separated features (X) and target variable (y)

Split dataset into training (80%) and testing (20%) sets

2️. Model Building

Applied Multiple Linear Regression

Trained the model using training data

Learned relationship between independent variables and house price

3️. Model Evaluation

---------------------------Model performance was evaluated using:---------------------------

R² Score

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

Root Mean Squared Error (RMSE)

-------------------------------Model Evaluation Metrics--------------------------------

R² Score – Measures how well the model explains variance in house prices.

MAE – Average prediction error.

MSE – Penalizes larger errors more.

RMSE – Provides prediction error in the same unit as house prices.

---------------------------------------Visualization--------------------------------------

The following visualizations were created:

Correlation Heatmap

Actual vs Predicted Price Scatter Plot

Perfect Prediction Line (y = x)

Residual Plot

These visualizations help understand feature relationships and model performance.
