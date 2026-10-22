Simple Sales Dashboard Design

Veda Technology · Data Analytics Track · Task 3 (Level 1, Day 3)

Objective

Turn cleaned data and KPIs into an interactive view that a stakeholder can actually use. The dashboard shows sales performance by product category, region and month.

Tools

Excel and Power BI

Dataset

Sample sales dataset with a Superstore-style structure: 432 order lines for 2025 with Order ID, Order Date, Month, Region, Category, Product, Units Sold, Sales (USD) and Profit (USD).

Note: this is a sample dataset generated for this exercise. The structure matches the Sample Superstore dataset, so the real data can be loaded in the same columns.

KPIs
KPI	Meaning
Total Sales	Sum of sales for the current selection
Profit Margin	Total profit divided by total sales (green = 15% or more, red = below 10%)
Units Sold	Total quantity sold
Top Region	Region with the highest sales
Visuals
Sales by Product Category (column chart)
Monthly Sales Trend (line chart)
Sales by Region (bar chart)
Interactivity
Region filter: All, East, West, North, South
Month filter: All, Jan to Dec

Selecting a value updates the KPIs and charts. In the Excel version the filters are dropdown cells driven by SUMIFS formulas; in the Power BI version they are slicers.

Key Takeaways (all regions, full year)
Total sales are about $2.05 million with a profit margin of about 10.4%.
West is the top region and Technology is the largest category.
Sales rise strongly in the last quarter, peaking in November and December.
Design Choices
Only 4 KPIs, to keep the first dashboard simple.
Consistent colour coding: green for healthy margin, red for weak margin.
Filters for month and region so the viewer can explore without the analyst.
Files
File	Description
Sales_Dashboard_Task3.xlsx	Interactive Excel dashboard (Dashboard, Data and Calc sheets)
Sales_Dashboard_Task3.pbix	Power BI dashboard
dashboard_screenshot.png	Screenshot of the dashboard
Dashboard_Note.pdf	One-page note explaining how to read the dashboard
README.md	This file
How to Use
Excel: open the file, go to the Dashboard sheet and use the yellow dropdown cells to filter by region and month.
Power BI: open the .pbix file in Power BI Desktop and use the Region and Month slicers.
