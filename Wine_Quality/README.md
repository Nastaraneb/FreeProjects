# Wine Quality Prediction (Regression)

This project aims to predict the **quality of wine** based on various physicochemical features using regression models. The dataset used for this project contains information about red wines, including features like alcohol content, acidity, pH, sulphates, and more. The goal is to predict the wine quality score (ranging from 3 to 8) based on these features.

## Project Overview

The dataset consists of various wine properties, and the task is to build a machine learning model that can accurately predict wine quality. The models used in this project include:
- **Linear Regression**
- **Polynomial Regression**
- **Random Forest Regression**
- **Gradient Boosting Regression**

Each model is evaluated based on the performance metrics:
- **Mean Absolute Error (MAE)**
- **Mean Squared Error (MSE)**
- **Root Mean Squared Error (RMSE)**
- **R² (Coefficient of Determination)**
- **Also try to visually evaluate using different plots**

The best model is chosen based on the lowest error and highest R².

## Key Features

- **Fixed acidity**
- **Volatile acidity**
- **Citric acid**
- **Residual sugar**
- **Chlorides**
- **Free sulfur dioxide**
- **Total sulfur dioxide**
- **Density**
- **pH**
- **Sulphates**
- **Alcohol content**

## Data Preprocessing

- **Handling missing values**: The dataset is checked for missing values, and appropriate steps are taken to handle them.
- **Feature selection**: Features are selected based on their importance and correlation with the target variable.

