# Analytic-report-for-superstore-using-powerbi-and-tableau

### Table of Contents
- [Project Overview](#project-overview)
- [Obejectives](#objectives)
- [Process](#process)
- [Dataset Description](#dataset-description)
- [Dashboard Features](#dashboard-features)
- [Key Insights](#key-insights)
- [Tools](#tools)
- [Challenges and Solutions](#challenges-and-solutions)
- [Future Enhancements](#future-enhancements)

### Project Overview
This project focuses on analyzing retail performance using the Superstore dataset.
Dashboards were created in Power BI and Tableau to understand sales trends, customer behavior, product performance, and regional contribution.

The dashboards help decision-makers identify:

 - High-revenue categories
 - Profitability trends
 - Regional performance
 - Customer segment contribution
 - Monthly sales movement
 - Top & bottom performing products

### Objectives
 - Provide a complete view of Superstore’s sales performance
 - Identify trends in sales, profit, and discount patterns
 - Analyze performance across categories, subcategories, segments, and regions
 - Understand monthly and yearly sales patterns
 - Identify high-performing vs. low-performing products
 - Enable interactive decision-making with slicers and filters

### Dataset Description

Dataset includes:
 - Order Date
 - Customer Segment
 - Category & Subcategory
 - Sales
 - Profit
 - Quantity Sold
 - Discount
 - Country/State
 - Product Name

This dataset represents transactional retail sales


### Process

1. Data Cleaning (Power Query)

   - Removed duplicate rows
   - Fixed incorrect date formats
   - Standardized product names and categories
   - Calculated additional fields (Profit %, Return Rate, etc.)
   - Handled missing or null values

2. Data Modeling

   - Designed necessary relationships between tables
   - Ensured proper data model for accurate aggregation

3. Dashboard Development

   - Designed KPI cards for high-level metrics
   - Built charts for visual storytelling
   - Applied filters for interactive experience
 
### Dashboard Features
Dashboard 1: Overall Sales Analysis using Tableau

Includes:

 - KPI Cards: Total Sales, Total Profit, Total Quantity
 - Sales by Category: Technology, Furniture, Office Supplies
 - Sales by Subcategory
 - Sales by State (Map)
 - Profit by Subcategory
 - Sales Trend Over Time
 - Sales by Customer Segment
 - Top 5 Selling Products

Dashboard 2: Overall Sales Analysis using PowerBI

Includes:

 - KPI Cards: Total Sales, Profit %, Quantity
 - Monthly Sales Trend (Line Chart)
 - Product-wise Manufacturing Price vs Sales
 - Units Sold by Product (Donut Chart)
 - Top & Bottom Products Based on Sales/Profit
 - Sales by Country (Map Visualization)

### Key Insights

- Technology category contributes the highest revenue among all categories.
- Year-end months show higher sales peaks, indicating seasonal demand.
- States like California and New York generate the highest sales.
- Office Supplies have higher quantity sold but lower profitability.
- Certain products (like “Paseo” and “Montana”) show strong sales volume.
- Some segments show profit loss due to high discounts.
- Customer Consumer segment contributes most to sales.

### Tools 

- Power BI – Data cleaning, modeling, DAX, dashboard design

- Tableau - Dashboard and Visualization

### Challenges and Solutions
1. Inconsistent Product and Category Labels

   Solution: Standardized using Power Query text transformations.

2. Profit Deviation in Subcategories

   Solution: Created custom DAX measures for accurate calculations.

3. Too Many Categories Leading to Overlapping Charts

   Solution: Used tooltip-based drilldowns and sorted charts clearly.

4. Visual Overload

   Solution: Clean layout with slicers + removing unnecessary visuals.

### Future Enhancements

- Add forecasting for predicting future sales
- Build a separate dashboard for Customer Lifetime Value (CLV)
- Add region-based drill-through pages
- Add a returns analysis page


