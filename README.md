# Customer Churn Analysis using Polars

## Overview

This project performs Exploratory Data Analysis (EDA) on a banking customer churn dataset using Polars, Pandas, Matplotlib, and Seaborn. The goal is to identify the factors that influence customer churn and derive business insights.

## Dataset

The dataset contains 10,000 customer records with information such as:

* Credit Score
* Geography
* Gender
* Age
* Tenure
* Balance
* Number of Products
* Credit Card Ownership
* Active Membership Status
* Estimated Salary
* Complaint Status
* Satisfaction Score
* Customer Churn (Exited)

### Target Variable

* 0 = Customer Retained
* 1 = Customer Churned

## Analysis Performed

### Data Inspection

* Dataset shape analysis
* Column inspection
* Schema analysis
* Missing value detection
* Duplicate record checking

### Exploratory Data Analysis

* Churn Distribution Analysis
* Age Distribution and Churn Analysis
* Geography vs Churn Analysis
* Gender vs Churn Analysis
* Credit Score Analysis
* Balance Analysis
* Tenure Analysis
* Number of Products Analysis
* Active Member Analysis
* Credit Card Analysis
* Complaint Analysis
* Satisfaction Score Analysis

### Statistical Analysis

* Mean
* Median
* Mode
* Standard Deviation
* Distribution Analysis

### Correlation Analysis

* Correlation Heatmap
* Feature Ranking with Churn

## Key Findings

1. Customer complaints are the strongest indicator of churn.
2. Older customers are more likely to leave the bank.
3. Inactive customers show significantly higher churn rates.
4. Germany has the highest churn rate among regions.
5. Customers with unusual product counts have higher churn risk.
6. Credit score and salary have relatively weak influence on churn.

## Conclusion

The analysis identified customer complaints, age, activity status, geography, and product usage as the most influential factors affecting customer churn. These insights can help banks improve customer retention strategies and reduce future churn.

## Tools Used

* Polars
* Pandas
* Matplotlib
* Seaborn
* Python
