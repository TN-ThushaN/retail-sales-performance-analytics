# Power BI Dashboard Plan

## Page 1 — Executive Overview
Cards: Total Sales, Total Profit, Profit Margin %, Orders, Units Sold, AOV.
Visuals: Monthly Sales Trend, Sales by Region, Profit by Category, Sales by Channel.

## Page 2 — Product Performance
Visuals: Sales vs Profit by Product, Category Share, Top 10 Products, Discount vs Profit Margin.

## Page 3 — Regional Analysis
Visuals: Region ranking, monthly regional trend, category mix by region, regional margin table.

## Recommended Slicers
Year, Region, Category, Customer Segment, Sales Channel.

## Suggested DAX Measures
```DAX
Total Sales = SUM(retail_sales[sales_lkr])
Total Profit = SUM(retail_sales[profit_lkr])
Profit Margin % = DIVIDE([Total Profit], [Total Sales])
Total Orders = DISTINCTCOUNT(retail_sales[order_id])
Units Sold = SUM(retail_sales[quantity])
Average Order Value = DIVIDE([Total Sales], [Total Orders])
```
