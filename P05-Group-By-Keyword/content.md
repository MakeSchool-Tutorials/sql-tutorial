---
title: "Group By Keyword"
slug: group-by-keyword
---

## Grouping data within a table

So let's say we want to know how many employees have similar last names. This is where the `Group By` keyword comes in.

It allows us to split up the dataset and apply aggregate functions within each group, resulting in one row per group.

> [action]
>
> Run this command in the sql-fiddle.
> This command selects last names of employees and counts them. Then groups them by their last name. If you run the command, you'll see distinct last names in one column and their count on another column.
>
```sql
SELECT LName, count(*) FROM Employees Group By LName
```
>

![group by lname](assets/group_by_lname.png "group by lname")


# Activity

> [challenge]
>
> Here are some challenges you can try on your own on the SQL fiddle
>
> - Select the preferred contact of customers and group it by preferred contact
> - Select Models of Cars with their count and group them by the Model.
> - Select Models of Cars with their count and group them by their Status.

# Feedback and Review - 2 minutes

**We promise this won't take longer than 2 minutes!**

Please take a moment to rate your understanding of the learning outcomes from this tutorial, and how we can improve it via our [tutorial feedback form](https://forms.gle/XZFTwPHGxHk2U6s27)

This allows us to get feedback on how well the students are grasping the learning outcomes, and tells us where we can improve the tutorial experience.

# Resources
[Info on Longtails in SQL](https://selectstarsql.com/longtail.html)

# Congrats!

You have successfully learned some new MySQL commands and queried databases using these MySQL commands! You're now ready to take on more challenging SQL questions. Should you ever need a refresher, come back and practice with this tutorial!
