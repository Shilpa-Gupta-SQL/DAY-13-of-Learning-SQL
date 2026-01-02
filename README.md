📘 SQL Window Functions & CTEs – Lecture 13
This repository documents my learning from Lecture 13, focused on SQL Window Functions and Common Table Expressions (CTEs). These concepts are essential for writing advanced, readable, and efficient SQL queries used in real-world analytics and reporting.

🔹 Window Functions
Window functions perform calculations across a set of rows related to the current row without collapsing results, unlike aggregate functions.

*OVER()
Defines the window (group of rows) for calculation using PARTITION BY and ORDER BY.

*ROW_NUMBER()
Assigns a unique sequential number to each row within a partition.

*RANK() 
Ranks rows within a partition, leaving gaps when values are tied.

*DENSE_RANK()
Ranks rows without gaps for ties.

*NTILE(n)
Divides rows into n equal groups (useful for bucketing and percentiles).

*LAG() & LEAD()
Access previous or next row values without using self-joins.

*RUNNING TOTAL
Calculates cumulative totals using SUM() OVER (ORDER BY ...).

*COALESCE()
Handles NULL values by returning the first non-NULL value.

🔹 Common Table Expressions (CTEs)
CTEs improve query readability and structure by defining temporary result sets.

*Simple CTE (WITH)
Used to break complex queries into logical steps.

*Using CTE Multiple Times
A single CTE can be referenced multiple times within a query.

*Window Functions + CTE Combination
CTEs are often combined with window functions to simplify complex analytics queries.

*Recursive CTE
Used for hierarchical or iterative data (e.g., org charts, parent-child relationships).
