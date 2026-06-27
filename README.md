# Telecom Customer Churn — Exploratory Data Analysis

Exploratory data analysis on a telecom customer churn dataset using Python, identifying key factors that drive customer churn.

## Project Overview
This project explores a telecom customer dataset to understand patterns and behaviors linked to customer churn. The analysis covers data cleaning, distribution analysis, and relationship analysis between key variables and churn.

## Process
- Loaded and inspected the dataset (shape, data types, missing values, duplicates)
- Separated numeric and categorical variables for targeted analysis
- Visualized distributions of tenure, MonthlyCharges, and TotalCharges
- Compared numeric and categorical variables against Churn using boxplots and count plots
- Examined correlations between numeric features using a heatmap

## Key Insights
- **Churn happens early** — most customers who leave do so within their first few months of tenure
- **Higher MonthlyCharges are linked to higher churn** — pricing sensitivity appears to play a role
- **Contract type is a strong predictor** — month-to-month customers churn far more than those on one-year or two-year contracts
- **Payment method matters** — customers paying via electronic check churn more than those using other methods
- **Long-tenure customers rarely churn** — loyalty builds significantly the longer a customer stays

## Files
- `EDA.ipynb` — full analysis notebook
- `Project_Summary.pdf` — detailed write-up with visualizations and insights
- `train.zip` — dataset used (zipped due to file size)

## Tools Used
Python, Pandas, NumPy, Matplotlib, Seaborn
