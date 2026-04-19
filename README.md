# CUSTOMER BEHAVIOUR ANALYSIS

End-to-End Data Analytics Project (Python → MySQL → Power BI)

---

## Overview

This project analyzes customer purchasing behavior to generate actionable business insights across revenue, discounts, customer segmentation, product performance, and subscription behavior.

The project follows a complete data analytics pipeline:

**Data Cleaning (Python) → Data Storage (MySQL) → Analysis (SQL) → Visualization (Power BI)**

---

## Project Files

* `Customer_Behaviour_Portfolio_Project.ipynb` → Data cleaning and preprocessing
* `customer_behaviour_portfolio_project.sql` → SQL queries and analysis
* `CUSTOMER BEHAVIOUR ANALYSIS.docx` → Project documentation
* `Python Documentation.docx` → Detailed Python workflow
* `SQL ANALYSIS DOCUMENTATION.docx` → SQL explanations and insights
* `customer_shopping_behavior.csv` → Original dataset
* `customer_behaviour_dashboard.pbix` → Power BI dashboard
* Gamma Presentation → Project presentation

---

## Tech Stack

* Python (Pandas, NumPy, Matplotlib, Seaborn)
* MySQL
* SQL
* Power BI

---

## Data Processing (Python)

* Loaded dataset using Pandas
* Handled missing values using:

  * Group-based mean imputation
  * Mode-based categorical filling
* Corrected category mapping inconsistencies
* Standardized size across categories
* Engineered feature: `previous_purchases` using group-wise shift
* Removed duplicates and standardized column names

Full details available in:


---

## Database Setup (MySQL)

* Created database: `customer_behaviour`
* Created structured table: `customer_data`
* Inserted cleaned dataset using SQLAlchemy

---

## SQL Analysis

The project answers key business questions using advanced SQL techniques including:

* Aggregations (SUM, AVG, COUNT)
* Conditional aggregation (CASE WHEN)
* Subqueries
* CTE (Common Table Expressions)
* Window Functions (RANK)
* Customer segmentation

Full SQL documentation:


---

## Key Business Questions

1. Which category generates the highest revenue?
2. Are discounts increasing purchase value?
3. Revenue contribution by gender
4. High-spending discount users
5. Product rating analysis
6. Shipping type vs purchase behavior
7. Subscription impact on revenue
8. Discount-driven products
9. Customer segmentation
10. Repeat buyers vs subscription behavior
11. Top products within each category
12. Revenue contribution by age group

---

## Key Insights

* Electronics category generates the highest revenue
* Discounts increase average order value but not total revenue
* High-value customers often do not depend on discounts
* Subscribers have higher average spend but lower overall count
* Express shipping correlates with higher purchase value
* Senior citizens contribute the highest revenue
* Certain products are highly discount-sensitive
* Repeat buyers are not strongly converting to subscriptions

---

## Power BI Dashboard

An interactive dashboard was built to visualize insights from the database.

### Key Metrics

* Total Customers: ~5000
* Total Revenue: ~994K
* Average Spend: ~198
* Average Review Rating: ~3.63

### Dashboard Features

* Revenue breakdown by category, gender, and age
* Discount impact analysis
* Product performance insights
* Shipping behavior analysis
* Subscription vs non-subscription comparison
* Interactive filters for dynamic analysis

---

## Business Impact

* Enables targeted discount strategies
* Improves customer segmentation and retention
* Optimizes product and inventory decisions
* Enhances customer lifetime value (CLV) strategies
* Supports data-driven decision making

---

## How to Run

### 1. Python

Install dependencies:

```
pip install pandas numpy matplotlib seaborn sqlalchemy pymysql
```

Run:

```
Customer_Behaviour_Portfolio_Project.ipynb
```

---

### 2. MySQL

Run SQL file:

```
customer_behaviour_portfolio_project.sql
```

---

### 3. Power BI

* Open `.pbix` file
* Connect to MySQL:

```
Server: localhost  
Database: customer_behaviour  
Username: root  
Password: root123  
```

---

## Project Strength

* End-to-end analytics pipeline implementation
* Strong SQL proficiency (CTE, window functions, segmentation)
* Real-world business problem solving
* Interactive dashboard for decision-making

---

## Presentation Link

https://gamma.app/docs/Customer-Behaviour-Analysis-gnqownc5k8rtgc4

## Author

Sumit Paul

---
