# Fraud Detection Project

This repository contains code for a fraud detection project using machine learning. The project involves the analysis of credit card transactions to identify fraudulent activities. It includes data preprocessing, exploratory data analysis, and the implementation of machine learning models for fraud detection.

## Dataset

The dataset used in this project consists of credit card transactions from two files: `fraudTrain.csv` and `fraudTest.csv`. The data includes various features such as transaction date, credit card number, merchant information, transaction amount, and whether the transaction is fraudulent or not.

## Libraries Used

- pandas
- numpy
- matplotlib
- seaborn
- plotly
- scikit-learn
- imbalanced-learn (SMOTE)

## Exploratory Data Analysis (EDA)

The exploratory data analysis covers various aspects of the dataset, including:

- Transaction amount distribution
- Gender vs Fraud
- Percentage difference in spending categories between fraud and non-fraud transactions
- Age distribution in fraudulent vs non-fraudulent transactions
- Time of day vs Fraud
- Day of the week vs Fraud
- Month vs Fraud
- State-wise analysis of fraud percentages

## Data Preprocessing

Data preprocessing involves handling duplicates and converting categorical variables into dummy variables.

## Machine Learning Models

Two machine learning models were implemented:

### Logistic Regression

- Utilized SMOTE for handling imbalanced classes


### Decision Tree Classifier

- Utilized SMOTE for handling imbalanced classes



