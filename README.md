# loan-default-risk-prediction
Predicting loan default risk using MongoDB, Machine Learning, NLP and Streamlit

# Loan Default Risk Prediction System

This project builds an end-to-end system to predict loan default risk using MongoDB, Machine Learning, Time-Series Forecasting and Natural Language Processing.

It helps financial institutions identify high-risk borrowers and make data-driven credit decisions.

## Features
- MongoDB based loan data storage
- Data cleaning & exploratory data analysis
- ML models: Logistic Regression, Decision Tree, Random Forest
- Default forecasting using time-series
- Interactive dashboards using Plotly & Streamlit
- Natural Language Querying (NLP → MongoDB)

## Model Performance
Random Forest achieved:
- Accuracy: ~85%
- Precision: ~82%
- Recall: ~80%

## Dataset
Synthetic loan dataset with features such as:
- Credit Score
- Income
- Loan Amount
- Interest Rate
- Employment Status
- Debt-to-Income Ratio

## Natural Language Queries
Examples:
- "Show defaulters with loan above 100000"
- "Average credit score of defaulters"
- "Default rate by income group"

## How to Run
```bash
pip install -r requirements.txt
streamlit run app/streamlit_app.py
pip install -r requirements.txt
streamlit run app/streamlit_app.py
