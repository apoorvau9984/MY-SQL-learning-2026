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


