# Week 4 Database Assignment

## Advanced SQL Queries and Aggregations

This repository contains solutions for the Week 4 Database Assignment using MySQL and the ClassicModels database schema.

### Topics covered
- Aggregate functions: `SUM()`, `AVG()`, and `MAX()`
- `GROUP BY`
- `ORDER BY`
- `LIMIT`
- Calculated totals using multiplication and aggregation

## Assignment Questions

### Question 1
Shows the total payment amount for each payment date, ordered from the latest date to the oldest, limited to the latest 5 payment dates.

### Question 2
Shows the average credit limit for each customer, including the customer name and country.

### Question 3
Shows the total price for products ordered, calculated as `quantityOrdered * priceEach`, grouped by product code and quantity ordered.

### Question 4
Shows the highest payment amount for each check number.

## Files

- [week4_assignment.sql](week4_assignment.sql) — SQL solutions for all four questions.

## Notes

The queries assume the standard MySQL **ClassicModels** database table and column names.
