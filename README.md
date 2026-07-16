# 🛒 Customer Shopping Behavior Analysis

## 📌 Project Overview

The **Customer Shopping Behavior Analysis** project is an end-to-end data analytics solution developed to analyze consumer purchasing patterns and generate actionable business insights for a retail company. The primary objective of this project is to help management understand how customer demographics, purchasing behavior, discounts, product preferences, seasonal trends, and subscription status influence sales performance and customer loyalty.

Using a dataset containing **3,900 customer transactions** across multiple product categories, the project demonstrates the complete data analytics pipeline—from raw data preprocessing and database management to business intelligence reporting. The analysis leverages **Python** for data cleaning and feature engineering, **PostgreSQL** for structured business analysis using SQL, and **Power BI** for interactive dashboard development.

The project aims to answer important business questions such as:

* Which customer segments generate the highest revenue?
* How do age, gender, and location influence purchasing behavior?
* What impact do discounts and promotional offers have on customer spending?
* Which products and categories perform the best?
* Are subscription customers more valuable than non-subscribers?
* How can the company improve customer retention and maximize profitability?

---

# 🎯 Business Problem

A leading retail company wanted to better understand its customers' shopping behavior to improve sales performance, customer satisfaction, and long-term loyalty. The company observed changing purchasing patterns across different customer demographics, product categories, and sales channels.

The objective of this project was to transform raw customer transaction data into meaningful insights that could support strategic business decisions in areas such as:

* Customer Segmentation
* Marketing Strategy
* Product Optimization
* Inventory Planning
* Customer Retention
* Revenue Growth

---

# 📂 Dataset Description

The dataset consists of **3,900 customer purchase records** with **18 attributes**, including customer demographics, purchase information, shopping preferences, and behavioral characteristics.

### Key Features

### Customer Information

* Age
* Gender
* Location
* Subscription Status

### Purchase Details

* Item Purchased
* Product Category
* Purchase Amount
* Season
* Color
* Size

### Shopping Behavior

* Discount Applied
* Previous Purchases
* Frequency of Purchases
* Shipping Type
* Review Rating
* Payment Method

---

# ⚙️ Project Workflow

The project follows a complete data analytics lifecycle consisting of three major phases.

## 1️⃣ Data Preparation and Cleaning (Python)

The first stage focused on preparing the raw dataset for analysis.

Major tasks included:

* Importing the dataset using Pandas
* Understanding data structure and distributions
* Detecting missing values
* Handling missing values in the **Review Rating** column using category-wise median imputation
* Renaming columns using snake_case naming convention
* Removing redundant attributes
* Creating new features for improved analysis:

  * Age Groups
  * Purchase Frequency (Days)
* Validating data consistency
* Loading the cleaned dataset into PostgreSQL

Python libraries used:

* Pandas
* NumPy
* Matplotlib
* Seaborn
* SQLAlchemy
* Psycopg2

---

## 2️⃣ Business Analysis using SQL

After cleaning the data, the dataset was imported into PostgreSQL where SQL queries were used to answer real-world business questions.

The analysis included:

### Customer Revenue Analysis

* Revenue contribution by gender
* Revenue by age group
* Average purchase value

### Customer Segmentation

Customers were categorized as:

* New Customers
* Returning Customers
* Loyal Customers

based on their purchase history.

### Product Analysis

The project identified:

* Top-selling products
* Top-rated products
* Best-performing categories
* Most discount-dependent products

### Customer Behavior Analysis

Business questions included:

* Do discounts increase purchase amount?
* Are subscribers spending more than non-subscribers?
* Does shipping preference affect purchase value?
* Are repeat customers more likely to purchase subscriptions?

Advanced SQL concepts used:

* Joins
* Window Functions
* CTEs
* Aggregate Functions
* Ranking Functions
* CASE Statements
* GROUP BY
* HAVING
* Subqueries

---

## 3️⃣ Interactive Dashboard Development (Power BI)

The final phase involved developing a comprehensive Power BI dashboard to visualize business insights for stakeholders.

The dashboard provides interactive analysis of:

* Sales Performance
* Customer Demographics
* Product Categories
* Subscription Analysis
* Revenue Distribution
* Seasonal Sales Trends
* Customer Segmentation
* Shipping Preferences
* Discount Usage
* Purchase Frequency

Interactive slicers enable users to explore data by:

* Age Group
* Gender
* Category
* Season
* Subscription Status
* Shipping Type

This allows decision-makers to quickly identify trends and make data-driven decisions.

---

# 📈 Key Insights Generated

The project uncovered several valuable business insights, including:

* Subscribers generally contribute higher overall revenue than non-subscribers.
* Loyal customers account for a significant share of total sales and should be prioritized through retention programs.
* Certain products rely heavily on discounts to drive purchases, highlighting opportunities to optimize pricing strategies.
* Top-rated products consistently outperform others, suggesting customer reviews strongly influence purchasing decisions.
* Seasonal trends affect purchasing behavior, enabling better inventory and promotional planning.
* Express shipping users tend to have higher average purchase values, indicating a segment with greater spending potential.

---

# 💡 Business Recommendations

Based on the analysis, the following recommendations were proposed:

* Introduce personalized loyalty programs to encourage repeat purchases.
* Promote exclusive subscription benefits to increase customer retention.
* Optimize discount strategies to improve profitability while maintaining sales volume.
* Focus marketing campaigns on high-value customer segments and top-performing age groups.
* Highlight highly rated and frequently purchased products in promotional campaigns.
* Use seasonal purchasing patterns to improve inventory management and demand forecasting.
* Offer targeted promotions based on customer purchase history and shopping preferences.

---

# 🛠️ Technology Stack

| Category        | Technologies              |
| --------------- | ------------------------- |
| Programming     | Python                    |
| Data Processing | Pandas, NumPy             |
| Database        | PostgreSQL                |
| SQL             | PostgreSQL SQL            |
| Visualization   | Power BI                  |
| IDE             | Jupyter Notebook, VS Code |
| Version Control | Git & GitHub              |

---

# 📁 Repository Structure

```text
Customer-Shopping-Behavior-Analysis/
│
├── data/
│   ├── raw_dataset.csv
│   └── cleaned_dataset.csv
│
├── python/
│   ├── data_cleaning.py
│   ├── feature_engineering.py
│   └── eda.ipynb
│
├── sql/
│   ├── database_schema.sql
│   ├── data_import.sql
│   └── business_queries.sql
│
├── powerbi/
│   └── Customer_Shopping_Dashboard.pbix
│
├── report/
│   └── Project_Report.pdf
│
├── presentation/
│   └── Project_Presentation.pptx
│
└── README.md
```

---

# 🚀 Learning Outcomes

This project demonstrates practical experience in:

* Data Cleaning and Preprocessing
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Relational Database Design
* SQL for Business Analytics
* Customer Segmentation
* Business Intelligence Reporting
* Dashboard Development
* Data Storytelling
* End-to-End Analytics Project Development

The project showcases how Python, SQL, and Power BI can be integrated into a complete analytics workflow to convert raw retail transaction data into meaningful insights that support strategic business decision-making.
