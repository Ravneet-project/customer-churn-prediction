# Customer Churn Analysis using Polars

## Overview

This project performs an Exploratory Data Analysis (EDA) on a banking customer churn dataset using **Polars**, **Pandas**, **Matplotlib**, and **Seaborn**. The objective is to identify the key factors that influence customer churn and provide actionable business insights.

---

## Dataset Information

The dataset contains information about 10,000 bank customers, including:

* Customer demographics
* Credit score
* Geography
* Gender
* Age
* Tenure
* Account balance
* Number of products
* Credit card ownership
* Active membership status
* Estimated salary
* Complaint status
* Satisfaction score
* Card type
* Customer churn status (Exited)

### Target Variable

**Exited**

* 0 = Customer Retained
* 1 = Customer Churned

---

## Tools and Libraries Used

* Polars
* Pandas
* Matplotlib
* Seaborn
* NumPy
* SciPy

---

## Exploratory Data Analysis Performed

### Data Understanding

* Dataset shape analysis
* Column inspection
* Schema verification
* Missing value analysis
* Duplicate record detection

### Univariate Analysis

* Age Distribution
* Credit Score Distribution
* Balance Distribution
* Salary Distribution
* Product Distribution
* Active Member Distribution
* Complaint Distribution
* Satisfaction Score Distribution

### Bivariate Analysis

* Geography vs Churn
* Gender vs Churn
* Age vs Churn
* Credit Score vs Churn
* Balance vs Churn
* Tenure vs Churn
* Number of Products vs Churn
* Active Member vs Churn
* Salary vs Churn
* Credit Card Ownership vs Churn
* Complaint vs Churn
* Satisfaction Score vs Churn

### Statistical Analysis

* Mean
* Median
* Mode
* Standard Deviation
* Skewness Analysis

### Correlation Analysis

* Correlation Heatmap
* Feature Correlation Ranking with Churn

---

## Key Findings

### 1. Customer Complaints are the Strongest Predictor

Customers who raised complaints showed an extremely high churn rate compared to customers who did not complain.

### 2. Age Influences Churn

Older customers were more likely to leave the bank than younger customers.

### 3. Active Customers are More Loyal

Inactive customers showed significantly higher churn rates.

### 4. Geography Matters

Customers from Germany exhibited the highest churn rate.

### 5. Number of Products Impacts Retention

Customers with two products had the lowest churn rate, while customers with three or more products showed higher churn risk.

### 6. Credit Score has Limited Impact

Credit score differences between churned and retained customers were relatively small.

### 7. Salary and Credit Card Ownership have Minimal Influence

These features showed weak relationships with churn.

---

## Business Recommendations

* Improve complaint resolution processes.
* Develop targeted retention programs for older customers.
* Increase customer engagement and activity.
* Focus retention efforts on high-risk regions.
* Monitor high-value customers with large balances.
* Encourage optimal product adoption through bundled offerings.

---

## Conclusion

The analysis identified customer complaints, age, activity status, geography, and product usage as the most influential factors affecting customer churn. These insights can help financial institutions improve customer retention strategies and reduce future churn. The project also provides a strong foundation for future machine learning models aimed at predicting customer churn.
