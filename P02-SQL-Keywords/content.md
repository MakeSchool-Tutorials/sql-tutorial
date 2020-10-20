---
title: "SQL Keywords"
slug: sql-keywords
---

## SQL Keywords

SQL keywords are used to specify actions in your queries. They are not case sensitive, but we suggest using all caps for SQL keywords so that you can easily set them apart from the rest of the query. Some frequently used keywords are:

1. SELECT
1. FROM
1. WHERE

## SELECT

SELECT​ allows us to grab data for specific columns from the database:

`*`​ (asterisk): it is used after *SELECT* to grab all columns from the table.

Example:
> [info]
>
> The code below grabs all the rows from the Customers table.
>

> [action]
>
> Run this command in the sql-fiddle.
>
```sql
SELECT * FROM Customers
```
>


> [info]
> Use Column_name(s): to select specific columns, put the names of the columns after SELECT​ and use commas to separate them.
>


Example:

> [action]
> ```sql
> SELECT FName FROM Customers
> ```
>

## FROM

FROM​ allows us to specify which table(s) we care about; to select multiple tables, list the table names and use commas to separate them. (But until you learn the JOIN keyword, you may be surprised at what happens. That will come later.)

To limit the number of rows you get from the result, you can add the keyword **LIMIT**
Run this, and see what happens.

```sql
SELECT * FROM Customers LIMIT 2;
```

You should only see 2 rows from the Customers table.

## WHERE

The **​WHERE**​ clause in a query is used to filter results by specific criteria.

> [action]
>
> Run this command in the sql-fiddle.
>
```sql
SELECT * FROM Customers WHERE FName = 'David'
```
>

This command selects all customers whose first name is David.

Let's try some of these things.

# Activity
> [challenge]
Here are some challenges you can try on your own on the SQL fiddle
> - Select all employees
> - Select all departments
> - Select all cars
> - Select salary of all employees
> - Select the model of all cars
> - Select Customers whose preferred contact is email
>


## Resources
https://www.edureka.co/blog/top-10-reasons-to-learn-sql/

https://mystery.knightlab.com/walkthrough.html
