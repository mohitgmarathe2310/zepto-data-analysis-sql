# zepto-data-analysis-sql

📌 Project Overview

This project focuses on analyzing an e-commerce inventory dataset from Zepto using PostgreSQL.
The goal of this project is to perform data cleaning, exploratory data analysis (EDA), and business insight generation using SQL queries.

Through this project, I explored product pricing, stock availability, product categories, and discount patterns to generate useful business insights.

📊 Dataset Information

The dataset contains product-level information from Zepto's inventory, including:

Product Name

Category

MRP (Maximum Retail Price)

Discounted Price

Discount Percentage

Available Quantity

Product Weight

This dataset simulates real-world e-commerce inventory data used for analytical purposes.

🛠 Tools & Technologies Used

PostgreSQL

SQL

GitHub

Data Cleaning Techniques

Exploratory Data Analysis (EDA)

🧹 Data Cleaning Steps

Several cleaning operations were performed to ensure accurate analysis:

Removed duplicate records

Handled missing values

Converted price units where required

Filtered incorrect values (e.g., products with zero price)

Standardized column formats

🔎 Key Analysis Performed

The following business questions were analyzed using SQL:

Total number of products available

Number of products in each category

Products with the highest discount

Most expensive and least expensive products

Average price of products per category

Stock availability analysis

Revenue estimation based on price and quantity

📈 Example SQL Concepts Used

SELECT statements

WHERE filtering

GROUP BY

ORDER BY

Aggregate Functions (SUM, AVG, MAX, MIN)

CASE statements

Data Cleaning queries

💡 Key Insights

Some product categories offer significantly higher discounts.

Certain categories have a higher concentration of products.

Pricing variation across categories indicates different pricing strategies.

Inventory distribution highlights potential high-demand product groups.
