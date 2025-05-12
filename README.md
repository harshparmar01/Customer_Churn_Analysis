# 📊 Telecom Customer Churn Analysis

This project analyzes customer churn behavior in a telecom company using Python (for data cleaning and exploration) and Power BI (for interactive visualization). The goal is to uncover patterns behind customer churn and provide insights that can help reduce attrition.

---

## 📌 Objective

To identify key factors contributing to customer churn and visualize these insights using an interactive Power BI dashboard.

---

## 🛠 Tools Used

- Python (Pandas, NumPy, Seaborn, Matplotlib)
- Google Colab / Jupyter Notebook
- Power BI (for dashboard)
- Git & GitHub (for version control)

---

## 🧩 Dataset Overview

The dataset contains details of ~7,000 telecom customers including:

- Customer demographics (gender, senior citizen status, etc.)
- Subscription details (contract type, payment method, etc.)
- Service usage (tenure, internet service, etc.)
- Churn label ("Yes" or "No")

---

## 🔄 Workflow Summary

1. **Data Cleaning (Python)**
   - Converted data types
   - Handled missing and inconsistent values
   - Transformed features (e.g., tenure grouping, label encoding)
   - Exported a cleaned dataset to `.csv`

2. **Exploratory Data Analysis (EDA)**
   - Categorical vs Churn (bar plots)
   - Numerical vs Churn (box plots)
   - Correlation heatmap

3. **Power BI Dashboard**
   - KPI Cards (Total customers, churned, avg. tenure, etc.)
   - Bar charts by contract type, payment method, and internet service
   - Slicers: Tenure group, Contract, Gender
   - Interactive filtering

---

## 🔍 Key Insights

- Customers on **month-to-month contracts** had the highest churn.
- **Electronic check** users showed significantly higher churn.
- **Short-tenure customers** (<12 months) were more likely to leave.
- **Senior citizens** and **fiber optic users** churned more frequently.

---

## 📁 Files in This Repo

| File/Folder | Description |
|-------------|-------------|
| `churn_analysis.ipynb` | Cleaned and analyzed dataset using Python |
| `cleaned_dataset.csv` | Final cleaned dataset |
| `PowerBI_Dashboard.pdf` | Exported view of the Power BI dashboard |
| `visuals/` | Folder containing visualizations |
| `README.md` | This documentation file |

