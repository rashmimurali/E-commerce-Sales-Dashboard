

# 📊 E-commerce Analytics Dashboard (Power BI Project)

# 🎯 Goal

The objective of this project was to design an end-to-end analytics solution for an e-commerce business. The focus was on tracking revenue growth, customer behavior, product performance, and churn trends to enable data-driven decision making.


# Dataset & Flow

1. Data Sources (CSV files):

a. Customers: demographics, region, join date, churn date

b. Products: categories, subcategories, price

c. Orders: customer-product transactions, order dates, discounts, payment method

d. Returns: order returns and reasons


#  Data Preparation:

Loaded CSVs into Power BI using Power Query

Created a Date table for time intelligence (Year, Month, Quarter)


Cleaned & merged tables based on ERD relationships:

Customers ↔ Orders

Products ↔ Orders

Orders ↔ Returns


# Modeling & Measures (DAX):

 a.Revenue KPIs: Total Revenue, Average Order Value (AOV), Customer Lifetime Value (LTV)

 b. Customer KPIs: Net Adds (New – Churned), Churn Rate

 c. Product KPIs: Top Products by Revenue, Returns %, Category Distribution


# Dashboard Design (Power BI):

1. Executive Summary Page: KPI cards, revenue trend, revenue by category

2. Customer Insights Page: customers by region, churn vs retention, cohort analysis

3. Product Insights Page: top products, revenue by category, product return analysis

4. Churn & Retention Page: Net Adds trend, customer lifecycle funnel

# ✅ Results & Insights

Identified top-selling categories and products with high returns

Tracked monthly revenue growth and customer churn trends

Highlighted regional performance and age-group level customer distribution

Estimated Customer Lifetime Value from order patterns

Delivered a single source of truth for executives, product teams, and marketing to make informed decisions

# 🛠️ Tools & Technologies

Power BI (DAX, Power Query) → Data modeling & visualization

SQL (SQLite) → Data cleaning and relationships

Excel → Initial exploration
