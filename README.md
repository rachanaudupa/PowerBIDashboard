Retail Store Sales Analysis Dashboard

This repository showcases a Power BI dashboard that provides detailed insights into the sales performance of a retail store. The dashboard presents various key metrics, allowing users to analyze data by categories, sub-categories, cities, and states, along with trends in sales and profit distribution.

Dashboard Overview
Key Features:
Total Profit: Displays the total profit generated by the retail store.

Total Sales: Highlights the overall revenue from all transactions.

Total Quantity Sold: Provides the total number of items sold.

Sales and Profit by Category: A visual comparison of total sales and profit across product categories (Electronics, Clothing, Furniture, etc.).

Sales by Payment Mode: A pie chart showing sales based on different payment modes (COD, Credit Card, EMI, UPI, etc.).

Sales Trend: A line chart showing monthly sales trends, helping identify peak periods.

Sales and Profit by Cities: A breakdown of sales and profit by city, providing insights into the best and worst-performing regions.

Sales by State: Geographical data visualized on a map to showcase regional performance.

Top Performing Sub-Categories: Highlights the sub-categories contributing most to the profit.

Interactive Filters:
Category Filters: Users can filter by specific product categories (Clothing, Electronics, Furniture) to drill down into relevant data.
Month Selection: Enables users to filter data by specific months or review all months combined.
Data Source
Page Navigation Button: A built-in button allows users to easily switch between the Main Page and the Detail Page, providing flexibility in the level of analysis.

The dashboard was built by importing and joining two CSV files:

Orders.csv: Contains fields like City, Customer Name, Order Date, and State.
Details.csv: Includes details such as Amount, Category, Profit, Payment Mode, and Sub-Category.
Data Validation

Data was thoroughly checked for missing or erroneous values.

A relationship between the two files was created using the Order ID field.
Column validations (Amount, Profit, Quantity, etc.) ensured data integrity, with no issues detected.


Insights & Usage
This dashboard provides actionable insights for retail businesses by highlighting trends, top-performing regions, and areas of improvement. It helps stakeholders:

Track sales and profit growth over time.
Identify the best-performing categories and sub-categories.
Optimize inventory and marketing strategies based on payment preferences and geographical trends.
