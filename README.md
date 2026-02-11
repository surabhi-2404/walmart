# Walmart Weekly Sales Prediction

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Machine Learning](https://img.shields.io/badge/Model-Regression-orange)
![Dataset](https://img.shields.io/badge/Dataset-Walmart-green)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Level](https://img.shields.io/badge/Level-Intermediate-yellow)
![Library](https://img.shields.io/badge/Framework-Scikit--Learn-red)
![Notebook](https://img.shields.io/badge/Environment-Jupyter-lightgrey)

## Project Overview

This project focuses on predicting weekly sales for Walmart stores using machine learning regression techniques. The goal is to analyze
historical sales data, engineer meaningful features, and build predictive models that estimate future sales accurately.The notebook demonstrates
a complete ML workflow including:

## Data loading

Exploratory data analysis (EDA)<br>
Feature engineering<br>
Model training<br>
Evaluation and comparison<br>

## Dataset

The dataset contains historical Walmart sales data with attributes such as:<br>
Store number<br>
Department<br>
Date<br>
Weekly_Sales (target variable)<br>
Holiday_Flag<br>
Temperature<br>
Fuel_Price<br>
CPI<br>
Unemployment<br>

 ## Project Workflow
1️. Data Preprocessing

Converted Date column to datetime format<br>
Extracted time-based features (year, month, week)<br>
Checked missing values and data types<br>

2️. Exploratory Data Analysis

Distribution plots of sales<br>
Crrelation analysis<br>
Trend visualization across time and stores<br>

3️. Feature Engineering

Time-based features<br>
Seasonal indicators<br>
Removal of redundant columns<br>

4️. Model Building

Multiple regression models were trained and compared:<br>
Linear Regression<br>
Random Forest Regressor<br>
XGBoost Regressor (if included in later cells)<br>

5️. Evaluation Metrics
Models were evaluated using:<br>
R² Score<br>
Mean Absolute Error (MAE)<br>
Root Mean Squared Error (RMSE)<br>

## Results

Tree-based models performed better than linear models.<br>
Seasonal patterns significantly influenced weekly sales.<br>
Feature engineering improved prediction accuracy.<br>

## Tech Stack

Python<br>
Pandas<br>
NumPy<br>
Matplotlib / Seaborn<br>
Scikit-learn<br>
XGBoost (optional)<br>

## Future Improvements

Hyperparameter tuning<br>
Time-series specific models (ARIMA, Prophet, LSTM)<br>
Store-wise model training<br>
Deployment as a web app dashboard<br>

## Author

Surabhi<br>
Machine Learning & Data Science Enthusiast
