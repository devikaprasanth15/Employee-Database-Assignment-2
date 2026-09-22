# MySQL Assignment 2 – Querying Data

## Introduction
This repository contains solutions for MySQL Assignment 2, focusing on querying and manipulating data within an employee database. Building upon table structures from previous assignments, these queries demonstrate essential SQL skills including data filtering, aggregate functions, grouping, sorting, and multi-table join operations.

---

## 📑 Assignment Topics & Exercises

### 1. Basic Querying & Column Aliasing
* **Distinct Values:** Query to retrieve distinct salaries from the `Employees` table.
* **Aliases (`AS`):** Query providing aliases for `age` as `Employee_Age` and `salary` as `Employee_Salary`.

### 2. Filtering & Data Manipulation
* **`WHERE` Clause & Operators:** Query retrieving employees earning over ₹50,000 hired before `2016-01-01`.
* **Updating Null Values:** Query identifying employees with missing designations and updating them to `"Data Scientist"`.

### 3. Sorting & Pagination
* **`ORDER BY`:** Sorting employees by department ID in ascending order and salary in descending order.
* **`LIMIT`:** Displaying the first 5 employees hired in the year 2018.

### 4. Aggregations & Grouping
* **Aggregate Functions:**
  * Sum of all salaries in the Finance department (`SUM`).
  * Minimum age among all employees (`MIN`).
* **`GROUP BY`:**
  * Maximum salary per location.
  * Average salary for designations containing the term `'Analyst'`.
* **`HAVING` Clause:**
  * Departments with fewer than 3 employees.
  * Locations with female employees where the average age is below 30.

### 5. Relational Joins
* **Inner Join:** Listing employee names, designations, and department names for assigned employees.
* **Left Join:** Displaying all departments along with employee counts, including departments without employees.
* **Right Join:** Displaying all locations with assigned employee names, returning `NULL` for locations with no assigned employees.
