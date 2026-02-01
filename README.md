# Diamond Price Prediction using Linear Regression

## Overview
This project predicts diamond prices using a Linear Regression model based on physical and quality related features. The objective is to build an interpretable baseline regression model and understand how different attributes influence diamond pricing.

## Dataset
The dataset contains numerical features such as carat, depth, table, and dimensions (x, y, z), along with categorical features including cut, color, and clarity. The target variable is price. An index column was removed during preprocessing.

## Exploratory Data Analysis
EDA was performed to analyze feature distributions, correlations, and relationships with price. Strong correlations were observed between carat and price, while categorical features showed varying influence on pricing.

## Model
Linear Regression was used as the prediction model. Categorical variables were manually encoded and numerical features were scaled before training. The data was split into training and testing sets to evaluate model performance.

## Evaluation Metrics
The model was evaluated using:
- R² Score
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)

## Prediction
The trained model can predict diamond prices for new inputs by applying the same encoding and scaling steps used during training.

## Tools Used
Python, Pandas, NumPy, Scikit-learn, Matplotlib

## Key Learning
This project focuses on understanding the complete regression workflow, proper preprocessing, and the limitations of Linear Regression on non-linear data.

## Author
Naja Nesrin


