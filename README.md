# Amazon Sales Dashboard – Power BI

## Project Overview
This project presents an interactive Power BI dashboard that visualizes Amazon sales performance data.  
The dashboard provides clear insights into sales, profitability, pricing, and regional trends to support data-driven decision-making.

## Purpose
The main objectives of this project are to:
- Track total products sold, total revenue, and total profit.
- Analyze average unit price by product category.
- Monitor revenue trends over time.
- Compare profitability by sales channel.
- Examine regional cost distribution.

## Dataset Description
The dataset contains historical sales data for Amazon products.  

**Key fields include:**
- Item Type  
- Average Unit Price *(custom DAX measure created using `AVERAGE(Sales[Unit Price])`)*  
- Units Sold  
- Total Revenue  
- Total Profit  
- Total Cost  
- Order Date  
- Ship Date  
- Region  
- Sales Channel  

**Note:** This dataset is for educational and visualization purposes only.

## Dashboard Features

### Display Cards
- Total Products Sold: 513K  
- Total Revenue: 137.35M  
- Total Profit: 44.17M  

### Visuals
1. **Average Unit Price by Item Type** – Horizontal bar chart showing the average price for each product category.  
2. **Revenue Trend Over Time** – Line chart displaying revenue fluctuations between 2010 and 2017.  
3. **Total Cost by Region** – Area chart comparing regional cost distribution.  
4. **Total Profit by Sales Channel** – Pie chart comparing online vs offline profitability.  

## Filters and Interactivity
The dashboard includes slicers for:
- Order Date
- Sales Channel
- Region
- Item Type

These filters allow users to drill down into specific data segments.


## Key Insights
- Household and Office Supplies have the highest average unit prices.
- Offline sales produce slightly more profit than online sales.
- Sub-Saharan Africa incurs the highest total cost among all regions.
- Revenue trends indicate recurring seasonal demand peaks.

