# Task 5 - Advanced Data Analytics & Business Intelligence Project

## 📌 Project Overview

This project represents the final stage of my Data Analytics & Business Intelligence internship.
In this task, I enhanced my previous dashboard by implementing advanced DAX calculations, customer segmentation, time intelligence, and dashboard optimization to create a portfolio-ready Business Intelligence solution.

---

## 🛠 Tools Used

* Microsoft Excel (Data Source)
* MySQL (Database & Queries)
* Power BI (Data Modeling & Dashboard)

---

## 📂 Dataset Structure

The project follows a **Star Schema Model**:

### Fact Table

* Orders

### Dimension Tables

* Customers
* Products

---

## 🔗 Data Modeling

Established relationships:

* Customers → Orders (1 : Many)
* Products → Orders (1 : Many)

This structure improves performance and enables efficient analysis.

---

## 📊 Advanced DAX Measures

Implemented advanced DAX functions:

* **Total Sales** = SUM(Orders[Sales])
* **Total Profit** = SUM(Orders[Profit])
* **Profit Margin %** = DIVIDE([Total Profit], [Total Sales])
* **Sales Rank** using `RANKX()`
* **High Sales Filter** using `CALCULATE()` and `FILTER()`

---

## ⏱ Time Intelligence

* Extracted Year and Month from Order Date
* Built sales trend analysis using time-based visuals
* Enabled better understanding of business growth patterns

---

## 👥 Customer Segmentation

Customers classified into:

* High Value
* Medium Value
* Low Value

Using DAX logic to support business decision-making and targeted strategies.

---

## 📈 Dashboard Features

* KPI Cards (Sales, Profit, Quantity, Margin %)
* Sales by Region
* Sales by Category
* Profit Analysis
* Customer Segmentation
* Sales Trend (Time Intelligence)
* Interactive Slicers (Region & Category)

---

## ⚡ Dashboard Optimization

* Improved layout and alignment
* Added meaningful titles
* Used interactive filters for better usability
* Enhanced readability and performance

---

## 🗄 SQL Concepts Used

* CREATE DATABASE
* CREATE TABLE
* INSERT INTO
* JOIN Operations
* GROUP BY & Aggregations

---

## 💡 Key Business Insights

* High-value customers contribute significantly to revenue
* Technology category generates the highest sales and profit
* Sales trends show consistent growth over time
* Regional performance varies, highlighting focus areas
* Segmentation helps in better customer targeting

---

## 📁 Files Included

* Task4_Data_Model.xlsx
* Task4_SQL_Queries.sql
* Task5_Advanced_BI_Project.pbix
* Task5_Business_Insights.docx

---

## 🚀 Outcome

This project demonstrates:

* Advanced DAX capabilities
* Data modeling and relationships
* Business intelligence dashboard creation
* Data storytelling and insights generation

It serves as a **portfolio-ready BI project** aligned with entry-level Data Analyst / BI Developer roles.
