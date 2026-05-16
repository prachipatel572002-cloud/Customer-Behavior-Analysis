# Customer Behavior Analysis

## 📖 Project Overview

This project focuses on analyzing customer purchasing behavior using **Python, MySQL, and Power BI**.

The objective of this project is to clean raw customer data, perform SQL-based analysis, and build an interactive dashboard to uncover meaningful business insights and customer trends.

---

## 🛠️ Tools & Technologies

- Python (Pandas)
- Jupyter Notebook
- MySQL
- Power BI

---

## 🧹 Data Cleaning & Preprocessing

Data cleaning and preprocessing were performed using Python in Jupyter Notebook.

### Cleaning Steps Performed

- Corrected incorrect data types
- Removed unnecessary columns
- Checked for missing/null values
- Identified missing values in the `review_rating` column
- Filled missing `review_rating` values using the median based on different product categories
- Standardized all column names into lowercase format
- Created a new `age_group` column for customer segmentation
- Created a new `frequency_purchase_days` column for purchase frequency analysis

---

## 📊 SQL Analysis

After preprocessing, the cleaned dataset was imported into MySQL for analysis.

SQL queries were used to analyze:

- Customer purchasing patterns
- Subscription behavior
- Discount impact on purchases
- Repeat buyer behavior
- Product performance
- Category-wise customer insights

---

## 📈 Power BI Dashboard

An interactive Power BI dashboard was created to visualize customer behavior, purchasing trends, and key business insights.

---

## 🔄 Project Workflow

Python (Data Cleaning & Preprocessing)

↓

MySQL (Data Analysis)

↓

Power BI (Dashboard Visualization)

---

## 📁 Project Files

| File Name | Description |
|---|---|
| `_cleaned_customer_behavior.ipynb` | Data cleaning and preprocessing using Python |
| `customer_behavior_queries.sql` | SQL queries used for analysis |
| `cleaned_customer_behavior.csv` | Cleaned dataset |
| `customer_analysis_dashboard(1).pbix` | Power BI dashboard file |
| `README.md` | Project documentation |
