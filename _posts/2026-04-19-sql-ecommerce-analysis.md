---
title: "SQL E-commerce Sales Analysis"
subtitle: "Customer, product, and revenue insights using SQL"
tags: [sql, e-commerce, analytics, portfolio]
---

## Project Goal

Analyze e-commerce transaction data with SQL to identify trends in revenue, customer behavior, and product performance.

## Tools

- SQL (CTEs, joins, window functions, aggregations)
- Relational database (PostgreSQL-style syntax)

## Business Questions

1. Which product categories generate the highest revenue?
2. What is the monthly sales trend over time?
3. Who are the top customers by total spend?
4. What is the average order value by month?

## Example SQL Query

```sql
SELECT
  DATE_TRUNC('month', order_date) AS order_month,
  ROUND(SUM(total_amount), 2) AS monthly_revenue,
  ROUND(AVG(total_amount), 2) AS avg_order_value,
  COUNT(DISTINCT order_id) AS total_orders
FROM orders
GROUP BY 1
ORDER BY 1;
```

## Key Insights

- Revenue showed steady month-over-month growth with seasonal spikes.
- A small segment of repeat customers contributed a large share of total sales.
- Two product categories consistently outperformed others in both volume and margin.

## Next Steps

- Add cohort retention analysis.
- Build a Power BI dashboard on top of the SQL output.
- Extend analysis with customer segmentation in Python.
