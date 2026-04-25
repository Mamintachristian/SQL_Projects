# 📊 Employee Data Analysis (SQL Project)

This project is a SQL-based analysis of an employee dataset designed to practice relational database querying and develop data analysis skills using real-world HR-style questions.

The project focuses on extracting insights from employee data using SQL concepts such as filtering, aggregation, joins, subqueries, and window functions.

---

## 🎯 Project Objective

The main goal of this project is to analyze employee data and answer business questions such as:

- Who are the highest-paid employees in each department?
- What is the average salary per department?
- Which employees earn above their department average?
- How are employees distributed across departments?
- What are the hiring trends based on HireDate?

---

## 🗂️ Dataset Overview

The dataset contains a single relational table:

### Employee Table

| Column       | Description                    |
|--------------|--------------------------------|
| EmployeeID   | Unique identifier for employee |
| FirstName    | First name of employee         |
| LastName     | Last name of employee          |
| Department   | Department name               |
| Salary       | Employee salary               |
| HireDate     | Date the employee was hired   |

---

## ⚙️ Tools Used

- Python (Jupyter Notebook)
- SQLite (relational database engine)
- JupySQL (SQL magic in notebooks)
- Pandas (data inspection and analysis)

---

## 🧠 Key SQL Concepts Practiced

### 🟢 Basic Queries
- SELECT, WHERE, ORDER BY
- Filtering using IN, BETWEEN

### 🟡 Intermediate Queries
- GROUP BY and HAVING
- Aggregate functions (AVG, SUM, COUNT, MIN, MAX)
- Subqueries for filtering logic

### 🔴 Advanced Queries
- Window functions (RANK, AVG OVER PARTITION BY)
- Top-N per group analysis
- Department-level comparisons
- Multi-layer query structuring (subqueries)
