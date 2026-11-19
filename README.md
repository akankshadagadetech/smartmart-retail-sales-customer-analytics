# SmartMart Retail Sales & Customer Intelligence Analytics

## 1. Project Overview
SmartMart Retail Sales & Customer Intelligence Analytics is a SQL-based data analytics project developed using MySQL. The project focuses on analyzing retail sales, customer purchasing behavior, product performance, and employee sales contributions.

The goal is to transform retail data into meaningful business insights that can support better business decisions.

## 2. Project Objectives
- Analyze customer purchasing behavior.
- Identify top-performing products and categories.
- Calculate total and monthly sales revenue.
- Analyze customer spending and segmentation.
- Evaluate employee sales performance.
- Identify high-value customers and orders.
- Understand sales trends and business performance.
- Generate meaningful insights using SQL queries.

## 3. Tools & Technologies
- MySQL 8.0+
- MySQL Workbench
- SQL

## 4. Database Structure

The project contains five relational database tables:

| Table Name | Description |
|---|---|
| Customers | Stores customer information |
| Employees | Stores employee details |
| Products | Stores product information |
| Orders | Stores customer order details |
| Order_Items | Stores individual products in each order |

## 5. Dataset Information

The database contains approximately 87,000 records.

| Table | Number of Records |
|---|---:|
| Customers | 20,000 |
| Employees | 2,000 |
| Products | 5,000 |
| Orders | 20,000 |
| Order_Items | 40,000 |
| **Total** | **87,000** |

The dataset is generated using SQL queries and recursive CTEs.

## 6. SQL Analysis Performed

This project includes 30 SQL analysis topics divided into six sections.

### A. Customer Analysis
- Total Customer Count
- City-Wise Customer Distribution
- Top 10 Customers by Revenue
- Repeat Customer Analysis
- Customers Who Have Not Purchased
- Customer Segmentation Based on Spending

### B. Product Analysis
- Top Products by Revenue
- Top Products by Quantity Sold
- Products Never Sold
- Category-Wise Revenue
- Low-Performing Products
- Product Ranking by Revenue

### C. Sales Analysis
- Total Revenue
- Monthly Revenue Trend
- Quarterly Revenue Trend
- Average Order Value
- High-Value Orders

### D. Employee Analysis
- Employee Revenue Contribution
- Top 10 Employees
- Employees With No Sales

### E. Advanced Business Analysis
- Pareto Analysis – Customer Revenue Concentration
- Running Monthly Revenue
- Month-over-Month Revenue Change
- Products Above Average Revenue
- Customers Above Average Spending

### F. SQL Advanced Concepts
- Creating SQL Views
- Index Analysis
- Monthly Sales Stored Procedure Execution
- UNION Operations
- UNION ALL Operations

## 7. SQL Concepts Used
- SELECT, WHERE, ORDER BY
- GROUP BY and HAVING
- INNER JOIN and LEFT JOIN
- Aggregate Functions
- Subqueries
- Common Table Expressions (CTEs)
- Window Functions
- DENSE_RANK()
- NTILE()
- LAG()
- UNION and UNION ALL
- Views
- Indexes
- Stored Procedure Calls

## 8. Key Business Insights
The project is designed to help businesses:
- Identify valuable customers.
- Understand product and category performance.
- Monitor monthly and quarterly revenue.
- Evaluate employee contributions.
- Identify products with low sales.
- Understand customer revenue concentration.

## 9. How to Run This Project

1. Download or clone this repository.
2. Open MySQL Workbench.
3. Execute `SmartMart_Retail_SQL_Data_Generation_MySQL.sql` first.
4. The database and five tables will be created with sample records.
5. Open `Smartmart_analysis (4-6) New.sql`.
6. Execute the analysis queries section by section.
7. Review the results and business insights.

## 10. Project Files

- `SmartMart_Retail_SQL_Data_Generation_MySQL.sql` – Database creation, table creation, sample data generation, and indexes.
- `Smartmart_analysis (4-6) New.sql` – Customer, product, sales, employee, and advanced business analysis queries.

## 11. Author

**Akanksha Dagade**

Aspiring Data Analyst | SQL | Python | Excel | Power BI

GitHub: https://github.com/akankshadagadech

