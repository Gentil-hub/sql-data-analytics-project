# SQL Data Analysis Project

## Overview
Exploratory SQL project analyzing sales, customers, and products using fact and dimension tables to generate insights and support data-driven decision-making.

## Objective
Analyze sales, customer, and product data using SQL to identify trends, evaluate business performance, and generate insights that support data-driven decision-making.

## Analysis Workflow
The project follows a structured data analysis approach:

1. Database Exploration – Understanding schema and data structure  
2. Dimension Analysis – Exploring categorical data  
3. Date Analysis – Identifying time-based patterns  
4. Measures Analysis – Calculating core business KPIs (e.g., sales, orders, and customer metrics) to evaluate overall business performance  
5. Magnitude & Ranking Analysis – Identifying top and bottom performers  
6. Change Over Time Analysis – Tracking trends and growth  
7. Cumulative Analysis – Running totals and long-term performance  
8. Performance Analysis – Evaluating business performance over time  
9. Part-to-Whole Analysis – Understanding contribution by category  
10. Customer Segmentation – Grouping customers based on behavior  
11. Reporting – Building customer and product-level reports  

## Key Insights
- A small segment of customers (VIP) contributes a significant portion of total revenue  
- Sales trends show consistent growth over time with identifiable patterns  
- Top-performing products drive the majority of overall sales  
- Customer purchasing behavior varies across different segments  
- Time-based analysis highlights changes in performance across periods  

## Technical Highlights
- Used window functions for running totals and trend analysis  
- Performed year-over-year analysis using LAG()  
- Applied CTEs to structure complex queries  
- Built customer segmentation logic using CASE statements  
- Created reusable reporting views for customer and product analysis  

## Skills
- SQL (Joins, Aggregations, Subqueries, Window Functions, CTEs)  
- Data Analysis & Exploratory Data Analysis (EDA)  
- Data Modeling (Fact & Dimension Tables)  
- Business Intelligence & Reporting  

## Project Structure
- `datasets/` – Source databases containing fact and dimension tables  
- `scripts/` – SQL scripts covering exploration, analysis, segmentation, and reporting  
- `README.md` – Project documentation  

## Notes
This project is based on concepts learned from Baraa Khatib Salkini. Additional queries and modifications were implemented to extend the analysis and demonstrate practical data analytics skills.
