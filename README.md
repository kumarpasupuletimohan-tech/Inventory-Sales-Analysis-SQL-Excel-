# Inventory-Sales-Analysis-SQL-Excel-
End-to-end inventory and sales analysis using SQL and Excel to track revenue trends, product performance, and regional sales insights.



This project focuses on analyzing inventory and sales data to uncover business insights such as revenue trends, top-performing products, and regional sales distribution.


![inventory22](https://github.com/user-attachments/assets/f50cedbf-fe4d-423a-98dc-21b78875b5b6)


 Objectives
 Analyze sales performance across regions
 Identify top-selling products
 Track revenue trends over time
 Optimize inventory decisions using data insights

 ![inventory23](https://github.com/user-attachments/assets/61fc0bc5-735a-460c-83c4-13aec8eecf35)


Tools & Technologies
 SQL (MySQL/PostgreSQL)
 Microsoft Excel

![inventory24](https://github.com/user-attachments/assets/7108c773-512f-4a8b-bb10-1d1fbeedd124)


 Dataset Details
The dataset includes:
 Order ID
 Product Name
 Category
 Region
 Sales Quantity
 Revenue
 Order Date

![inventory25](https://github.com/user-attachments/assets/2ce78499-5718-433b-95f8-47bd9b5efeb2)


 Key Analysis Performed
 Total Revenue Calculation
 Monthly Sales Trends
 Top 5 Products by Revenue
 Region-wise Sales Analysis
 Category Performance Insights

  Sample SQL Queries
sql
 Total Revenue
SELECT SUM(revenue) AS total_revenue FROM sales;

Top Products
SELECT product, SUM(revenue) AS revenue
FROM sales
GROUP BY product
ORDER BY revenue DESC
LIMIT 5;
