PostgreSQL Mini Project – Customer & Order Management System
=============================================================

Overview:
---------
This project demonstrates a simple customer-order-product relational database design using PostgreSQL. 
It includes:

- 5 related tables
- Sample data insertions
- 20+ practical SQL queries
- A business-oriented scenario to simulate real-world use

It’s perfect for beginners who want hands-on SQL practice.

Files:
------
- schema.sql         → Table creation scripts
- insert_data.sql    → Sample data for each table
- queries.sql        → Business logic queries (with comments)
- erd-diagram.png    → Entity-Relationship Diagram (visual overview)
- README.txt         → You are here :)

How to Use:
-----------
1. Make sure PostgreSQL is installed on your machine.
2. Open SQL Shell (psql) or your preferred SQL client.
3. Create a new database (optional):
   CREATE DATABASE mydb;
   \c mydb

4. Run each SQL file in this order:
   \i 'schema.sql'
   \i 'insert_data.sql'
   \i 'queries.sql'

OR use command line (outside psql shell):
   psql -U postgres -d mydb -f schema.sql
   psql -U postgres -d mydb -f insert_data.sql
   psql -U postgres -d mydb -f queries.sql

Project Scenario:
-----------------
Imagine you're running a small e-commerce business. This database helps you answer questions like:

1. Which customers are generating the most revenue?
2. What are the most and least popular products?
3. Which products are in low stock?
4. What’s the total order value per customer?
5. How can you filter products by price or category?

These kinds of queries are essential for data-driven decision-making.

Bonus:
------
- ER diagram included to visualize relationships
- Clean SQL scripts with comments
- Optimized queries using joins, subqueries, GROUP BY, and more

Author:
-------
Created by [İbrahim Ethem AFŞAR]
Medium: https://medium.com/@etem4224
GitHub: https://github.com/ghostron09

License:
--------
This project is open-source and free to use for educational purposes.
