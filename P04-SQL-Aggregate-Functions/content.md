---
title: "SQL Aggregate Functions"
slug: sql-aggregate-functions
---

## SQL Aggregate Functions

An aggregate function performs a calculation one or more values and returns a single value. The aggregate function is often used with the GROUP BY clause and HAVING clause of the SELECT statement.

Here are a few useful aggregate functions SQL provides:

### MAX
finds the maximum value

### MIN
finds the minimum value

### SUM
calculates the sum of the specified column values

### AVG
calculates the average of the specified column values

### COUNT​
counts the number of specified column values


> [action]
>
> Run this command in the sql-fiddle. 
> This command selects the employee with the maximum salary.
>
```sql
SELECT max(salary) FROM Employees
```
>


# Activity
> [challenge]
Here are some challenges you can try on your own on the SQL fiddle
> - Select an employee with the most recent hire data


## Resources

https://mystery.knightlab.com/walkthrough.html

https://www.sqlservertutorial.net/sql-server-aggregate-functions/
