LOAN APPROVAL PREDICTION
Project Overview

This project develops a machine learning model to predict loan approval based on applicant data, including income, credit history, and demographics. By automating the risk assessment process, it enhances the efficiency and accuracy of lending decisions.

TECHNOLOGIES USED

Programming Language: Python

LIBRARIES:

pandas, numpy: Data manipulation and analysis

matplotlib, seaborn: Data visualization

scikit-learn: Machine learning algorithms and preprocessing

joblib: Model serialization

streamlit: Interactive web application

DEVELOPMENT TOOLS:

Jupyter Notebook / Python Scripts

IDE: VS Code / PyCharm

PROJECT STRUCTURE

loan-approval-prediction/

1:- data/
loan_data.csv          # Raw dataset

2:-notebooks/
 eda.ipynb              # Exploratory Data Analysis

3:-models/
  model.py               # Model training and evaluation
  model.pkl              # Serialized model

4:-requirements.txt           # Project dependencies

5:-app.py                     # Streamlit app for model deployment

6:- README.md                  # Project overview

DATASET

The dataset used in this project is sourced from Kaggle's Loan Prediction dataset. It contains 13 features:

Loan_ID: Unique identifier

Gender: Applicant's gender

Married: Marital status

Dependents: Number of dependents

Education: Education level

Self_Employed: Employment status

ApplicantIncome: Applicant's income

CoapplicantIncome: Coapplicant's income

LoanAmount: Loan amount in thousands

Loan_Amount_Term: Loan term in months

Credit_History: Credit history (1 = good, 0 = bad)

Property_Area: Area of property (Urban/Semiurban/Rural)

Loan_Status: Loan approval status (Y = Yes, N = No)
