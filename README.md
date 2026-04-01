E-commerce Sales Analytics Pipeline

End-to-end data analytics project using Python, SQL, and Power BI to analyze e-commerce sales data and generate actionable business insights.

Project Overview

This project presents a complete analytics workflow on a simulated e-commerce dataset designed to reflect real-world data challenges. It demonstrates the ability to generate, clean, analyze, and visualize transactional data, transforming raw inputs into decision-ready insights.

The dataset was intentionally engineered with inconsistencies such as missing values, duplicate records, incorrect data types, and categorical errors to simulate real business scenarios.

Objective
Simulate real-world transactional data with quality issues
Perform data cleaning and transformation using Python
Conduct analytical querying using SQL
Build an interactive dashboard in Power BI
Generate actionable insights to support business decision-making
Tools & Technologies
Python (Pandas, NumPy)
Google Colab
SQL (SQLite)
Power BI
Dataset Description

The dataset contains 1200+ transaction records, including:

Order and customer information
Product details (category, pricing)
Transaction metrics (quantity, total price, discount)
Payment methods
Regional data
Order status
Simulated Data Challenges
Duplicate Order IDs
Missing values in key columns (OrderDate, ProductName, ShippingCost)
Inconsistent categorical values (e.g., “Credit Card” vs “Creditcard”)
Incorrect data types (Price stored as text)
Negative quantities
Price outliers
Data Generation & Preparation

A synthetic dataset was generated using Python to simulate realistic e-commerce transactions. Randomization techniques were used to model customer behavior, product selection, and pricing variation.

Intentional inconsistencies were introduced to replicate real-world data issues and validate the robustness of the data cleaning process.

Data Cleaning (Python)

Data preprocessing was performed using Pandas:

Converted Price column to numeric format
Handled missing values:
Imputed shipping cost using mean
Removed or treated critical null records
Standardized categorical variables:
Fixed inconsistencies in payment methods and categories
Identified and validated duplicate OrderID values
Removed invalid records (e.g., negative quantities)
Ensured consistency in calculated fields such as TotalPrice

The cleaned dataset was exported for downstream analysis.

SQL Analysis

SQL was used to perform structured querying and simulate a production-level analytics workflow.

Key Operations
Revenue and order aggregation
Identification of high-value customers using subqueries
Creation of reusable analytical views
Customer ranking using window functions
Feature engineering for reporting
Key Outputs
Customer Summary (total orders, total spend)
Category Revenue Analysis
Payment Method Performance
Ranked customer segmentation
Final analytical table with:
Net revenue calculation
Monthly and yearly time features
Power BI Dashboard

An interactive dashboard was built to visualize business performance and key trends.

Key Metrics
Total Revenue: 3.01M
Average Order Value: 2.70K
Total Customers: 1115
Total Quantity Sold: 6168
Dashboard Insights
Electronics category contributes the highest share of revenue
Certain regions consistently outperform others, indicating demand concentration
Revenue trends show periodic spikes, suggesting seasonal or campaign-driven growth
Digital payment methods dominate transactions
A small group of customers contributes significantly to overall revenue
Business Recommendations
Allocate budget toward high-performing categories and regions
Leverage time-based trends to optimize campaign timing
Focus on high-value customer segments for retention strategies
Improve product positioning for underperforming items
Implement data validation processes to reduce inconsistencies
Project Structure
ecommerce-sales-analytics-pipeline
 ┣ README.md
 ┣ data
 ┃ ┣ cleaned_ecommerce_sales.csv
 ┣ python
 ┃ ┗ data_cleaning_eda.ipynb
 ┣ sql
 ┃ ┗ analysis_queries.sql
 ┣ dashboard
 ┃ ┗ ecommerce_dashboard.pbix
 ┗ images
   ┗ dashboard.png
End-to-End Workflow
Data Generation (Python)
Data Cleaning & Transformation (Python)
Data Analysis (SQL)
Data Visualization (Power BI)

This workflow reflects a real-world analytics pipeline used in business environments.

Use of AI Tools

AI tools were used selectively for debugging, improving workflow efficiency, and refining documentation. All analytical decisions, data modeling, and insights were developed independently.

Conclusion

This project demonstrates the ability to work with raw, unstructured data and transform it into meaningful insights using Python, SQL, and Power BI.

It reflects a strong understanding of the data analysis lifecycle and showcases readiness to contribute effectively in a data-driven role.
