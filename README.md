Customer Shopping Behavior Analysis

This project analyzes customer shopping behavior using Python, SQL(PostgreSQL), and Power BI. It uncovers patterns in spending, product preferences, customer segments, and subscription behavior using a dataset of 3,900 transactions across multiple product categories.

⭐ Project Overview

Performed end-to-end data analysis using Python (EDA), PostgreSQL (business queries), and Power BI (interactive dashboard).
Extracted insights to support decisions related to marketing, customer segmentation, and product strategy.

📊 Dataset Summary
Rows: 3,900
Columns: 18

Key Features:
Customer demographics
Purchase amount, category, size, color
Subscription status
Discount usage, promo codes
Review ratings and shipping type
Missing values: 37 in review ratings (handled with median imputation)

🐍 Exploratory Data Analysis (Python)

Data loading, cleaning, and column standardization
Missing value imputation by product category

Feature engineering:
Age groups
Purchase frequency
Checked redundant columns and removed promo_code_used
Loaded cleaned data into PostgreSQL for further analysis

🗄️ SQL Analysis (PostgreSQL)

Key business queries include:
Revenue comparison by gender and age groups
Top 5 highest-rated products
Discount-dependent products
Shipping method comparison
Customer segmentation (New, Returning, Loyal)
Correlation between repeat buying and subscription status
Top 3 products per category

📈 Power BI Dashboard

An interactive dashboard visualizes:
Revenue trends
Top categories and products
Demographic insights
Discount vs. non-discount behavior
Customer segmentation metrics

✅ Business Recommendations

Promote subscription benefits
Introduce loyalty programs
Improve discount strategy for profitability
Highlight top-rated and best-selling products
Target high-revenue customer groups with focused marketing

📁 Technologies Used

Python (Pandas)
PostgreSQL
Power BI
Jupyter Notebook
