# 📊 Customer Churn Analysis – Power BI

## 📌 Project Overview

This project is an end-to-end Customer Churn Analysis project developed using **Python, Pandas, NumPy, Jupyter Notebook, MySQL, SQL, and Microsoft Power BI**.

The project focuses on cleaning customer data, performing data analysis, creating calculated features, analyzing customer churn, performing SQL analysis, creating DAX measures, and developing an interactive Power BI dashboard.

---

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Jupyter Notebook
- MySQL
- SQL
- Microsoft Power BI
- DAX

**Data Source:** Excel (`.xlsx`) file loaded into Python using Pandas.

---

## 🎯 Project Objectives

- Clean and prepare customer churn data.
- Handle missing and inconsistent values.
- Remove duplicate records.
- Validate customer data.
- Perform data analysis using Python.
- Use Pandas and NumPy for data cleaning and transformation.
- Create new analytical features.
- Store the cleaned data in MySQL.
- Perform business analysis using SQL.
- Create DAX measures in Power BI.
- Build an interactive customer churn dashboard.
- Identify customer churn patterns.
- Present business insights through data visualization.

---

## 🧠 Project Goal

The main goal of this project is to analyze customer churn and understand patterns related to:

- Customer behavior
- Contract type
- Subscription type
- Payment method
- Internet service
- Monthly charges
- Customer tenure
- Senior citizen status
- Revenue

The final objective is to transform raw customer data into meaningful business insights using Python, SQL, and Power BI.

---

## 🔄 Project Workflow

```text
Raw Customer Data
        ↓
Python / Jupyter Notebook
        ↓
Pandas + NumPy
        ↓
Data Cleaning & Transformation
        ↓
Feature Engineering
        ↓
Cleaned CSV
        ↓
MySQL + SQL Analysis
        ↓
Power BI
        ↓
DAX Measures
        ↓
Interactive Dashboard
        ↓
Business Insights
🐍 Python-Based Customer Churn Analysis

Python was used for data cleaning, preparation, transformation, and analysis.

Pandas

Pandas was used for:

Loading the dataset
Exploring the dataset
Checking missing values
Checking duplicate records
Removing duplicates
Replacing dirty values
Cleaning text fields
Standardizing categorical values
Filtering invalid records
Converting dates
Handling missing values
Exporting the cleaned dataset
NumPy

NumPy was used for:

Numerical operations
Data processing
Feature engineering
Creating customer classification flags
Jupyter Notebook

Jupyter Notebook was used to document and perform the complete Python data-cleaning workflow.

🧹 Data Cleaning

The raw dataset initially contained:

542 rows
18 columns

The cleaning process included:

Duplicate removal
Dirty-value replacement
Extra-space removal
Proper-case standardization
Age validation
Negative-charge removal
Date conversion
Missing-value handling
Data-type validation

After cleaning and transformation, the dataset contained:

492 rows
23 columns
⚙️ Feature Engineering

The following analytical columns were created during the Python workflow:

Customer_Value
Customer_Value = Monthly_Charges × Tenure_Months
Monthly_Revenue
Monthly_Revenue = Monthly_Charges
Tenure_Group

Customers were grouped into:

0–12 Months
13–24 Months
25–48 Months
49–72 Months
Senior_Flag

Customers were classified based on age:

Adult
Senior
Churn_Flag

The churn status was converted into a numerical flag:

Yes = 1
No  = 0
🗄️ MySQL & SQL

The cleaned dataset was exported to MySQL using SQLAlchemy and PyMySQL.

MySQL Database
Database: churndb
Table: customer_churn

SQL was used for:

Customer analysis
Churn analysis
Filtering
Grouping
Aggregation
Contract analysis
Payment method analysis
Service analysis
Revenue analysis
📊 Power BI Dashboard

Microsoft Power BI was used to create the Customer Churn Analysis Dashboard.

The dashboard contains KPI cards, charts, slicers, and interactive visualizations.

📈 Dashboard KPIs

The dashboard displays the following KPIs:

KPI	Dashboard Value
Total Customers	445
Churn Customers	105
Retained Customers	340
Churn Rate	23.60%
Total Revenue	22.16M
Average Monthly Charges	1.36K
Average Tenure	35.95
📐 DAX

DAX was used to create Power BI measures for the dashboard.

The dashboard includes measures for:

Total Customers
Churn Customers
Retained Customers
Churn Rate
Total Revenue
Average Monthly Charges
Average Tenure

These measures are used in the KPI cards and dashboard visualizations.

📊 Dashboard Features

The dashboard includes:

1. Churned Customers by Contract Type

Shows churned customers across:

Two Year
One Year
Month-To-Month
2. Churned Customers by Subscription Type

Shows churned customers across:

Standard
Premium
Basic
3. Monthly Charges vs Churned Customers

Shows the relationship between:

Total Monthly Charges
Churned Customers
4. Churned Customers by Payment Method

Shows churned customers by:

UPI
Debit Card
Credit Card
Net Banking
Cash
5. Total Revenue by State

Shows total revenue across the major states displayed in the dashboard.

6. Churned Customers by Internet Service

Shows churned customers across:

Cable
5G
Fiber
DSL
7. Churned Customers by Senior Citizen Status

Shows churned customers by:

Yes
No
8. Subscription Type Slicer

The dashboard provides a slicer for:

Basic
Premium
Standard

This allows interactive filtering of the dashboard.

📊 Dashboard Preview
![Customer Churn Analysis Dashboard](Customer_Churn_Dashboard.png)
📂 Project Structure
Customer-Churn-Analysis-Power-BI/
│
├── README.md
│
├── Churn_Unclean_Project.xlsx
│
├── Clean_Churn_Data.csv
│
├── Churn Dataset Cleaning.ipynb
│
├── Customer_Churn_Analysis_Dashboard.pbix
│
└── Customer_Churn_Dashboard.png
