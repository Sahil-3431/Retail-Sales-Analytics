# Retail Sales Analytics, Customer Segmentation, Churn Prediction & Sales Forecasting

## Project Overview

This project provides an end-to-end Retail Business Analytics Solution using the Online Retail II Dataset. The solution combines Data Analytics, Machine Learning, Customer Segmentation, Churn Prediction, Time Series Forecasting, and Business Intelligence dashboards to generate actionable business insights.

The project helps organizations understand customer behavior, identify high-value customers, predict churn risks, and forecast future sales trends for better decision-making.

---

## Objectives

- Clean and preprocess retail transaction data
- Analyze sales performance and customer behavior
- Perform Customer Segmentation using RFM Analysis
- Predict Customer Churn using Machine Learning
- Forecast Future Sales using Time Series Models
- Build Interactive Power BI Dashboards
- Generate business insights and recommendations

---

## Dataset

The project uses the **Online Retail II Dataset**, which contains:

- Invoice Number
- Customer ID
- Product Information
- Quantity
- Unit Price
- Invoice Date
- Country

Multiple yearly datasets were merged and processed into a single analytical dataset.

---

## Data Preprocessing

The following preprocessing steps were performed:

- Combined multiple datasets
- Removed missing values
- Removed duplicate records
- Removed cancelled transactions
- Filtered invalid quantities and prices
- Converted dates into datetime format
- Created Total Sales feature

```python
Total_Amount = Quantity * Price
