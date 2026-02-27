# 🍕 Pizza Sales Analysis using PostgreSQL

## 📌 Project Overview
This project analyzes pizza sales data using PostgreSQL to uncover key business insights related to revenue, product performance, customer ordering patterns, and time-based trends.

The dataset consists of four Excel files:
- orders
- order_details
- pizzas
- pizza_types

These were imported into PostgreSQL and connected using primary and foreign keys to perform relational analysis.

---

## 🧱 Database Design
Created normalized tables with proper keys:

- orders → order date & time  
- order_details → order-level quantity  
- pizzas → size & price  
- pizza_types → category & ingredients  

---

## 🎯 Business Questions Solved

- Total number of orders  
- Total revenue generated  
- Highest-priced pizza  
- Most common pizza size  
- Top 5 most ordered pizzas  
- Category-wise quantity sold  
- Hourly order distribution  
- Average pizzas ordered per day  
- Top 3 pizzas by revenue  
- Revenue % contribution by category  
- Cumulative revenue over time  
- Top 3 pizzas per category using window functions  

---

## 🧠 SQL Concepts Used

- Multi-table INNER JOIN  
- GROUP BY & ORDER BY aggregations  
- Subqueries  
- Window functions  
  - RANK()  
  - SUM() OVER()  
- DATE_PART() for time analysis  
- Revenue calculations using price × quantity  

---

## 📊 Key Analytical Highlights

- Identified revenue-driving pizzas  
- Found peak ordering hours for operational planning  
- Measured category-wise revenue contribution  
- Analyzed sales trends using cumulative revenue  
- Ranked top pizzas within each category  

---

## 📁 Project Structure

```
pizza-sales-sql-analysis/
│── pizza_sales_project.sql
│── README.md
│── dataset/
│   ├── orders.xlsx
│   ├── order_details.xlsx
│   ├── pizzas.xlsx
│   └── pizza_types.xlsx
```

---

## 🚀 How to Run

1. Create tables using the DDL queries  
2. Import Excel data into PostgreSQL  
3. Execute the analysis queries  
4. Review insights  
