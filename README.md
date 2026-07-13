<div align="center">

<img
src="https://github.com/user-attachments/assets/219a453f-cdc4-4bb0-ad8a-61299051de77"
width="650"
/>

</div>


![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python)
![Streamlit](https://img.shields.io/badge/WebApp-Streamlit-red?logo=streamlit)
![SQLite](https://img.shields.io/badge/Database-SQLite-blue)
![Machine Learning](https://img.shields.io/badge/AI-Machine%20Learning-success)
![XGBoost](https://img.shields.io/badge/Model-XGBoost-green)
![Power BI](https://img.shields.io/badge/Dashboard-PowerBI-yellow?logo=powerbi)
![Excel](https://img.shields.io/badge/Excel-Analysis-darkgreen?logo=microsoftexcel)

An AI-powered **Telecom Customer Churn Analysis & Prediction System** developed using **Python, Streamlit, SQL, SQLite, Machine Learning, and Business Intelligence**.

The project combines interactive dashboards, advanced customer analytics, predictive modeling, and business recommendations to help telecom companies identify customers at risk of churn and take proactive retention actions.

---

# Project Overview

Customer churn is one of the biggest challenges facing telecom companies.

This project transforms raw customer data into actionable business intelligence through:

- Interactive dashboards
Customer risk prioritization
- Revenue analysis
- Churn analysis
- Machine Learning prediction
- Risk explanation
- Business recommendations
- What-if simulation
- Executive insights

The goal is not only to predict customer churn, but also to explain **why** customers are likely to churn and recommend personalized retention strategies.

---

# Business Problem

Customer churn is one of the most significant challenges in the telecommunications industry.

Acquiring a new customer is considerably more expensive than retaining an existing one. Therefore, identifying customers who are likely to churn before they leave can significantly reduce revenue loss and improve customer retention strategies.

This project leverages Business Intelligence and Machine Learning techniques to help telecom companies:

- Identify customers at high risk of churn.
- Understand the key factors driving churn.
- Prioritize customers based on business impact.
- Recommend personalized retention actions.
- Support data-driven business decisions.

---

# Features

## Executive Dashboard

- Executive KPIs
- Customer Overview
- Churn Rate Analysis
- Revenue Analysis
- Revenue Loss Tracking
- Contract Type Analysis
- Customer Retention by Contract
- Churn by Tenure
- Churn Category Breakdown
- Top Churn Reasons
- Geographic Churn Analysis (Top 5 Cities)
- Interactive Filters & CSV Export
- Business Insights

---

## Customer & Revenue Dashboard

- Customer Demographics Analysis
- Senior vs Non-Senior Churn Analysis
- Revenue by Married Status
- Revenue by Payment Method
- Revenue Lost by Churn Category
- Churn Rate by Age Group
- Tech Support vs Internet Type Analysis
- Customer Revenue Analysis
- Interactive Filters & CSV Export
- Business Recommendations

---

## Machine Learning Module

- XGBoost Classification Model
- Customer Churn Prediction
- Customer Risk Score
- High / Medium / Low Risk Classification
- Probability-based Prediction
- Tuned Decision Threshold
- Customer Risk Explanation
- Personalized Business Recommendations
- High-Risk Customer Watchlist
- Top Customers Prioritization
- What-if Simulator
- Feature Importance Visualization
- Model Reliability Check
- Cross Validation
- Overfitting Detection

---

# Machine Learning Pipeline

```text
Raw Data
     │
     ▼
Data Cleaning
     │
     ▼
Feature Engineering
     │
     ▼
Preprocessing
│
├── Missing Value Handling
├── Standard Scaling
└── One-Hot Encoding
     │
     ▼
Random Under Sampling
     │
     ▼
XGBoost Classifier
     │
     ▼
Prediction

↓

Risk Classification

↓

Risk Explanation

↓

Business Recommendation

↓

High-Risk Customer Watchlist
```

---

# Technologies Used

| Technology | Purpose |
|------------|---------|
| Python | Programming Language |
| Streamlit | Web Application |
| SQLite | Database |
| Pandas | Data Manipulation |
| NumPy | Numerical Computing |
| Plotly | Interactive Charts |
| Scikit-learn | Machine Learning |
| XGBoost | Classification Model |
| Imbalanced-learn | Handling Imbalanced Data |

---

# Machine Learning Model

The final model was built using:

- XGBoost Classifier
- Business Feature Engineering
- One-Hot Encoding
- Random Under Sampling
- Stratified Train/Test Split
- 5-Fold Cross Validation
- Threshold Optimization
- Feature Importance Analysis

The model predicts the probability of customer churn and provides interpretable business recommendations.

---

# Model Evaluation

Metrics used for evaluation include:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC
- Confusion Matrix
- Cross Validation
- Overfitting Check

---

### Model Results:

| Metric | Score |
|--------|-------|
| Accuracy | ~84% |
| Recall | ~73% |
| F1 Score | ~71% |
| Train-Test Gap | ~0.7 pts (No Overfitting) |
| 5-Fold CV Mean | ~83% |

---

# Business Value

Unlike traditional churn prediction models that only classify customers as churn or non-churn, this project provides an end-to-end decision support system by:

- Predicting customer churn probability.
- Explaining why each customer is at risk.
- Generating personalized retention recommendations.
- Prioritizing high-value customers using a High-Risk Customer Watchlist.
- Allowing business users to simulate customer scenarios using a What-if Simulator.

The application bridges the gap between Machine Learning models and real business decision-making.

---

# Getting Started

### Clone Repository

```bash
git clone https://github.com/SalmaAbdelgelil/Telecom-Churn-Intelligence.git
```

---

### Navigate to Project

```bash
cd Telecom-Churn-Intelligence
```

---

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

### Run the Application

```bash
streamlit run app.py
```

---

# Screenshots

## Overview

<img width="1354" height="574" alt="image" src="https://github.com/user-attachments/assets/d7bd43cd-a8bd-4291-a59b-198722c80a4b" />


---

## Executive Dashboard

<img width="1358" height="577" alt="image" src="https://github.com/user-attachments/assets/e008a95a-69ae-4c11-8586-fa258e52f77d" />


---

## Customer Dashboard

<img width="1352" height="574" alt="image" src="https://github.com/user-attachments/assets/ba5d3b17-ff80-4cd5-9105-3d3951ede294" />


---

## Prediction Module
<img width="1348" height="635" alt="image" src="https://github.com/user-attachments/assets/cab77fc4-58e4-4605-aedd-5e4bdb6ecbe5" />
<img width="1345" height="630" alt="image" src="https://github.com/user-attachments/assets/f92c2631-a90a-48ae-82a2-be22dce5bcdc" />


---

## High-Risk Customer Watchlist

<img width="1351" height="637" alt="image" src="https://github.com/user-attachments/assets/caeb994c-780a-4252-8c9a-0c8b28478505" />
<img width="1352" height="634" alt="image" src="https://github.com/user-attachments/assets/19df3797-33da-4634-8deb-db4fb4e71b31" />


---

## What-if Simulator

<img width="1349" height="635" alt="image" src="https://github.com/user-attachments/assets/8f0fb3de-e2fe-4d42-bad4-94f6960d6260" />


---

# Future Improvements

- Customer Lifetime Value Prediction
- Explainable AI (SHAP)
- Real-time Prediction API
- Automated Customer Retention Campaigns
- Automated Reporting
- Cloud Deployment
- Multi-company Support

---

# Author

**Salma Abdelgelil**

GitHub:
https://github.com/SalmaAbdelgelil

LinkedIn:
https://www.linkedin.com/in/salma-abdelgelil-384790314
