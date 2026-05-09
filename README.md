# sql_retail_sales_P1
# 🛒 SQL Retail Sales Analysis

## 📌 Project Overview
This project focuses on analyzing retail sales data using SQL.  
The analysis helps uncover customer behavior, sales trends, product performance, and business insights through SQL queries.

The project demonstrates practical SQL skills including:
- Data Cleaning
- Data Exploration
- Aggregations
- Grouping
- Window Functions
- Business Problem Solving

---

## 🛠️ Tools & Technologies
- SQL
- PostgreSQL / MySQL
- DBMS

---

## 📂 Database & Table Structure

### Database Created
```sql
CREATE DATABASE sql_project_p2;
| Column Name    | Data Type |
| -------------- | --------- |
| transaction_id | INT       |
| sale_date      | DATE      |
| sale_time      | TIME      |
| customer_id    | INT       |
| gender         | VARCHAR   |
| age            | INT       |
| category       | VARCHAR   |
| quantity       | INT       |
| price_per_unit | FLOAT     |
| cogs           | FLOAT     |
| total_sale     | FLOAT     |

🧹 Data Cleaning Performed
Checked NULL values
Removed incomplete records
Verified transaction consistency

Example:
DELETE FROM retail_sales
WHERE transaction_id IS NULL
   OR sale_date IS NULL
   OR sale_time IS NULL;

📊 Business Problems Solved
✅ Q1. Sales made on a specific date

Retrieved all sales made on '2022-11-05'.

✅ Q2. Clothing transactions with quantity ≥ 4

Filtered clothing category sales in November 2022.

✅ Q3. Total sales by category

Calculated total revenue and total orders for each category.

✅ Q4. Average customer age

Found the average age of customers purchasing from the Beauty category.

✅ Q5. High-value transactions

Retrieved transactions where total sales exceeded 1000.

✅ Q6. Transactions by gender & category

Analyzed customer purchasing behavior based on gender.

✅ Q7. Best selling month each year

Used SQL Window Functions and RANK() for yearly best month analysis.

✅ Q8. Top 5 customers

Identified highest spending customers.

✅ Q9. Unique customers by category

Calculated distinct customers purchasing in each category.

✅ Q10. Sales shift analysis

Categorized orders into:

Morning
Afternoon
Evening
📈 Key SQL Concepts Used
SELECT Statements
WHERE Clause
GROUP BY
ORDER BY
Aggregate Functions
Window Functions
Common Table Expressions (CTE)
CASE Statements
Date Functions
🚀 Project Highlights

✔ Real-world retail sales analysis
✔ SQL query optimization practice
✔ Business-oriented problem solving
✔ Hands-on experience with data exploration
✔ Beginner-friendly SQL portfolio project

📁 Project Files
sql_query_p1.sql → Complete SQL analysis project
🎯 Learning Outcome

Through this project, I improved my understanding of:

SQL data analysis
Writing optimized queries
Extracting business insights from raw data
Data cleaning techniques
👨‍💻 Author
Soumyajeet Sur

Aspiring Data Analyst

Excel
SQL
Power BI (Learning)
Python (Learning)
⭐ If you like this project

Give this repository a ⭐ and share your feedback!
