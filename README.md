[README.md](https://github.com/user-attachments/files/35032176/README.md)[Uploading RE## Dashboard Preview

![Executive Dashboard](Executive_Dashboard.png)


# Sales Performance & Business Analysis Dashboard using Power BI

## Project Overview

This project presents an interactive Sales Performance and Business Analysis Dashboard developed using Microsoft Power BI. The dashboard transforms raw sales data into meaningful business insights across sales, profit, products, categories, regions, and time.

## Project Objective

The objective of this project is to analyze sales and profitability performance and provide an interactive dashboard that helps identify high-performing categories, regions, and products while supporting data-driven business decisions.

## Tools & Technologies

* Microsoft Power BI Desktop
* Power Query
* DAX (Data Analysis Expressions)
* Microsoft Excel

## Dashboard Pages

### 1. Executive Dashboard

Provides an overall view of business performance through key performance indicators and visualizations, including:

* Total Sales
* Total Profit
* Total Orders
* Total Quantity
* Profit Margin
* Sales by Category
* Profit by Category
* Sales by Region

### 2. Regional Analysis

Analyzes sales and profit performance across different regions and categories.

Key visuals include:

* Profit by Region
* Profit by Category & Region
* Sales by Category & Region

### 3. Sales Trend Analysis

Shows how sales fluctuate over time using a time-series line chart.

### 4. Product Analysis

Analyzes product-level performance using:

* Top 10 Products by Sales
* Top 10 Products by Profit
* Top 10 Products by Profit Margin

## Key Business Insights

* Office Supplies generated the highest overall sales and profit among the three categories.
* East was the highest-performing region in terms of both sales and profit.
* Furniture was the strongest category within the East region based on sales and profit.
* Ergonomic Chair was the highest-selling product among the analyzed products.
* Premium Paper generated the highest profit among the Top 10 products by profit.
* Storage Box showed the highest profit margin among the Top 10 products analyzed by profit margin.
* The overall profit margin was approximately 13.37%.
* The average order value was approximately 1.41K.
* Sales showed a fluctuating trend over time rather than a consistent upward or downward pattern.

## Business Recommendations

* Continue strengthening the Office Supplies category because of its strong sales and profit performance.
* Analyze successful strategies in the East region and consider applying similar approaches to other regions.
* Focus on Furniture performance in the East region.
* Monitor profitability alongside sales volume because high sales do not necessarily mean high profit.
* Maintain the availability of high-profit products such as Premium Paper.
* Identify opportunities to increase sales of products with strong profit margins.
* Monitor sales trends over time to support better inventory and promotional planning.

## DAX Measures

```DAX
Total Sales = SUM(Sales_Data[Sales])

Total Profit = SUM(Sales_Data[Profit])

Total Orders = COUNT(Sales_Data[Order_ID])

Total Quantity = SUM(Sales_Data[Quantity])

Profit Margin % = DIVIDE([Total Profit], [Total Sales], 0)

Average Order Value = DIVIDE([Total Sales], [Total Orders], 0)
```

## Project Files

* `Sales_Performance_Dashboard.pbix` — Power BI dashboard file.
* `Sales_Performance_Dashboard_Documentation.docx` — Detailed project documentation.

## Conclusion

This project demonstrates how Power BI, Power Query, and DAX can be used to transform raw sales data into an interactive business intelligence solution. The dashboard provides insights into overall performance, regional trends, category performance, product profitability, and sales trends over time.
ADME.md…]()
