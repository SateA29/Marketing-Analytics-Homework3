***Survival Analysis***

**Overview**

This code analyzes customer retention using telecom data to help telecom companies understand and improve customer loyalty. 
It predicts how long customers will stay with the company and how much they're worth over time.

**Key Features**

Survival Analysis: Predicts customer churn using different models based on telecom data.
Customer Value Prediction: Estimates the lifetime value of each customer to the telecom company.
Visuals: Provides graphs and visualizations to understand which customers are most valuable and at risk of leaving.

**Usage**

Data Preparation:
Place your telecom data file (e.g., 'telco.csv') in the same directory as the code.
Ensure your data includes relevant columns such as customer ID, tenure, churn status, and demographic information.
Run the Code:
Open the provided Python script or notebook in your preferred Python environment (e.g., Jupyter Notebook).
Run the code to import the telecom data and preprocess it for analysis.
Survival Analysis:
Fit survival analysis models (Log-Normal, Log-Logistic, Weibull, Exponential) to the tenure and churn data.
Evaluate model performance using Akaike Information Criterion (AIC) and Bayesian Information Criterion (BIC).
CLV Prediction:
Predict CLV for individual customers using the fitted survival models.
Visualize CLV distributions across different customer segments.
Retention Strategies:
Identify valuable customer segments based on CLV analysis.
Estimate retention budgets and allocate resources effectively to target at-risk customers.
