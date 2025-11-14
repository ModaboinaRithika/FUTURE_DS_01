Task 1 — Business Sales Dashboard (E-Commerce Dataset)
1) Objective

Analyze e-commerce sales data to identify best-selling products, sales trends, and high-revenue categories using Power BI.

Best-selling products
Sales & profit trends
High-revenue categories
Customer & regional performance


2) Tools Used

Power BI Desktop
Power Query (Data Cleaning)
DAX (Data Analysis Expressions)
Excel (initial checks)

3) steps Performed :
   
Data Cleaning Steps (Power Query Editor)

Steps applied:

Order Date → Date
Ship Date → Date
Sales, Profit, Quantity → Whole Numbers/Decimal
Category, Sub-category → Text
Removed Blank Rows
Removed Duplicates
Replaced missing Customer IDs with “Unknown”
Fixed text columns: trimmed, cleaned


4) DAX Measures Used :
   
Total Sales = SUM(Data[Sales])
Total Quantity Sold = SUM(Data[Quantity])
Total Profit = SUM(Data[Profit])
Total Customers = DISTINCTCOUNT(Data[Customer ID])
Average Order Value = [Total Sales] / [Total Customers]

5) Dashboard Insights

Charts
Sales by Category (Bar Chart)
Profit by Category (Bar Chart)
Sales by Sub-Category (Horizontal Bar)
Sales Trend (Year/Month) (Line Chart)
Top 10 Products by Sales
Sales by Region / State (Map Chart)
Profitability by Segment (Donut Chart)

