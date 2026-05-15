Grocery Management System using SQL
📌 Project Overview

The Grocery Management System is a SQL-based database project designed to manage and analyze grocery store operations efficiently. This project focuses on handling key business areas such as suppliers, products, customers, employees, orders, and sales analysis.

It helps in understanding business performance through SQL queries by generating insights related to:

Customer purchasing behavior
Product performance
Sales trends
Supplier contribution
Employee performance
Order-level analysis

This project demonstrates strong skills in Database Design, SQL Query Writing, Data Analysis, and Business Intelligence.

🗂 Database Name
grocery_db
🏗 Database Schema

The project consists of the following 7 tables:

1. Supplier

Stores supplier information.

Column Name	Data Type
sup_id	TINYINT (PK)
sup_name	VARCHAR
address	TEXT
2. Categories

Stores product categories.

Column Name	Data Type
cat_id	TINYINT (PK)
cat_name	VARCHAR
3. Employees

Stores employee details.

Column Name	Data Type
emp_id	TINYINT (PK)
emp_name	VARCHAR
hire_date	VARCHAR
4. Customers

Stores customer details.

Column Name	Data Type
cust_id	SMALLINT (PK)
cust_name	VARCHAR
address	TEXT
5. Products

Stores product information.

Column Name	Data Type
prod_id	TINYINT (PK)
prod_name	VARCHAR
sup_id	TINYINT (FK)
cat_id	TINYINT (FK)
price	DECIMAL
6. Orders

Stores customer orders.

Column Name	Data Type
ord_id	SMALLINT (PK)
cust_id	SMALLINT (FK)
emp_id	TINYINT (FK)
order_date	VARCHAR
7. Order Details

Stores detailed order transactions.

Column Name	Data Type
ord_detID	SMALLINT (PK, AI)
ord_id	SMALLINT (FK)
prod_id	TINYINT (FK)
quantity	TINYINT
each_price	DECIMAL
total_price	DECIMAL
📊 Analysis Performed
1. Customer Insights
Unique customers who placed orders
Customers with highest number of orders
Total and average purchase value per customer
Top 5 customers by total purchase amount
2. Product Performance
Products available in each category
Average price by category
Highest sales volume products
Product-wise revenue generation
Sales variation by category and supplier
3. Sales & Order Trends
Total number of orders
Average order value
Most active order dates
Monthly order volume and revenue trends
Weekday vs Weekend sales patterns
4. Supplier Contribution
Total suppliers in database
Supplier with maximum products
Average product price by supplier
Supplier contribution to total revenue
5. Employee Performance
Employees handling orders
Top-performing employees by order count
Employee-wise total sales
Average order value handled per employee
6. Order Details Deep Dive
Quantity vs Total Price relationship
Average quantity ordered per product
Product-wise unit price variation
🛠 SQL Concepts Used
DDL (CREATE DATABASE, CREATE TABLE)
DML
JOINS (INNER JOIN)
GROUP BY
ORDER BY
AGGREGATE FUNCTIONS
COUNT()
SUM()
AVG()
DISTINCT
Common Table Expressions (CTE)
DATE FUNCTIONS
STR_TO_DATE()
DATE_FORMAT()
DAYOFWEEK()
FOREIGN KEY Constraints
CASCADE Operations
🎯 Key Business Insights
Identified top customers contributing maximum revenue
Found best-selling products and high-performing categories
Tracked supplier contribution to sales
Measured employee productivity
Compared weekday and weekend sales patterns
Evaluated monthly revenue growth trends
🚀 Tools Used
MySQL
SQL Workbench / MySQL Workbench
GitHub
