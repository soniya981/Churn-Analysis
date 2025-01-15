# Customer Churn Analysis and Prediction

A project to analyze customer churn, predict future churners, and visualize insights using Power BI.

## About

This project focuses on understanding customer churn patterns and predicting future churners based on historical data. The analysis and predictions are visualized in Power BI to provide actionable insights for stakeholders.

## Features

- Data cleaning and transformation in SQL Server Management Studio.
- Churn analysis and prediction using Power BI.
- Visualization of current and future churn trends.
- Predictive modeling using a Random Forest Classifier.
  
### Prerequisites

- SQL Server Management Studio
- Power BI Desktop
- Python

## Usage

### Step 1: Data Cleaning
- Use SQL queries to clean customer datasets.

### Step 2: Churn Analysis
- Perform exploratory analysis in Power BI to identify trends and patterns.

### Step 3: Predict Future Churners
- Apply predictive models specifically a Random Forest Classifier to new customer data.
- Evaluate model performance using metrics like accuracy, precision, recall and F1-score.

Example Confusion Matrix:
```
[[783  64]
 [126 229]]
```

Example Classification Report:
```
              precision    recall  f1-score   support

           0       0.86      0.92      0.89       847
           1       0.78      0.65      0.71       355

    accuracy                           0.84      1202
   macro avg       0.82      0.78      0.80      1202
weighted avg       0.84      0.84      0.84      1202
```

### Step 4: Visualization
- Create dashboards in Power BI to present the insights and predictions visually.


