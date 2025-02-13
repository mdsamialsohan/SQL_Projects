# SQL Analysis with SQL Magic & XAMPP in Jupyter Notebook

## 📌 Project Overview

This project explores Sakila Database using SQL Magic (%%sql) in Jupyter Notebook while connecting to a MySQL database hosted on XAMPP. It includes various Data Manipulation (DML) and Aggregation queries, providing insights into customer rentals, payments, and movie statistics.

## 🚀 Features & Operations
- **Database Connection:** Using SQL Magic (%%sql) to connect MySQL with Jupyter Notebook.
- **Data Retrieval:** SELECT queries with filtering, sorting, and joins.
- **Data Manipulation:** INSERT, UPDATE, DELETE operations.
- **Aggregation & Analysis:** SUM, COUNT, AVG, GROUP BY, HAVING.
- **Subqueries & Transactions:** Ensuring ACID compliance in MySQL.

## 🔗 Setup & Installation
### 1. Install Required Libraries
 Before running the notebook, install ipython-sql for SQL Magic in Jupyter:
   ```
   pip install ipython-sql
   ```
### 2. Start MySQL in XAMPP
* Open XAMPP Control Panel
* Start Apache & MySQL
### 3. Connect MySQL to Jupyter Notebook
In your Jupyter Notebook, run:
```
%load_ext sql
%sql mysql+pymysql://root:@localhost/sakila
```
🔹 Note: Adjust credentials (root, localhost, sakila) if needed.

## 📌 Author
MD SAMIAL HASAN SOHAN

www.samialsohan.com

[linkedin](https://www.linkedin.com/in/mdsamialsohan/)
