# E-Commerce Customer Behavior — Exploratory Data Analysis

A complete exploratory data analysis of the Olist Brazilian e-commerce dataset (99,441 orders across 7 tables, Sep 2016 – Oct 2018), performed in Python with pandas, matplotlib/seaborn, and SQL (SQLite) inside a Jupyter notebook.

**Notebook:** `ecommerce_eda.ipynb` — load and run top to bottom (Runtime → Run all); it executes without errors.

## Key findings
- 97.02% of orders were delivered; cancellations are just 0.63%.
- São Paulo state accounts for 42.0% of all customers.
- Orders peaked in Nov 2017 (7,544 — Black Friday effect) after growing from hundreds per month.
- Delivery speed drives reviews: correlation −0.334 between delivery days and review score — 5★ orders averaged 10.2 days, 1★ orders 20.9 days.
- health_beauty is the top revenue category (~R$1.45M, 4.14★); bed_bath_table sells the most items but rates lowest of the top 10 (3.90★).

## Recommendation
Enforce a ~14-day delivery-time standard with proactive flagging/expediting ahead of the November peak, prioritizing shipments outside the SP–RJ–MG core.

Dataset: Olist Brazilian E-Commerce (orders, items, customers, products, reviews, payments, category translation).
