# Retail-Sales-Customer-Analysis
# Retail Sales & Customer Analysis

## Project Overview

This project analyzes retail sales and customer transaction data using MySQL.

The objective is to identify useful business insights such as:

- Total revenue
- Top-selling products
- High-value customers
- Revenue by product category
- Monthly sales trends
- Customer purchasing behavior
- City-wise sales performance

## Technologies Used

- MySQL
- SQL
- Relational Database
- Git & GitHub

## Database Structure

The project contains three main tables:

### Customers

Stores customer information.

Columns:

- customer_id
- customer_name
- gender
- age
- city
- registration_date

### Products

Stores product information.

Columns:

- product_id
- product_name
- category
- price

### Sales

Stores transaction information.

Columns:

- sale_id
- customer_id
- product_id
- quantity
- sale_date

## Table Relationships

Customers and Sales are connected using:

customer_id

Products and Sales are connected using:

product_id

## SQL Concepts Used

- SELECT
- WHERE
- GROUP BY
- HAVING
- ORDER BY
- INNER JOIN
- LEFT JOIN
- Aggregate Functions
- CASE Statements
- Subqueries
- LIMIT
- DATE_FORMAT
- MONTH

## Key Analysis

The project performs analysis on:

1. Total revenue
2. Total quantity sold
3. Top-selling products
4. Revenue by category
5. Customer spending
6. Top customers
7. Sales by city
8. Sales by gender
9. Monthly revenue
10. High-value transactions
11. Customer purchase frequency
12. Product performance

## How to Run

### Step 1

Install MySQL.

### Step 2

Open MySQL Workbench.

### Step 3

Run:

`01_create_database.sql`

### Step 4

Run:

`02_create_tables.sql`

### Step 5

Run:

`03_insert_data.sql`

### Step 6

Run:

`04_analysis_queries.sql`

## Project Objective

The project demonstrates how SQL can be used to transform transactional data into meaningful business insights for decision-making.

## Author

Aditya Parewa
