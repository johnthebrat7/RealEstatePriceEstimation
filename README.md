Real Estate Price Estimation – Using Machine Learning 

Overview

This project predicts real estate prices in Bengaluru, India using machine learning regression algorithms.
It demonstrates end-to-end implementation — from data preprocessing and feature engineering to model evaluation — with a focus on accuracy, scalability, and interpretability.

Objective

The main goal is to build a model that accurately estimates property prices based on key factors such as location, number of bedrooms (BHK), total square footage, and bathrooms.
The project compares multiple regression techniques to determine the best-performing algorithm for price prediction.

Key Features

Cleaned and preprocessed raw real estate data (handled missing values and outliers).
Engineered new features such as price per square foot and encoded categorical data using OneHotEncoding.
Implemented and compared five ML algorithms:

Linear Regression
Decision Tree Regression

Evaluated model performance using R², MAE, and RMSE metrics.

Achieved ~80% prediction accuracy using Linear Regression.

Workflow

Data Collection:

Dataset sourced from Kaggle.
Data Cleaning & Preprocessing:
Removed irrelevant and duplicate records.
Handled missing values and outliers.
Converted categorical data to numerical via One-Hot Encoding.
Exploratory Data Analysis (EDA):
Visualised feature correlations using Matplotlib and Seaborn.
Identified patterns between location, area, and price.

Model Building:

Trained regression models (Linear, Decision Tree).
Used train_test_split() for data partitioning and cross-validation.

Model Evaluation:

Measured performance using R², MAE, and RMSE.
Compared accuracy scores to select the best model.

Results & Insights:

Linear Regression yielded the highest R² value (~0.80).


How to Run

Clone this repository:
git clone https://github.com/johnthebrat7/RealEstatePriceEstimation.git
cd RealEstatePriceEstimation

Install dependencies:
pip install -r requirements.txt

Launch the notebook:
jupyter notebook RealEstatePriceEstimation.ipynb

