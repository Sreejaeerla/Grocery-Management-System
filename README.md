Grocery Store Database Analysis using SQL
📌 Project Overview

This project focuses on designing and analyzing a Grocery Store Database using MySQL.
The database includes information related to:

Customers
Orders
Products
Categories
Suppliers
Employees
Order Details

The project demonstrates how SQL can be used for:

Database creation
Table relationships
Data analysis
Business insights generation
Sales and customer analytics
🗂️ Database Schema

The project contains the following tables:

Table Name	Description
supplier	Stores supplier details
categories	Stores product category information
employees	Stores employee details
customers	Stores customer information
products	Stores product details
orders	Stores customer order records
order_details	Stores product-level order information
🔗 Relationships
One supplier can supply many products
One category can contain many products
One customer can place many orders
One employee can process many orders
One order can contain multiple products

Foreign keys are implemented using:

ON UPDATE CASCADE
ON DELETE CASCADE
⚙️ Technologies Used
MySQL
SQL Queries
Relational Database Design

📊 Analysis Performed

1️⃣ Customer Insights
Unique customers who placed orders
Customers with highest orders
Total & average purchase value per customer
Top 5 customers by revenue

2️⃣ Product Performance
Products count by category
Average product price by category
Highest selling products by quantity
Product-wise revenue analysis
Sales by category and supplier

3️⃣ Sales & Order Trends
Total orders placed
Average order value
Peak order dates
Monthly sales trends
Weekday vs Weekend order analysis

4️⃣ Supplier Contribution
Total suppliers
Supplier with maximum products
Average product price by supplier
Supplier revenue contribution

5️⃣ Employee Performance
Employees processing orders
Employees handling maximum orders
Total sales processed by employees
Average order value handled by employees

6️⃣ Order Details Deep Dive
Quantity vs total price relationship
Average quantity ordered per product
Product-wise unit price analysis

🧠 Key Insights
Certain customers contribute significantly to total revenue.
Product categories show different pricing patterns.
Some suppliers generate higher sales contribution.
Monthly trends help identify sales growth patterns.
Weekend and weekday purchasing behaviors differ.
Employee performance can be measured using sales handled.

📈 Business Value

This project helps in:

Understanding customer purchasing behavior
Tracking product performance
Monitoring employee efficiency
Evaluating supplier contribution
Identifying revenue trends
Supporting business decision-making
