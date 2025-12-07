📘 Customer Shopping Behavior Analysis — Complete EDA Project

A complete end-to-end Exploratory Data Analysis (EDA) project using
Python + SQL + Power BI, based on a dataset of 3,900 customers.

This project analyzes customer purchase patterns, revenue drivers, discount behavior, loyalty segments, and product performance.

🔍 Project Overview

This project covers:

✔ 1. Data Cleaning & Preprocessing (Python)

Loaded CSV file into Pandas

Checked datatypes & missing values

Cleaned inconsistencies

Created additional features:

age_group

purchase_frequency_days

Exported cleaned data into MySQL table using SQLAlchemy

✔ 2. SQL-Based Business Insights

Wrote 10 analytical SQL queries to answer:

Revenue by gender

High-value discount customers

Top-rated products

Express vs Standard shipping spend

Subscriber vs non-subscriber revenue

Top discounted products

Customer segmentation (New / Returning / Loyal)

Top 3 products per category

Repeat buyer behavior

Revenue contribution by age groups

✔ 3. Data Visualization (Power BI Dashboard)

Created a professional dashboard with:

Revenue trends

Product performance

Customer segmentation

Discount usage analysis

Age groups & subscription insights

📂 Folder Structure
Customer-Shopping-Behavior-Analysis/
│
├── data/
│   └── customer_shopping_behavior.csv
│
├── python/
│   └── data_cleaning.ipynb
│
├── sql/
│   └── analysis_queries.sql
│
├── dashboard/
│   └── customer_data_eda.pbix
│
└── README.md

🐍 Python Code Summary

Loaded CSV & inspected data

Handled missing values

Converted columns to clean format

Added age group categories

Loaded data into MySQL using SQLAlchemy

Verified table upload with sample query

🛢️ SQL Queries Included

The SQL file contains:

1️⃣ Revenue by gender
2️⃣ Discount users spending above average
3️⃣ Highest rated products
4️⃣ Average purchase by shipping type
5️⃣ Subscriber spending comparison
6️⃣ Products with highest discount usage
7️⃣ Customer segmentation (New/Returning/Loyal)
8️⃣ Top products in each category
9️⃣ Subscription behavior of repeat customers
🔟 Revenue contribution by age groups

📊 Power BI Dashboard

Includes visualizations for:

Total Revenue

Average Spend

Customer Demographics

Subscription vs Spending

Product-wise performance

Discount analysis

Customer loyalty segmentation

🚀 How to Run the Project
1. Python
pip install pandas sqlalchemy pymysql
python data_cleaning.ipynb

2. SQL

Import analysis_queries.sql into MySQL Workbench or run directly.

3. Power BI

Open customer_data_eda.pbix in Power BI Desktop.

📝 Author

Jahnavi Rai
M.Sc. Statistics | Data Analyst | SQL • Python • Power BI
