# 🍽️ Swiggy-Orders-SQL-Analytics

## 📌 Overview

This project demonstrates an end-to-end SQL workflow on Swiggy food order data, including:

* Data validation & cleaning
* Duplicate removal
* Star schema data warehouse design
* Fact and dimension table creation
* ETL data loading
* KPI generation
* Business intelligence queries

The goal is to transform raw transactional data into a structured analytical model and extract actionable insights.

---

## 🛠️ Tools & Technologies

* SQL Server
* Data Warehousing (Star Schema)
* ETL using SQL
* Window Functions
* Aggregations & Joins

---

## 📂 Dataset Fields

* State
* City
* Order_Date
* Restaurant_Name
* Location
* Category
* Dish_Name
* Price_INR
* Rating
* Rating_Count

---

## ⚙️ Project Workflow

### ✅ Data Cleaning & Validation

* Null detection
* Blank string identification
* Duplicate detection & removal using ROW_NUMBER()

### ✅ Data Warehouse Modeling

Created dimension tables:

* dim_date
* dim_location
* dim_restaurant
* dim_category
* dim_dish

Created fact table:

* fact_swiggy_orders

### ✅ ETL Implementation

* Loaded dimension tables using DISTINCT
* Populated fact table using joins between raw data and dimensions

---

## 📊 KPIs Generated

* Total Orders
* Total Revenue
* Average Rating

---

## 📈 Business Insights

* Monthly, Quarterly & Yearly order trends
* Orders by weekday
* Top cities by revenue
* Revenue contribution by state
* Top restaurants by sales
* Most ordered dishes
* Category performance
* Price range distribution
* Rating distribution

---

## 🚀 Learning Outcomes

* Data cleaning techniques
* Star schema modeling
* ETL pipeline using SQL
* Advanced joins & aggregations
* Business insight generation

---
