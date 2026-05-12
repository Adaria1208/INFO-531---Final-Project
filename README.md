# Telco Customer Churn Machine Learning Project

## Project Overview

This project focuses on using machine learning techniques to predict customer churn using the Telco Customer Churn dataset from Kaggle. Customer churn refers to when a customer leaves a company or stops using its services. Predicting customer churn is important because businesses can use this information to identify customers who may be at risk of leaving and develop strategies to improve customer retention.

The goal of this project was to prepare the dataset for machine learning, identify predictor variables and the target variable, preprocess categorical data, split the dataset into training and testing sets, and apply machine learning classification models.

---

## Dataset

Dataset Source:  
https://www.kaggle.com/datasets/blastchar/telco-customer-churn

The dataset contains customer demographic information, billing information, account details, internet service information, and customer churn status.

---

## Tools and Technologies

- Python
- Pandas
- Scikit-learn
- Jupyter Notebook
- GitHub

---

## Machine Learning Models Used

The following machine learning models were implemented:

1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier

---

## Project Workflow

1. Data Preparation
   - Loaded the dataset into Python
   - Checked for missing values
   - Converted the Churn column into binary format
   - Converted TotalCharges into numeric format

2. Feature Selection and Encoding
   - Selected important predictor variables
   - Applied one-hot encoding to categorical variables

3. Training and Testing
   - Split the dataset into training and testing datasets using an 80/20 split

4. Machine Learning Modeling
   - Trained and tested Logistic Regression
   - Trained and tested Decision Tree
   - Trained and tested Random Forest

---

## Results

- Logistic Regression Accuracy: ~79%
- Decision Tree Accuracy: ~73%
- Random Forest Accuracy: ~75%

The Logistic Regression model produced the best performance for predicting customer churn in this project.

---

## Repository Files

- `INFO531_Week16_Project_Report_Blackwell.ipynb`
  - Final project notebook containing code, outputs, explanations, and model results

- `README.md`
  - Project overview and documentation

- `WA_Fn-UseC_-Telco-Customer-Churn.csv`
  - Dataset used for the project

---

## Author

Adaria Blackwell

INFO 531: Data Warehousing and Analytics in the Cloud  
Spring 2026