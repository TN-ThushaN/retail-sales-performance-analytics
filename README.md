# Retail Sales Performance Analytics

A real-world Business Intelligence portfolio project that analyzes retail sales, profitability, discounts, regions, customer segments, and channels.

## Business Problem
A retail company wants management to understand **where revenue comes from, which categories are most profitable, whether discounting hurts margin, and which regions/channels deserve more attention**.

## Key KPIs
- Total Sales
- Total Profit
- Profit Margin %
- Number of Orders
- Units Sold
- Average Order Value
- Sales Growth by Month/Year
- Profit by Region / Category / Channel

## Tools
- Power BI or Excel for dashboarding
- SQL for business queries
- Python (Pandas) for validation and analysis

## Dataset
`data/retail_sales.csv` contains 1,800 synthetic but realistic retail order records from 2024 to 2026.

## Suggested Dashboard Pages
1. **Executive Overview** — Sales, Profit, Margin, Orders, monthly trend
2. **Product & Category Analysis** — category/product contribution and profitability
3. **Regional Performance** — region comparison and growth
4. **Customer & Channel Analysis** — segments, channels, discount impact

## Sample Insights from the Dataset
- Highest-sales region: **Western**
- Most profitable category: **Electronics**
- Highest-sales channel: **Online**
- Average profit margin: **37.1%**

## Repository Structure
```text
retail-sales-performance-analytics/
├── data/retail_sales.csv
├── sql/analysis_queries.sql
├── python/retail_analysis.py
├── dashboard_plan.md
├── insights.md
└── README.md
```

## How to Use
1. Import `retail_sales.csv` into Power BI.
2. Convert `order_date` to Date type.
3. Create measures for Sales, Profit, Margin, Orders, Quantity, and AOV.
4. Build slicers for Year, Region, Category, Customer Segment, and Channel.
5. Use the SQL/Python files to validate dashboard results.

## Portfolio Value
This project demonstrates business KPI design, data cleaning, SQL analysis, dashboard planning, profitability analysis, and management-focused storytelling.
