# AML Group 22 Project

## Background and Context
The ability to predict loan approval outcomes and assess financial risk is crucial for banks and financial institutions to make informed lending decisions. Creditworthiness and financial stability are key factors that influence loan approvals, and accurate predictions in these areas can reduce default rates, streamline lending processes, and enhance financial inclusion. 

This project aims to explore several machine learning models that can predict the binary outcome of loan approval based on a range of demographic, financial, and historical data. If time permits, we will also work on predicting the risk score using regression.

## Dataset Description
The dataset used for this project is a synthetic dataset designed for risk assessment and loan approval modeling, sourced from Kaggle:  
[Financial Risk for Loan Approval Dataset](https://www.kaggle.com/datasets/lorenzozoppelletto/financial-risk-for-loan-approval/data)  

It contains 20,000 records with 36 attributes related to demographic information, credit history, income levels, existing debt, and financial stability. Key features include:
- Age
- Credit score
- Employment status
- Loan amount
- Debt-to-income ratio
- Previous loan defaults, and more.

This dataset provides a comprehensive foundation for building models that predict:
1. **Risk Score** (a regression problem)
2. **Loan Approval Status** (a binary classification problem)

## Contributions
1.  data exploration: Ruoqi Yan, Kaushal Damania
2. Data preprocessing: Naveen Reddy Dyava, Kaushal Damania
3. Model Training: Naveen Reddy Dyava
4. Model Evaluation: Naveen Reddy Dyava, Kaushal Damania 
5. Model Interpretation: Kaushal Damania
6. Report: Naveen Reddy Dyava, Kaushal Damania


## Proposed Machine Learning Models
The following machine learning models are proposed for this project:
1. Logistic
2. CatBoost
3. AdaBoost
4. LightGBM
5. MLP

## Running the project
To run the project please follow the following instructions:
```bash
# create a python environment
python3.10 -m venv .venv
```
```bash
# Install the required packages
pip install -r requirements.txt
```
```bash
# activate the environment
source .venv/bin/activate
```
You can now run any notebook in the project

