# Retail Customer Churn Prediction & Segmentation

## Overview
End-to-end data analysis project on 1M+ retail transactions.
Segments customers using RFM analysis and predicts churn using Machine Learning.

## Business Problem
A UK-based retailer wants to identify which customers are likely to stop buying
so the marketing team can intervene before they churn.

## Dataset
- Source: UCI Online Retail II Dataset
- 1,067,371 transactions | 2009–2011 | UK-based retailer

## Project Pipeline
1. Data Cleaning & Preprocessing
2. Exploratory Data Analysis (EDA)
3. RFM Segmentation (Champions, Loyal, At Risk, Lost)
4. Churn Prediction using Logistic Regression (71.79% accuracy)
5. Power BI Dashboard

## Key Findings
- Recency is the strongest churn predictor
- Champions segment generates the highest revenue
- Clear seasonality spike every October–November (holiday season)
- 1,395 Lost customers vs 1,361 Champions — urgent retention opportunity

## Tech Stack
- Python (Pandas, Matplotlib, Seaborn, Scikit-learn)
- Jupyter Notebook
- Power BI
- Git & GitHub

## ML Model
- Algorithm: Logistic Regression (tuned with GridSearchCV)
- Accuracy: 71.79%
- Approach: Time-based train/test split to avoid data leakage
- Features: Recency, Frequency, Monetary + engineered features

## Project Structure
retail-clv-project/
├── Data/
├── 01_data_loading.ipynb
├── 02_eda.ipynb
├── 03_rfm.ipynb
├── 04_churn_model.ipynb
└── dashboard/
    └── retail_dashboard.pdf