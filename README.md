CUSTOMER CHURN EDA REPORT
> Project Overview

This project performs Exploratory Data Analysis (EDA) on a customer churn dataset to identify patterns and factors influencing customer retention and churn behavior.

The analysis focuses on demographic, financial, and service-related attributes to uncover insights that can help improve customer retention strategies and support predictive modeling.

> Dataset Description

The dataset contains customer-related information categorized into:

> Demographic Features
Age
Gender
Region

> Service Features
Plan Type
Service Usage
Resolution Status

> Financial Features
Amount Spent
Subscription Tenure

> Target Variable
ChurnStatus
0 → Retained Customer
1 → Churned Customer

> Objectives
- Understand customer churn distribution
- Identify factors contributing to churn
- Analyze customer behavior and spending patterns
- Discover relationships between tenure, spending, and churn
- Generate insights useful for machine learning models
  
> Key Insights
1. Churn Distribution
The dataset shows a class imbalance.
Churned customers represent a smaller portion of the dataset.
Metrics like F1-score, Precision-Recall, or resampling techniques may be necessary during model training.
2. Amount Spent vs Churn
Customers who churn generally spend less compared to retained customers.
Higher financial engagement is associated with stronger customer loyalty.
3. Tenure vs Churn
Customers with longer subscription tenure are less likely to churn.
Tenure appears to be one of the strongest predictors of retention.
4. Correlation Analysis
Positive correlation exists between:
Tenure and Amount Spent
Negative correlation exists between:
Churn and Tenure
Churn and Amount Spent
Resolution status shows moderate influence on churn.
5. Resolution Status vs Churn
Customers with unresolved or pending service issues are more likely to churn.
Improving customer support and issue resolution can reduce churn rates.

> Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook

> Suggested Workflow
Data Loading
Data Cleaning
Exploratory Data Analysis
Data Visualization
Correlation Analysis
Feature Understanding
Insights Extraction

> Example Visualizations
Churn Distribution Plot
Boxplots for Spending vs Churn
Tenure Distribution
Correlation Heatmap
Resolution Status Analysis

> Conclusion

The EDA highlights that:

Customer tenure,
Spending behavior,
And service resolution status

are major indicators of churn behavior.

These insights can be used for:

Customer retention strategies
Business decision-making
Feature engineering
Predictive churn modeling
