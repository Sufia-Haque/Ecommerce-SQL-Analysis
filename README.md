# Ecommerce-SQL-Analysis
SQL Business Analysis on E-Commerce Sales Data using MySQL
 
 Project Overview
This project performs an end-to-end SQL Business Analysis on a real-world E-Commerce Sales dataset covering transactions from 2023 to 2025. Using MySQL Workbench, I explored sales performance, customer behavior, regional trends, and profitability across product categories — answering 7 critical business questions that a data analyst would face in a real company.

 Business Objective

"Identify key revenue drivers, uncover loss-making areas, and provide actionable recommendations to improve profitability across regions, categories, and product lines."

Key Business Insights
1.  Category Performance

Analyzed total orders, quantity, sales, profit and profit margin across all product categories
Identified which categories drive the most revenue vs which are most profitable

2.  Regional Analysis

Compared sales and profit performance across North, South, East and West regions
Calculated average order value per region to identify high-value markets

3. Monthly Sales Trend

Extracted month and year from Order Date to build a time series analysis
Revealed seasonal patterns and peak sales months across 2023–2025

4. Discount Impact

Used CASE WHEN logic to group orders into discount brackets:
No Discount | Low (1–10%) | Medium (11–20%) | High (20%+)
Found that higher discounts significantly reduce average profit — key pricing insight

5. Least-profit-Making Products

Ranked the top 10 worst-performing products by total loss
These products are strong candidates for repricing or discontinuation

6. Year-over-Year Growth

Used CTE + LAG Window Function to calculate YoY sales growth %
Provides executive-level insight into business growth trajectory

Business Recommendations-
Based on the SQL analysis, here are key recommendations:

1. Focus marketing on top-performing regions — allocate more budget to highest profit margin areas

2. Review discount strategy — high discounts (20%+) are hurting profitability significantly

3. Discontinue or reprice loss-making products — identified via negative profit filter

4. Capitalize on peak season months — revealed by monthly trend analysis

5. Invest in top sub-categories — double down on highest profit margin product lines


This project is part of my data analytics portfolio built to demonstrate real-world SQL skills for junior data analyst roles.
