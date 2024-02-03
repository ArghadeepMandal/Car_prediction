# car_prediction
## Objective
The main objective of the problem is to develop the machine learning approach to forecast the demand of car rentals on an hourly basis.
Engagement Score Prediction
## Problem Statement
ABC, a car rental company in Bangalore, faces a growing demand for car rentals and aims to balance supply and demand. To address this, a machine learning approach is developed to forecast the hourly demand for car rentals based on past data.

## Objective
The primary goal is to create a machine learning model that accurately predicts the demand for car rentals on an hourly basis.

## Data Dictionary
## Train Data:

date: Date (yyyy-mm-dd)
hour: Hour of the day
demand: Number of car rentals in an hour
## Test Data:

date: Date (yyyy-mm-dd)
hour: Hour of the day
Submission Data:

date: Date (yyyy-mm-dd)
hour: Hour of the day
demand: Predicted number of car rentals in an hour
## Table of Contents
## Importing Relevant Libraries
## Data Inspection
## Data Cleaning
## Exploratory Data Analysis
## Building Models
5.1 K-Nearest Neighbors (KNN)
5.2 Linear Regression
5.3 Decision Tree
5.4 Random Forest
5.5 XGBoost
5.6 Logistic Regression (Note: This is not suitable for the problem, as it's a regression task, not classification.)
## Model Evaluation
6.1 KNN
6.2 Linear Regression
6.3 Decision Tree
6.4 Random Forest
6.5 XGBoost
6.6 Logistic Regression (Not applicable)
Feature Engineering
Model Building and Prediction
8.1 Linear Regression
8.2 Submission of Predictions
Instructions for Running the Code
## Library Installation:

bash
## Copy code
pip install matplotlib pandas numpy seaborn scikit-learn xgboost
Run the Code:
Execute the provided code cells in a Jupyter Notebook or any Python environment.

## Note:

The Logistic Regression model is not suitable for regression tasks, so it should be disregarded.
Feature engineering involves encoding categorical variables and separating the data into training and testing sets.
Models are evaluated using root mean squared error (RMSE) and R-squared (R2) score.
The final predictions are submitted in a CSV file (my_submission_LR.csv).
