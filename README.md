# Power BI Retail Sales & Inventory Dashboard

## Project Overview
A fully interactive Business Intelligence dashboard built using 
Microsoft Power BI Desktop, integrating 4 different data sources 
for comprehensive retail analytics.

## Data Sources
- Excel Workbook — Product catalogue & inventory (35 products)
- CSV File — Sales transactions fact table (5,200 rows)
- CSV File — Customer demographics & loyalty (300 customers)
- Python Script Output — Monthly sales forecast (48 months)

## Features
- Star Schema data model (FactSales + 4 dimension tables)
- 10 DAX measures including YoY Growth % and Profit Margin %
- KPI Cards, Line Chart, Donut Chart, Bar Chart, Map, Table
- Interactive slicers for Year, Region, and Category
- Sales Forecasting with confidence bounds
- AI Smart Narrative visual (bonus feature)
- Conditional formatting on low-stock inventory alerts

## Tools Used
- Microsoft Power BI Desktop
- Power Query (ETL & data cleaning)
- DAX (Data Analysis Expressions)
- Python (forecast data generation)

## Key Business Insights
- South region generates highest revenue (28% of total)
- Electronics category has highest stockout risk
- Corporate segment = 45% revenue from only 22% of customers
- Q4 consistently outperforms other quarters by 35-40%
