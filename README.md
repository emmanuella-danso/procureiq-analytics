# ProcureIQ Analytics — Procurement Intelligence Project

## Overview

ProcureIQ Analytics is an end-to-end procurement intelligence project designed to analyze supplier performance, procurement spend, operational risk, negotiated savings, and forecasting trends using Python, SQL, and Power BI.

This project combines procurement analytics with predictive modelling and executive dashboard reporting to support data-driven procurement decision-making.

---

# Business Problems Solved

This project answers the following procurement questions:

- Which suppliers account for the highest procurement spend?
- Which suppliers have the worst delivery delays?
- Which suppliers produce the highest defect rates?
- Are negotiated prices reducing procurement costs?
- Which suppliers are high-spend but low-performance?
- Which procurement categories generate the highest savings?
- Can procurement spend be forecasted using predictive modelling?
- Which suppliers represent operational procurement risk?

---

# Interactive Dashboard

### Power BI Dashboard
[View Interactive Power BI Dashboard](https://drive.google.com/file/d/1NYTqCDdyOxIjGpjk84kQT45Q3IO-dnkh/view?usp=sharing)

---

# Full Project Report

### Procurement Intelligence Report (PDF)
[View Full Report](https://github.com/emmanuella-danso/procureiq-analytics/blob/main/Danso_Emmanuella_ProcureIQ_Analytics_Report.pdf)

---

# Tools & Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- SQLite
- Power BI
- Jupyter Notebook

---

# Project Workflow

## 01 — Data Understanding
- Initial data inspection
- Data quality assessment
- Missing value analysis
- Procurement structure validation

---

## 02 — Exploratory Data Analysis
- Supplier spend analysis
- Procurement category analysis
- Delivery delay analysis
- Defect trend analysis
- Compliance tracking

---

## 03 — Feature Engineering
Created procurement KPIs and engineered features including:

- Delivery_Delay_Days
- Savings_Per_Unit
- Total_Savings
- Defect_Rate
- Rolling averages
- Lag features
- Growth rate calculations

---

## 04 — Predictive Modelling
Built and evaluated multiple forecasting models:

### Models Used
- Linear Regression
- Random Forest Regressor
- Gradient Boosting Regressor

### Best Model Performance
- R² Score: 0.967
- MAE: 350.37

Forecasting was used to predict future procurement savings and identify procurement spend trends over time.

---

## 05 — SQL Validation
Validated procurement metrics using SQL queries and SQLite to ensure analytical consistency and reporting accuracy.

---

## 06 — Power BI Metrics Preparation
Prepared production-ready CSV datasets for dashboard reporting and procurement KPI visualization in Power BI.

---

# Key Business Insights

## Supplier Risk Analysis
Delta Logistics was identified as the highest-risk supplier due to:
- High defect rates
- Low compliance rate
- Significant procurement spend exposure

---

## Procurement Savings
Negotiated supplier pricing generated substantial procurement savings across multiple procurement categories.

---

## Forecasting Insights
Procurement forecasting identified strong fluctuations in monthly procurement savings and spend patterns.

---

## Operational Recommendations
The project recommends:
- Supplier performance reviews
- Compliance monitoring
- SLA optimization
- Procurement risk mitigation
- Spend concentration management

---

# Power BI Dashboard Features

The dashboard includes:

- Executive Procurement Overview
- Supplier Risk Scorecards
- Spend Forecasting Trends
- Procurement Category Analysis
- Compliance Monitoring
- Supplier Performance Tracking
- Procurement KPI Monitoring
- 
- ### Power BI Dashboard
[View Interactive Power BI Dashboard](https://drive.google.com/file/d/1NYTqCDdyOxIjGpjk84kQT45Q3IO-dnkh/view?usp=sharing)


---

# Repository Structure

```bash
procureiq-analytics/
│
├── notebooks/
├── outputs/
├── powerbi/
├── reports/
├── data/
└── README.md
```

---

# Files Included

- Procurement Intelligence Report (PDF)
- Power BI Dashboard
- Jupyter Notebooks
- SQL Validation Workflows
- Power BI CSV Outputs
- Procurement Forecasting Models

---

# Business Value Delivered

This project demonstrates how procurement analytics can:
- Reduce supplier risk
- Improve procurement visibility
- Support strategic sourcing
- Improve supplier accountability
- Enable data-driven procurement decisions
- Forecast procurement trends proactively

---

# Author

## Danso Emmanuella

### GitHub
https://github.com/emmanuella-danso

### LinkedIn
https://www.linkedin.com/in/emmanuella-danso-699b54404/

---

# Project Status

Completed — End-to-End Procurement Intelligence Analytics Pipeline
