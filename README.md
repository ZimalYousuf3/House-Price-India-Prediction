# House Price India Prediction

A regression project predicting house prices in India using real world housing data. This project covers the full machine learning workflow from exploratory data analysis to model comparison and feature importance analysis.

## Project Overview
- **Type**: Regression (predicting house prices)
- **Models used**: Linear Regression, Random Forest Regressor
- **Evaluation metrics**: MAE, RMSE, R2 Score

## What is covered
- Exploratory Data Analysis (info, describe, correlation heatmap)
- Correlation analysis to identify key price drivers
- Identifying and removing a misleading feature (id column, which showed false correlation due to row ordering, not a genuine pattern)
- Train/Test split (80/20)
- Training and comparing Linear Regression and Random Forest models
- Feature importance analysis
- Scatter plot visualization of top features against price

## Key Results
- **Winning Model**: Random Forest (R2: 0.85, MAE: 70,149) outperformed Linear Regression (R2: 0.54, MAE: 125,366)
- **Top Feature**: Grade of the house, followed by living area
  
## Dataset
House Prices India dataset from Kaggle (Sukhmandeep Singh Brar), containing 14,619 rows and 23 columns covering house features like bedrooms, bathrooms, living area, grade, location, and price.

## Tools Used
Python, pandas, numpy, seaborn, matplotlib, scikit-learn
