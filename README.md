# Customer Transaction Prediction

## Project Overview

This project focuses on predicting whether a bank customer will make a specific transaction in the future using Machine Learning classification techniques.

The objective is to develop a predictive model that helps banks identify potential transacting customers using historical customer transaction patterns.

The project uses an anonymized banking dataset containing 200 numerical features, an ID column and a binary target variable.

## Problem Statement

Build a predictive model to identify which customers are likely to make a transaction in the future, irrespective of the amount of money transacted.

**Domain:** Banking

**Project ID:** PRCP-1003

## Dataset Information

The dataset contains:

- `ID_code`: Unique customer identifier
- `target`: Target variable
  - `0` – Customer will not make a transaction
  - `1` – Customer will make a transaction
- `var_0` to `var_199`: 200 anonymized numerical features

**Dataset characteristics:**
- 200,000 records
- 200 numerical input features
- Binary classification problem
- Imbalanced target distribution

Note: The dataset features are anonymized, so their real-world business meanings are unavailable.

## Technologies & Libraries Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- LightGBM
- XGBoost
- CatBoost
- Imbalanced-learn (SMOTE)
- Joblib

## Project Workflow

### 1. Data Understanding and Preprocessing
- Dataset loading and inspection
- Data types and statistical analysis
- Missing value analysis
- Duplicate record detection
- Target distribution analysis
- Stratified train-validation splitting

### 2. Exploratory Data Analysis
- Univariate analysis
- Feature distribution analysis
- Correlation analysis
- Feature variance analysis
- Statistical feature analysis

### 3. Model Building and Comparison

The following machine learning algorithms were implemented and evaluated:

1. Logistic Regression
2. Decision Tree
3. Random Forest
4. Extra Trees
5. XGBoost
6. LightGBM
7. CatBoost

### 4. Handling Class Imbalance

Since the
