# 📊 Retail Sales Analysis Using MySQL

## 📌 Project Overview

This project focuses on analyzing retail sales transaction data using MySQL. The objective is to explore sales records, clean and format textual data, extract meaningful date information, and analyze monthly revenue.

The project demonstrates practical SQL skills through real-world retail business questions.

## 🎯 Project Objectives

- Import CSV datasets into MySQL.
- Create and manage databases and tables.
- Explore and inspect sales transaction records.
- Apply SQL string functions to clean and format data.
- Use date functions to extract useful date information.
- Analyze monthly revenue and sales trends.
- Answer business questions using SQL queries.

## 📂 Dataset Description

The dataset contains 100 retail sales transaction records.

| Column | Description |
|---|---|
| date | Transaction date |
| region | Sales region |
| product | Product name |
| channel | Sales channel |
| units | Number of units sold |
| unit_price | Price per unit |
| revenue | Total revenue |

## 🛠️ Tools & Technologies

- MySQL
- MySQL Workbench
- SQL
- CSV Dataset
- Git & GitHub

## 🗄️ Database Structure

Database Name: `RetailDB`

Table Name: `retail_sales`

```sql
CREATE TABLE retail_sales (
    date DATE,
    region VARCHAR(50),
    product VARCHAR(100),
    channel VARCHAR(30),
    units INT,
    unit_price DECIMAL(10,2),
    revenue DECIMAL(12,2)
);
```

## 📚 SQL Concepts Covered

### 1. Database Management
- CREATE DATABASE
- USE
- CREATE TABLE
- DROP TABLE
- DESCRIBE

### 2. Data Exploration
- SELECT
- COUNT()
- LIMIT
- SUM()
- AVG()

### 3. String Functions
- UPPER()
- LOWER()
- LENGTH()
- LEFT()
- CONCAT()
- TRIM()

### 4. Date Functions
- YEAR()
- MONTH()
- MONTHNAME()
- DAY()
- DAYNAME()
- DATE_FORMAT()
- DATEDIFF()

### 5. Data Analysis
- GROUP BY
- ORDER BY
- BETWEEN
- Aggregate Functions

## 📈 Business Questions Solved

1. How can product names be displayed in uppercase and lowercase?
2. What is the character length of each product name?
3. How can we extract the first five characters of product names?
4. How can region and sales channel be combined into one label?
5. How can leading and trailing spaces be removed?
6. How can transaction dates be broken down into year, month and weekday?
7. What is the total revenue generated each month?
8. How can sales transactions be filtered by date range?

## 📊 Key Learnings

Through this project, I gained practical experience in:

- Database creation and management.
- Importing CSV datasets into MySQL.
- Data exploration and cleaning.
- Applying SQL string and date functions.
- Grouping and aggregating sales data.
- Answering business-oriented questions using SQL.

## 📁 Project Structure

```text
Retail-Sales-SQL-Analysis/
│
├── retail_sales.sql
├── README.md
├── dataset/
│   └── sales_transactions.csv
│
└── screenshots/
    ├── database.png
    ├── imported_data.png
    └── query_outputs.png
```

## 🚀 How to Run This Project

1. Download or clone this repository.
2. Open MySQL Workbench.
3. Create the RetailDB database.
4. Create the retail_sales table.
5. Import the CSV dataset using Table Data Import Wizard.
6. Open the SQL file.
7. Execute the queries to explore and analyze the data.

## 👨‍💻 Author

**Steward Jacob**

BCA Graduate | Data Science & AI

Interested in Data Analytics, Data Engineering and Machine Learning.
