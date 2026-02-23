# Sql-Data-Analysis-Portfolio
This Repository showcases my SQL skills developed through structured, day-wise practice using MYSQL and Mode Analytics.
It is designed to help recuriters and hiring managers quickly review my ability to write clean , readable and business-focused SQL queries.

---
## Skills Demonstrated
- SQL querying and data filtering
- Aggregations and GROUP BY Logic
- JOIN operations (INNER, LEFT)
- Subqueries and nested logic
- Analytical problem solving
- Window functions and advanced SQL Concepts
---
## Repository Structure
|      Folder                 |     Description                  |
|-----------------------------|----------------------------------|
|  `Basic_SQL/`               |SQL fundamentals, GROUP BY        |
| `Intermediate_SQL/`         |Having,Joins,CASE WHEN            |
|`Subqueries_Analytics_Logic/`|Subqueries and analytical queries |
| `Advanced_SQL/`             |Window functions and advanced SQL |
---
## Query Documentation Style
Each SQL file contains:
- A clear business question
- Clean and readable SQL
- Proper comments explaining intent
---
## Example SQL Query

The following example demonstrates my approach to solving
business-oriented data analysis problems using SQL.

```sql
-- Business Question:
-- Identify the top 5 countries by number of users

SELECT
  country,
  COUNT(*) AS user_count
FROM users
GROUP BY country
ORDER BY user_count DESC
LIMIT 5;
```
---

## Tools Used
- MySQL
- Mode Analytics SQL Tutorial
- GitHub
---
## Purpose
- Demonstrate SQL proficiency for Data Analyst roles
- Showcase analytical thinking using SQL
- Provide a clean, accessible SQL portfolio for recruiters
---
## Contact
Open to Data Analyst opportunities and professional discussions.
