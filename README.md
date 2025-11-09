Coffee Shop Sales Dashboard

SQL | MySQL | Power BI | Data Modelling

Project Overview:
    This end-to-end analytics project analyzes coffee shop sales data using MySQL for backend processing and Power BI for interactive dashboard creation.The goal is to help store owners understand sales performance, product trends, customer demand, and store-level insights to support daily decision-making.

 Problem Statement:
   A retail coffee shop chain is experiencing inconsistent revenue across stores and 
 product categories.
Management does not have a consolidated view of:
Daily/Monthly sales trends
Best & worst performing products
Store-wise performance comparison
Peak business hours
Customer purchase patterns

The objective is to build a centralized dashboard that highlights key insights and helps improve operational and sales decisions.

 Tools & Technologies:

MySQL – Data storage & SQL querying
SQL – KPI calculations, joins, cleaning
Power BI – Dashboard design & visualization
Power Query – Data transformation
DAX – Measures, calculated fields

Steps Taken:

1. Data Understanding
Reviewed product, sales, customer, and store datasets
Identified duplicates, missing values, and inconsistent fields

2. Data Cleaning (SQL):
Removed duplicates
Standardized date and time formats
Corrected category labels
Joined tables into a fact-sales model

3.KPI Development (SQL):
Created KPIs like:
Total Sales
Total Transactions
Average Bill Amount
Sales by Category
Sales by Store
Peak Hour Analysis
Daily/Monthly trends

4.Data Modelling in Power BI:
Connected Power BI to MySQL
Built Date Dimension table
Created relationships for star schema
Developed DAX measures (Sales, Units Sold, Category Share)

5.Dashboard Building
Designed visuals:
KPI cards
Sales trend line chart
Category comparison bar chart
Store performance matrix
Peak hour heatmap
Slicers for Date, Category, Store

Key Insights:
Morning hours (8 AM – 11 AM) generate the highest sales.
Coffee beverages contribute the largest share of total revenue.
Certain stores show consistently higher performance, indicating strong customer base.
Sales drop during late evenings; promotional offers may help.
Weekends show 15–20% higher sales compared to weekdays.

Outcomes:
Identified peak sales hours and improved staffing and operational efficiency.
Highlighted best-selling products, helping optimize inventory and boost revenue.
Analyzed store-wise performance to support better resource and promotion planning.
Provided clear revenue trends for accurate forecasting and business decision-making.
