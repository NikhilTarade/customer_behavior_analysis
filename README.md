# customer_behavior_analysis
This project analyzes customer shopping behavior using Python, PostgreSQL, and Power BI to uncover valuable business insights from transactional data. The workflow covers data cleaning, SQL-based analysis, and interactive dashboard development to support data-driven decision-making.
# 🛍️ Customer Shopping Behavior Analysis

An end-to-end Data Analytics project that analyzes customer shopping behavior using **Python**, **PostgreSQL**, **SQL**, and **Power BI**. The project focuses on cleaning raw data, performing business analysis, and building an interactive dashboard to generate actionable business insights.

---

# 📌 Table of Contents

- Project Overview
- Problem Statement
- Objectives
- Dataset Information
- Technology Stack
- Project Workflow
- Data Cleaning & Preprocessing
- Database Integration
- SQL Business Analysis
- Power BI Dashboard
- Key Business Insights
- Business Recommendations
- Project Structure
- How to Run the Project
- Future Improvements
- Author

---

# 📖 Project Overview

Customer shopping data contains valuable information that helps businesses understand purchasing behavior, customer preferences, and revenue trends.

This project demonstrates the complete data analytics workflow:

- Data Cleaning using Python
- Database Integration using PostgreSQL
- Business Analysis using SQL
- Dashboard Creation using Power BI

---

# 🎯 Problem Statement

Retail businesses collect large amounts of customer transaction data but often struggle to extract meaningful insights.

This project aims to transform raw shopping data into business insights that help improve:

- Customer Retention
- Revenue Growth
- Marketing Strategies
- Product Performance
- Subscription Analysis

---

# 🎯 Objectives

- Clean and preprocess customer shopping data.
- Handle missing values.
- Store cleaned data in PostgreSQL.
- Perform SQL-based business analysis.
- Build an interactive Power BI dashboard.
- Generate business recommendations.

---

# 📊 Dataset Information

**Dataset Name:**
Customer Shopping Trends Dataset

### Dataset Summary

- Total Records: **3900**
- Total Features: **18**

### Features

- Customer ID
- Age
- Gender
- Item Purchased
- Category
- Purchase Amount
- Location
- Size
- Color
- Season
- Review Rating
- Subscription Status
- Shipping Type
- Discount Applied
- Promo Code Used
- Previous Purchases
- Payment Method
- Frequency of Purchases

---

# 🛠 Technology Stack

| Tool | Purpose |
|------|----------|
| Python | Data Cleaning & Analysis |
| Pandas | Data Manipulation |
| NumPy | Numerical Operations |
| PostgreSQL | Database |
| SQLAlchemy | Python-PostgreSQL Connection |
| SQL | Business Analysis |
| Power BI | Dashboard & Visualization |
| Jupyter Notebook | Development |

---

# 🔄 Project Workflow

```
Dataset
     ↓
Python Data Cleaning
     ↓
Feature Engineering
     ↓
PostgreSQL Database
     ↓
SQL Analysis
     ↓
Power BI Dashboard
     ↓
Business Insights
```

---

# 🧹 Data Cleaning & Preprocessing

The following preprocessing steps were performed:

- Imported dataset using Pandas
- Checked data types
- Removed duplicate records
- Handled missing values
- Standardized column names
- Created Age Group feature
- Checked data consistency
- Prepared data for SQL analysis

---

# 🗄 Database Integration

The cleaned dataset was loaded into PostgreSQL using SQLAlchemy.

### Steps

- Created PostgreSQL database
- Connected using SQLAlchemy
- Imported cleaned DataFrame
- Stored data as SQL table

---

# 📝 SQL Business Analysis

The following SQL queries were performed:

- Revenue by Gender
- Subscribers vs Non-Subscribers
- Top Rated Products
- Revenue by Age Group
- Shipping Type Comparison
- Customer Segmentation
- Top Products by Category
- Repeat Buyer Analysis
- Discount Analysis
- Revenue Contribution Analysis

---

# 📈 Power BI Dashboard

The interactive dashboard includes:

### KPI Cards

- Total Customers
- Average Purchase Amount
- Average Review Rating

### Charts

- Revenue by Category
- Sales by Category
- Revenue by Age Group
- Sales by Age Group
- Subscription Status Distribution

### Interactive Filters

- Gender
- Category
- Shipping Type
- Subscription Status

---

# 📊 Key Business Insights

- Clothing category generated the highest revenue.
- Young Adults contributed the highest revenue.
- Non-subscribers represent the majority of customers.
- Customers with subscriptions tend to make frequent purchases.
- Revenue varies significantly across product categories.
- Customer segmentation helps identify loyal customers.

---

# 💡 Business Recommendations

- Increase subscription benefits.
- Launch customer loyalty programs.
- Optimize discount strategies.
- Promote high-performing products.
- Use targeted marketing based on customer age groups.
- Improve customer retention campaigns.

---

# 📁 Project Structure

```
Customer-Shopping-Behavior-Analysis/

│
├── Dataset/
│     └── shopping_trends.csv
│
├── Python/
│     └── Data_Cleaning.ipynb
│
├── SQL/
│     └── SQL_Queries.sql
│
├── Dashboard/
│     └── Customer_Behavior_Dashboard.pbix
│
├── Report/
│     └── Customer_Shopping_Behavior_Analysis.pdf
│
├── Images/
│     └── Dashboard.png
│
├── README.md
│
└── requirements.txt
```

---

# ▶️ How to Run the Project

### Clone Repository

```bash
git clone https://github.com/yourusername/Customer-Shopping-Behavior-Analysis.git
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Jupyter Notebook

```bash
jupyter notebook
```

### Import Dataset

Load the dataset into the notebook.

### Load Data into PostgreSQL

Run the SQLAlchemy connection script.

### Execute SQL Queries

Run the SQL scripts in PostgreSQL.

### Open Dashboard

Open the `.pbix` file using Power BI Desktop.

---

# 🚀 Future Improvements

- Build an ETL pipeline.
- Deploy dashboard to Power BI Service.
- Add Machine Learning models.
- Create customer churn prediction.
- Build a Streamlit web application.
- Automate data refresh.

---

# 📷 Dashboard Preview

> Add your Power BI dashboard screenshot here.

Example:

```
![Dashboard](Images/Dashboard.png)
```

---

# 👨‍💻 Author

**Nikhil Tarade**

**M.Sc.  Applied Statistics and Informatics**

Aspiring Data Analyst | SQL | Python | Power BI | PostgreSQL

---

# ⭐ If you found this project useful, don't forget to Star this repository!
