# 🏦 CreditRisk360: Banking Risk Intelligence & Client Risk Scoring

## Transforming Banking Data into Actionable Lending Intelligence

> *"Effective lending isn't just about predicting risk—it's about understanding customer behavior, quantifying uncertainty, and enabling confident business decisions through data."*

<p align="center">

![Python](https://img.shields.io/badge/Python-Data%20Analytics-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-Business%20Intelligence-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Processing-150458?style=for-the-badge&logo=pandas)
![Status](https://img.shields.io/badge/Project-Completed-success?style=for-the-badge)

</p>

---

# 📖 Project Overview

Banks collect vast amounts of customer and financial data every day, yet turning that information into meaningful lending decisions remains a significant challenge. Traditional reports often summarize historical performance but provide limited support for identifying customers who may pose future financial risk.

**CreditRisk360** is an end-to-end Banking Risk Intelligence project that demonstrates how data analytics, machine learning, and business intelligence can be combined to support smarter credit risk assessment.

Starting from raw banking data, the project performs data cleaning, exploratory data analysis, feature engineering, predictive modeling, and interactive dashboard development. Each customer is assigned a continuous **Risk Score**, allowing financial institutions to prioritize high-risk clients and gain a comprehensive view of their lending portfolio.

Rather than focusing solely on model development, the project emphasizes how analytical solutions can bridge the gap between technical insights and real business decision-making.

---

# 🎯 Business Problem

Financial institutions face a delicate balance between managing lending risk and maintaining customer growth.

Approving loans for high-risk customers can lead to increased defaults and financial losses, while overly conservative lending strategies may result in missed business opportunities.

To support better decision-making, banks need answers to questions such as:

- Which customers present the highest lending risk?
- Which financial indicators contribute most to customer risk?
- Which customers should relationship managers prioritize for review?
- How can lending and deposit portfolios be monitored in real time?
- How can risk insights be communicated effectively to non-technical stakeholders?

Without structured analysis, these decisions often rely on fragmented reports and manual interpretation rather than data-driven evidence.

This project addresses these challenges by combining predictive analytics with interactive business reporting to create a unified banking risk intelligence solution.

---

# 🎯 Project Objectives

The primary objective of this project is to demonstrate how modern data analytics techniques can support risk assessment within the banking industry.

The project focuses on:

- Assessing data quality and preparing banking data for analysis.
- Understanding customer financial behavior through exploratory analysis.
- Engineering meaningful financial risk indicators.
- Building an interpretable machine learning model for customer risk prediction.
- Generating continuous customer risk scores for portfolio prioritization.
- Developing an interactive Power BI dashboard for business users.
- Transforming analytical results into actionable lending intelligence.

---

# ✨ Project Highlights

✔ End-to-End Banking Risk Analytics Workflow

✔ Exploratory Data Analysis (EDA)

✔ Financial Feature Engineering

✔ Machine Learning-Based Risk Scoring

✔ Customer Risk Segmentation

✔ Interactive Power BI Dashboard

✔ Executive KPI Reporting

✔ Business-Oriented Data Storytelling


# 📂 Repository Structure

```text
CreditRisk360/
│
├── README.md                  # Project documentation
├── CreditRisk360.ipynb        # End-to-end Python analytics & machine learning workflow
├── CreditRisk360.pbix         # Interactive Power BI dashboard
└── Banking.csv                # Retail banking dataset
```

---

# 🏗 Solution Architecture

The project follows a complete analytics workflow that transforms raw banking data into business-ready insights.

```text
                    Raw Banking Dataset
                           │
                           ▼
                 Data Cleaning & Validation
                           │
                           ▼
             Exploratory Data Analysis (EDA)
                           │
                           ▼
                 Financial Feature Engineering
                           │
                           ▼
              Machine Learning Risk Model
                           │
                           ▼
               Customer Risk Score (0–1)
                           │
                           ▼
            Risk Band & Risk Decile Creation
                           │
                           ▼
             Interactive Power BI Dashboard
                           │
                           ▼
           Data-Driven Lending Decisions
```

This workflow demonstrates how analytical models can be integrated with business intelligence tools to support credit risk assessment and portfolio monitoring.

---

# 📊 Dataset Overview

The project uses a retail banking dataset containing approximately **3,000 customer records** and **21 business attributes**, representing various aspects of customer financial behavior.

The data combines customer demographics, banking relationships, account balances, lending information, and internal risk indicators to support comprehensive risk analysis.

### Dataset Includes

| Category | Examples |
|-----------|----------|
| Customer Information | Age, Gender, Nationality, Occupation |
| Banking Relationship | Client ID, Relationship Type, Joined Bank |
| Lending | Bank Loans, Business Lending |
| Deposits | Bank Deposits, Savings, Checking Accounts |
| Credit Information | Credit Card Balance, Number of Credit Cards |
| Financial Profile | Estimated Income, Foreign Currency Account |
| Risk Indicator | Risk Weighting |

For reporting purposes, the Power BI solution is built using relational banking tables, while the machine learning workflow uses a consolidated dataset for predictive modeling.

---

# 🔄 Analytics Workflow

The project follows a structured workflow similar to those used in banking analytics and business intelligence teams.

### **1️⃣ Data Preparation**

- Loaded the banking dataset into Python.
- Validated data types and schema.
- Parsed date fields.
- Converted financial attributes into appropriate numeric formats.

---

### **2️⃣ Data Quality Assessment**

Performed a comprehensive audit to evaluate dataset quality before analysis.

This included:

- Missing value assessment
- Duplicate record detection
- Data type validation
- Cardinality analysis
- Basic statistical profiling

Ensuring high-quality data before modeling helps improve both model reliability and business confidence.

---

# 🧹 Data Cleaning & Quality Assessment

Several preprocessing steps were completed to prepare the dataset for analysis and machine learning.

### Data Cleaning Activities

✔ Parsed customer joining dates.

✔ Calculated customer tenure.

✔ Converted financial attributes into numeric values.

✔ Identified missing values across all variables.

✔ Checked for duplicate observations.

✔ Validated categorical and numerical columns.

✔ Assessed data completeness before feature engineering.

Rather than aggressively removing observations, the workflow preserves customer information wherever possible and addresses missing values within the machine learning pipeline using appropriate imputation techniques.

---

# 📈 Exploratory Data Analysis

Exploratory analysis was conducted to understand customer behavior, financial characteristics, and overall data quality before building the predictive model.

The analysis included:

- Distribution analysis for numerical variables
- Customer demographic exploration
- Missing value visualization
- Outlier detection using the IQR method
- Correlation analysis using Spearman coefficients
- Categorical frequency analysis

These analyses helped identify meaningful financial relationships and informed the feature engineering process used during model development.

---


---
# ⚡ Feature Engineering

Raw financial balances alone rarely capture a customer's true financial behavior. To improve the predictive capability of the model, several domain-specific features were engineered using banking and lending concepts.

| Engineered Feature | Business Purpose |
|--------------------|------------------|
| **Credit Utilization** | Measures credit card balance relative to customer income |
| **Loan-to-Income Ratio** | Estimates the customer's debt burden |
| **Deposit-to-Loan Ratio** | Indicates financial liquidity and repayment capacity |
| **Cards per Income** | Normalizes credit usage by earning potential |
| **Total Accounts** | Represents the depth of the customer's banking relationship |
| **Customer Tenure** | Measures the duration of the banking relationship |

These engineered variables provide stronger indicators of financial health than raw monetary values and improve the model's ability to distinguish between low- and high-risk customers.

---

# 🤖 Machine Learning Pipeline

The objective of the predictive model is to estimate the likelihood that a customer belongs to the highest-risk segment of the lending portfolio.

An end-to-end **Scikit-Learn Pipeline** was implemented to automate preprocessing and model training, ensuring a reproducible workflow and preventing data leakage.

### Pipeline Workflow

```text
Raw Dataset
     │
     ▼
Missing Value Imputation
     │
     ▼
Feature Scaling
     │
     ▼
One-Hot Encoding
     │
     ▼
Logistic Regression
     │
     ▼
Customer Risk Probability
```

### Model Components

- SimpleImputer
- StandardScaler
- OneHotEncoder
- ColumnTransformer
- Logistic Regression

The target variable was derived from the existing **Risk Weighting** attribute, where customers in the top quartile were classified as **High Risk**.

Logistic Regression was selected because it provides a transparent and interpretable baseline, making it well suited for financial applications where model explainability is important.

---

# 📈 Model Performance

The model was evaluated using a hold-out test dataset to measure its ability to distinguish between high-risk and lower-risk customers.

| Metric | Score |
|---------|-------:|
| **ROC-AUC** | **0.891** |
| **Accuracy** | **81.6%** |
| **Precision** | **0.684** |
| **Recall** | **0.771** |

### Performance Summary

- Strong discrimination between high-risk and low-risk customers.
- Good recall for identifying customers requiring additional review.
- Probability-based predictions allow customers to be ranked by risk rather than simply classified.

The model achieved a **ROC-AUC of 0.891**, demonstrating effective separation between higher- and lower-risk customers while maintaining an interpretable modeling approach.

---

# 🎯 Customer Risk Scoring

Rather than assigning customers to a single risk category, the model generates a continuous **Risk Score** between **0** and **1**, representing the predicted likelihood of belonging to the high-risk segment.

Each customer is enriched with three business-ready outputs:

| Output | Description |
|---------|-------------|
| **Risk Score** | Probability of being classified as high risk |
| **Risk Band** | Low, Medium, or High risk category |
| **Risk Decile** | Relative ranking of customers from lowest to highest risk |

These outputs make the model immediately usable for downstream business applications such as portfolio monitoring, customer prioritization, and lending strategy.

---

# 💼 Operational Business Use Case

To demonstrate how predictive analytics can support business operations, the project identifies customers who require immediate attention based on both model predictions and financial health.

Customers meeting the following conditions are flagged for review:

- High Risk classification
- Low Deposit-to-Loan Ratio

This operational prioritization helps relationship managers and risk teams focus on customers who may require proactive intervention, making the model actionable beyond traditional reporting.

---
