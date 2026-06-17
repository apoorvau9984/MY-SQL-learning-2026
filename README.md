# 1 SQL SELECT Statement Practice

## Overview

This repository contains my practice work for learning the SQL `SELECT` statement in MySQL.

## Queries Covered

### View Employee Demographics

```sql
SELECT *
FROM employee_demographics;
```

### View Employee Salaries

```sql
SELECT *
FROM employee_salary;
```

### View Park Departments

```sql
SELECT *
FROM parks_departments;
```
# 2 SQL WHERE Clause Practice

## Overview

This repository contains my practice queries for learning the SQL `WHERE` clause in MySQL. The `WHERE` clause is used to filter records based on specific conditions.

## Topics Covered

### Greater Than Operator (`>`)

```sql
SELECT employee_id AS unique_id, first_name AS name_, salary AS vetan_
FROM employee_salary
WHERE salary > 70000;
```

### Equal To Operator (`=`)

```sql
SELECT *
FROM employee_demographics
WHERE gender = "male";
```

### Not Equal To Operator (`!=`)

```sql
SELECT *
FROM employee_demographics
WHERE gender != "male";
```

### Less Than Operator (`<`)

```sql
SELECT *
FROM employee_demographics
WHERE age < 30;
```
# 3 SQL Intermediate Queries

## Overview

This repository contains my practice work on intermediate SQL concepts in MySQL, including grouping, sorting, filtering aggregated data, limiting results, aliasing, and joins.

## Topics Covered

### GROUP BY

* Group records based on a column.
* Calculate aggregate values for each group.

### Aggregate Functions (MIN & MAX)

* Find minimum and maximum values within groups.

### ORDER BY

* Sort records in ascending and descending order.

### HAVING vs WHERE

* `WHERE` filters rows before grouping.
* `HAVING` filters groups after aggregation.

### LIMIT

* Restrict the number of rows returned.
* Retrieve specific records using offset.

### ALIASING

* Assign temporary names to columns for better readability.

### JOINS

* Combine data from multiple tables using common columns.

### SELF JOIN

* Join a table with itself to compare related rows.

## Concepts Practiced

* GROUP BY
* AVG()
* MIN()
* MAX()
* ORDER BY
* HAVING
* LIMIT
* Aliases
* RIGHT JOIN
* SELF JOIN

#  4 SQL Union and String Functions

## Overview

This repository contains my practice work on SQL `UNION` operations and commonly used String Functions in MySQL.

## Topics Covered

### UNION

* Combine results from multiple SELECT statements.
* Remove duplicate records automatically.
* Sort combined results using ORDER BY.

### String Functions

#### LENGTH()

* Find the number of characters in a string.

#### UPPER() and LOWER()

* Convert text to uppercase and lowercase.

#### TRIM Functions

* `LTRIM()` removes leading spaces.
* `RTRIM()` removes trailing spaces.

#### SUBSTRING Functions

* `LEFT()` extracts characters from the beginning.
* `RIGHT()` extracts characters from the end.
* `SUBSTRING()` extracts a specific part of a string.

#### REPLACE()

* Replace existing values with new values.

#### LOCATE()

* Find the position of a substring within a string.

#### CONCAT()

* Combine multiple values into a single string.

## Concepts Practiced

* UNION
* ORDER BY
* LENGTH()
* UPPER()
* LOWER()
* LTRIM()
* RTRIM()
* LEFT()
* RIGHT()
* SUBSTRING()
* REPLACE()
* LOCATE()
* CONCAT()

## Learning Objectives




