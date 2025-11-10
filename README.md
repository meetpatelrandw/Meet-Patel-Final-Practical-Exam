Project Overview

This Excel project analyzes a 100-row sales dataset to demonstrate data import, cleaning, analysis, visualization, and dashboard creation using advanced Excel tools and formulas.

 Dataset Selection & Import

Imported Sales_Data_100.xlsx into Excel.

Verified data types (Date, Number, Text).

Removed unnecessary blank rows or headers.

 Data Cleaning & Preparation

Used Remove Duplicates under Data Tools.

Replaced missing or invalid values using IF and ISBLANK.

Formatted dates and numbers correctly.

 Pivot Tables

Created Pivot Table to analyze Sales by Region, Product Category, and Customer.

Summarized Total Sales, Average Profit, and Total Quantity Sold.

 Advanced Formulas Used
Formula	Purpose
=VLOOKUP(Customer_ID, CustomerTable, 3, FALSE)	Fetch customer name
=IF(Discount>0.1,"High","Low")	Categorize discounts
=INDEX(SalesRange, MATCH("East", RegionRange, 0))	Lookup using INDEX-MATCH
=SUMIFS(Profit, Region, "West", Category, "Clothing")	Conditional total profit
 Data Visualization

Created Column and Pie Charts to show Sales by Category and Profit by Region.

Applied Conditional Formatting for top/bottom sales performers.

 Interactive Dashboard

Added Slicers for filtering by Region and Category.

Used a Timeline for interactive analysis by Order Date.

Linked charts and Pivot Tables for dynamic updates.
