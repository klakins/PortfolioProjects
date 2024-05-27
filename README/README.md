# Credit Risk Analysis

## Overview

This project aimed to predict the likelihood of a customer defaulting on a loan using a classification algorithm.

## Completed tasks
Data Exploration and Cleaning

- Loaded the dataset and used .info() and .describe() to understand its structure and summary statistics.
- Identified missing values in person_emp_length and loan_int_rate columns.
- Imputed missing values using the median 

## Exploratory Data Analysis (EDA)
- Distribution of Loan Status: Count plot to show the balance of target variable.
- Correlation Heatmap: Displayed correlations between numerical features.

## Data Preprocessing:
- Feature Engineering:
- Created new features such as debt_to_income_ratio.

## Categorical Data Treatment
- Applied one-hot encoding to categorical columns (person_home_ownership and loan_intent).

## Normalization:

- Normalized data using StandardScaler to standardize features.

## Modeling
Logistic Regression:

- Split the dataset into training and testing sets.
- Trained a logistic regression model.
- Evaluated model performance using accuracy, precision, recall, and F1 score.

## Summary
This project showed the steps involved in building a predictive model for credit risk analysis, from data cleaning and feature engineering to model training and evaluation.
