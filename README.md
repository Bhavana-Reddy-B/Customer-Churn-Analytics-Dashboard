# 📊 Customer Churn Analytics Dashboard

A comprehensive **end-to-end Data Analytics & Business Intelligence project** on customer churn analysis.  
This project demonstrates advanced data cleaning (SQL + Python), exploratory data analysis (EDA), feature engineering, **predictive modeling**, and interactive insights using **Power BI**.

---

## 📑 Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Project Workflow](#project-workflow)
  - [1. Data Cleaning (SQL & Python)](#1-data-cleaning-sql--python)
  - [2. Exploratory Data Analysis (EDA)](#2-exploratory-data-analysis-eda)
  - [3. Feature Engineering](#3-feature-engineering)
  - [4. Predictive Modeling (Basic)](#4-predictive-modeling-basic)
  - [5. Power BI Dashboard](#5-power-bi-dashboard)
- [Features](#features)
- [Contributing](#contributing)
- [License](#license)

---

## 📌 Project Overview
Customer churn analysis is a critical business intelligence challenge that directly impacts revenue and growth.  
This comprehensive analytics solution addresses:
- **Risk Assessment**: Which customers are at high risk of churning?
- **Root Cause Analysis**: What key factors drive customer churn?
- **Predictive Analytics**: Can we accurately predict churn using advanced machine learning?
- **Business Intelligence**: How can we visualize churn insights interactively in **Power BI** for actionable decision-making?

---

## 📂 Dataset
The project utilizes a comprehensive **Customer Churn dataset** containing:
- **Demographic Information**: Gender, Age, Family Status, Dependents  
- **Service Portfolio**: Phone, Internet, Security, Streaming services  
- **Financial Data**: Contract type, Payment methods, Monthly & Total charges  
- **Target Variable**: `Churn` (Yes/No) - Customer retention status

👉 [Dataset Source](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)  

---

## 🔄 Project Workflow

### 1. Data Cleaning (SQL & Python)
- Imported raw dataset into **SQL** for structured cleaning.  
- Removed duplicates & invalid entries (e.g., blank `TotalCharges`).  
- Created flags (binary columns) in SQL: `PartnerFlag`, `PhoneServiceFlag`, `PaperlessBillingFlag`, etc.  
- Exported SQL-cleaned data → processed further in **Python** (handled nulls, type conversions).

### 2. Exploratory Data Analysis (EDA)
- Summary statistics, distributions & missing values check.  
- Visualized churn patterns by demographics, services, contract type.  
- Example EDA Insights:
  - Month-to-month customers churn the most.
  - Higher churn for customers with **higher monthly charges**.
  - Long-tenure customers are more loyal.

### 3. Feature Engineering
- Encoded categorical variables (One-Hot Encoding).  
- Created derived features:
  - `TotalServices` = count of services used.  
  - `HighChargesFlag` = 1 if monthly charges > median.  
- Handled missing values (imputation for `MultipleLines`).

### 4. Predictive Modeling & Machine Learning
- **Primary Model**: Logistic Regression with advanced feature selection
- **Model Performance**: **82% accuracy** with balanced precision-recall
- **Confusion Matrix Results**:
  - Precision (Churn=1): 0.68  
  - Recall (Churn=1): 0.60  
  - F1-Score: 0.64
- **Business Impact**: Successfully identifies high-risk customers for targeted retention campaigns

### 5. Power BI Dashboard
An interactive **Churn Analysis Dashboard** was created with 5 key sections:

1. **Overall Customer Overview**  
   - Customer distribution by gender, contract, internet service.  
   - Churn rate KPI.

2. **Services & Churn Patterns**  
   - Service usage breakdown (Phone, Internet, Streaming).  
   - Churn comparison by service type.

3. **Financial Analysis**  
   - Monthly charges distribution split by churn.  
   - Average monthly charges card (with churn conditional color).  

4. **Customer Demographics**  
   - Churn split by gender, senior citizen, and dependents.  
   - Box plot of monthly charges vs churn.  

5. **Churn Risk & Insights**  
   - Tenure group vs churn (stacked column).  
   - Contract type impact on churn.  
   - High-risk customer segment identification.

---
## 🌟 Key Features

- **Advanced Data Processing**: SQL + Python dual approach for robust data cleaning
- **Machine Learning Integration**: Predictive modeling with business-focused metrics
- **Interactive Business Intelligence**: Comprehensive Power BI dashboard with actionable insights
- **End-to-End Analytics**: Complete workflow from data ingestion to business recommendations
- **Scalable Architecture**: Designed for enterprise-level customer analytics

---
## 👨‍💻 Author

**Bhavana Reddy**  
*Data Visualization Expert | Business Intelligence Professional*

- 🔗 **[LinkedIn](https://www.linkedin.com/in/bhavanab28033/)**
- 📧 **Email**: reddybhavanapreethamb@gmail.com
- 💼 **[Portfolio](https://github.com/Bhavana-Reddy-B)**

---

