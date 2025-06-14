# Customer Churn Prediction (Logistic Regression)

This project uses a logistic regression model to predict whether a customer will churn (leave a service) based on historical data. It is a simple terminal-based machine learning tool with no visual interface, designed to demonstrate end-to-end predictive modeling using Python.



## Overview

Customer churn is a key metric for businesses, especially in subscription-based industries. This script processes a dataset, trains a logistic regression model, and provides model accuracy and a confusion matrix — all from the command line.



## Features

- Predicts churn using logistic regression  
- Accepts any CSV with a `Churn` column  
- Automatically encodes categorical data  
- Displays model accuracy and confusion matrix  
- Beginner-friendly and lightweight (no dashboards, no visualizations)



## Dataset Format

You must supply a `.csv` file with a column named `Churn`. This column should have binary values (e.g., `Yes`/`No`, or `1`/`0`). Other columns can include demographic or usage data such as:

Gender, Age, MonthlyCharges, Tenure, Contract, Churn
Male, 45, 29.85, 12, Month-to-month, Yes
Female, 32, 56.75, 24, One year, No



## How to Run the Project

1. **Clone or download** this repository.
2. Make sure you have **Python 3.7+** installed.
3. Install dependencies:

```bash
pip install pandas scikit-learn
Run the script:


python churn_prediction.py
When prompted, enter the path to your CSV file (example):


Enter the path to your customer CSV file: C:/Users/yourname/Desktop/churn.csv
Output Example

Enter the path to your customer CSV file: churn.csv
Accuracy: 0.83
Confusion Matrix:
[[90  5]
 [12 43]]
🛠 Technologies Used
Python
pandas
scikit-learn


#Made by Youssef Soliman
