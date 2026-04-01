Ecommerce Sales Analytics Pipeline

Built an end-to-end analytics pipeline to transform messy e-commerce sales data into actionable business insights using Python, SQL, and Power BI.

Project Overview

This project demonstrates a complete data analytics workflow on a simulated e-commerce dataset designed to replicate real-world data challenges. It showcases the ability to clean, transform, analyze, and visualize raw transactional data, enabling data-driven decision-making.

The dataset was intentionally engineered with inconsistencies such as missing values, duplicate records, incorrect data types, and categorical errors to simulate practical business scenarios.

Business Problem

Businesses often deal with fragmented and inconsistent sales data, making it difficult to identify key revenue drivers, customer behavior patterns, and growth opportunities.

This project addresses these challenges by building a structured analytics pipeline that converts unreliable raw data into meaningful insights for decision-making.

Objective
Simulate real-world transactional data with quality issues
Perform data cleaning and transformation using Python
Conduct analytical querying using SQL
Build an interactive dashboard in Power BI
Generate actionable insights to support business decisions
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

A synthetic dataset was generated using Python to simulate realistic e-commerce transactions. Randomization techniques were applied to model customer behavior, product selection, and pricing variation.

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

SQL was used to simulate a production-level analytics workflow and perform structured querying.

Advanced SQL Techniques Used
Subqueries for customer segmentation
Window functions (RANK) for customer ranking
View creation for reusable analysis
Feature engineering for reporting datasets
Key Outputs
Customer Summary (total orders, total spend)
Category Revenue Analysis
Payment Method Performance
Ranked customer segmentation
Final analytical table with:
Net revenue calculation
Monthly and yearly time features
Power BI Dashboard

Power BI file is included in the /dashboard folder for full interactive exploration.

Key Metrics
Total Revenue: 3.01M
Average Order Value: 2.70K
Total Customers: 1115
Total Quantity Sold: 6168
Key Insights
Electronics contributes approximately 35–40% of total revenue, making it the primary revenue driver
Top-performing regions generate a significantly higher share of revenue, indicating geographic demand concentration
Revenue trends show periodic spikes, suggesting seasonal or campaign-driven growth patterns
Digital payment methods (Credit Card and PayPal) dominate transactions, reflecting customer preference for convenience
A small percentage of customers contributes a disproportionately large share of total revenue, indicating strong customer concentration
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
 ┃ ┗ cleaned_ecommerce_sales.csv
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

Why This Project Matters

This project simulates a real-world analytics scenario where raw data is unreliable and fragmented. It demonstrates how structured data workflows enable better decision-making across marketing, sales, and operations.

Use of AI Tools

AI tools were used selectively for debugging, improving workflow efficiency, and refining documentation. All analytical decisions, data modeling, and insights were developed independently.

License

This project is licensed under the MIT License.

Conclusion

This project demonstrates the ability to transform raw, messy data into actionable insights using Python, SQL, and Power BI.

It reflects a strong understanding of the data analysis lifecycle and showcases readiness to contribute effectively in a data-driven role.
