📊 Superstore Sales Insights Dashboard (Power BI)
This project is a Power BI Sales Insights Dashboard built using the Superstore dataset.
<img width="1198" height="670" alt="Superstore Dashboard Overview" src="https://github.com/user-attachments/assets/f2ac7eb0-111e-483f-aafe-a2f188512377" />



It analyzes sales, profit, product performance, and regional trends to provide clear, actionable business insights.


🔍 Project Overview
The goal of this project is to demonstrate core Power BI skills:

Data cleaning and transformation

Building a Date table using DAX

Creating measures for key business metrics

Designing interactive visuals

Adding slicers for dynamic filtering

Writing insights based on data analysis

This dashboard is designed as a single‑page executive summary.

🛠 Tools & Techniques Used
Power BI Desktop

DAX (Data Analysis Expressions)

Data Modeling

Slicers & Filters

Interactive Visuals


📅 DAX Measures
Total Sales = SUM(Orders[Sales])

Total Profit = SUM(Orders[Profit])

Profit Margin = DIVIDE([Total Profit], [Total Sales])

Total Quantity = SUM(Orders[Quantity])

Date Table:
Date = CALENDAR(MIN(Orders[Order Date]), MAX(Orders[Order Date]))


📈 Dashboard Visuals
The report includes:
KPI Cards: Total Sales, Total Profit, Profit Margin

Sales Trend Over Time (Line Chart)

Sales by Region (Bar Chart)

Profit by Category (Bar Chart)

Top 10 Products by Sales (Bar Chart)

Slicers: Date, Region, Category

Insights Text Box


🧠 Key Insights
Technology leads in total sales across all regions.

Office Supplies shows strong profit margins despite lower sales volume.

The West region consistently outperforms other regions.

Top 10 products contribute a significant portion of total revenue.


📁 Files Included
Superstore_Sales_Insights.pbix — Power BI report file

README.md — Project documentation

🎯 Purpose
I built this dashboard to strengthen my Power BI skills and demonstrate my ability to analyze data, create DAX measures, and design interactive business dashboards.
