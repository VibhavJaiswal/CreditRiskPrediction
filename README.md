# CreditRiskPrediction

🚀 Credit Risk Prediction using Machine Learning
📌 Overview

This project focuses on credit risk modeling by predicting whether a company will default or not based on financial attributes. Using EDA, feature engineering, and machine learning models, we assess credit risk to help financial institutions minimize loan default risks.
🎯 Objectives:

    Build a predictive model to classify companies as defaulters or non-defaulters.
    Perform Exploratory Data Analysis (EDA) to understand key financial indicators.
    Apply Machine Learning models (Logistic Regression, Random Forest, Gradient Boosting).
    Handle class imbalance using SMOTE (Synthetic Minority Oversampling Technique).
    Provide business recommendations based on data-driven insights.


    📊 Dataset Overview

    The dataset consists of financial attributes from 4,256 companies.
    The target variable: Default (1 = Defaulter, 0 = Non-Defaulter).
    50 independent variables, including:
        Total Assets, Net Worth, Income, Expenses, Borrowings, Sales, Liabilities.
        Financial Ratios (PBT%, PAT%, Cash Profit%, Debt-to-Equity, Creditors Turnover).

💡 Preprocessing Steps:

    Missing values treatment: Dropped columns with >30% null values, imputed others using median.
    Outlier detection: Used IQR method to cap extreme values.
    Feature Selection: Removed highly correlated variables to avoid multicollinearity.
    Class Imbalance Handling: Used SMOTE to balance minority class (6.5% default cases).