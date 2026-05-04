# DSA 210 Project: Impulsive Purchasing Behavior Analysis

## Project Overview
This project analyzes online retail transaction data to explore impulsive purchasing behavior. The main focus is to understand whether the time of purchase affects buying patterns.

## Dataset
The dataset used is the Online Retail dataset from Kaggle. It includes transaction-level data such as:
- Invoice number
- Product description
- Quantity
- Timestamp (date & time)
- Customer ID
- Country

## Methodology
The project follows a standard data science pipeline:

1. Data Loading & Cleaning  
2. Feature Engineering (hour, day)  
3. Exploratory Data Analysis (EDA)  
4. Data Visualization  
5. Hypothesis Testing
6.  Machine Learning Methods

## Hypothesis
- H0: There is no significant difference between daytime and evening purchases.  
- H1: There is a significant difference between daytime and evening purchases.  

## Results
Purchases are concentrated during specific hours of the day. However, statistical testing (t-test) shows no strong evidence of a significant difference between daytime and evening purchasing behavior.
## Machine Learning Methods

In the current stage of the project, machine learning methods are applied to better understand purchasing behavior patterns.

The following steps were performed:

- Data preprocessing and feature engineering
- Train-test split
- Model training and evaluation
- Prediction of purchasing behavior patterns

## Models Used

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

## Current Progress

The machine learning models are being used to identify patterns related to impulsive purchasing behavior. Preliminary results show that time-related features may contribute to predicting purchasing tendencies.

## Tools Used
- Python  
- Pandas  
- Matplotlib  
- SciPy
- Scikit-learn

## Files
- dsa210-3.ipynb : Initial EDA and hypothesis testing notebook
- dsa210-4.ipynb : Updated notebook including machine learning methods
## Dataset
The dataset is too large to be uploaded to GitHub. 
The dataset used in this project can be accessed directly from Kaggle:
Dataset link:  
https://www.kaggle.com/datasets/vijayuv/onlineretail

[Online Retail Dataset]((https://www.kaggle.com/datasets/vijayuv/onlineretail))

The specific file used is `OnlineRetail.csv`.

## Author
Cahide Kaya

