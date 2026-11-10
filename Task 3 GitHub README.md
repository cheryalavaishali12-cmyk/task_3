# Elevate Labs - Data Analyst Internship
## Task 3: SQL for Data Analysis

---

## 📌 Project Overview
This repository contains the submission for **Task 3: SQL for Data Analysis** as part of the Elevate Labs Data Analyst Internship. 

The objective of this task is to extract, filter, group, aggregate, and analyze structured data from a relational database using fundamental and advanced SQL concepts.

---

## 🛠️ Tools & Technologies Used
* **Database Management System:** SQLite (`sqliteonline.com`)
* **Version Control:** GitHub
* **File Deliverables:** 
  * `sql_queries.sql` (Complete SQL Code Script)
  * Execution Screenshots (`.png` / `.jpg`)
  * `README.md` (Project Documentation)

---

## 📊 Database Schema Summary
The project utilizes a two-table relational database model:

1. **`Department` Table**
   * `Dept_ID` (INTEGER PRIMARY KEY)
   * `Dept_Name` (VARCHAR)
   * `Location` (VARCHAR)

2. **`Employee` Table**
   * `Emp_ID` (INTEGER PRIMARY KEY)
   * `Emp_Name` (VARCHAR)
   * `Age` (INTEGER)
   * `Salary` (DECIMAL)
   * `Dept_ID` (INTEGER - Foreign Key linked to `Department.Dept_ID`)

---

## 📂 Key Topics Covered
- **Data Selection & Filtering:** Using `SELECT`, `WHERE`, and `ORDER BY` clauses.
- **Data Aggregation & Grouping:** Utilizing `GROUP BY`, `HAVING`, `AVG()`, `COUNT()`, `MAX()`, and `MIN()` functions.
- **Relational Joins:** Implementing `INNER JOIN`, `LEFT JOIN`, and `RIGHT JOIN`.
- **Subqueries:** Writing nested queries to retrieve data conditionally across tables.
- **Views & Optimization:** Creating reusable virtual views (`CREATE VIEW`) and applying database indexing (`CREATE INDEX`).

---

## 🎯 Key Takeaways & Conclusion

Through completing this task, practical experience was gained in writing clean, efficient, and structured SQL queries to extract data-driven insights from relational databases:

1. **Relational Data Modeling:** Understood how primary and foreign keys establish relationships between normalized tables (`Employee` and `Department`).
2. **Data Manipulation & Filtering:** Mastered conditional queries using `WHERE`, `ORDER BY`, and subqueries for multi-step data retrieval.
3. **Summarization & Aggregation:** Effectively analyzed key metrics using `GROUP BY`, `HAVING`, and built-in aggregate functions (`AVG`, `SUM`, `MIN`, `MAX`).
4. **Combining Datasets:** Applied various `JOIN` operations (`INNER`, `LEFT`, `RIGHT`) to combine disparate data entities seamlessly.
5. **Database Abstraction & Optimization:** Built custom views (`CREATE VIEW`) for simplified reporting and learned indexing concepts (`CREATE INDEX`) to improve query performance.

Overall, this project provided strong foundational and analytical skills required for real-world SQL data analysis tasks.