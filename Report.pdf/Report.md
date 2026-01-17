# Business Sales Analysis Report

## 1. Introduction
This project focuses on analyzing business sales data to identify sales trends,
customer behavior, and product performance. The insights derived can help
businesses improve decision-making, optimize product strategy, and increase revenue.

---

## 2. Dataset Description
The dataset contains transactional sales data with the following attributes:
- Order ID
- Order Date
- Customer ID
- Product Name
- Category
- Quantity
- Price

Additional features such as Total Sales, Year, Month, and Month Name were created
during data preprocessing.

---

## 3. Data Cleaning & Preparation
The following steps were performed:
- Removed duplicate records
- Converted order date to datetime format
- Created derived features:
  - Total Sales = Quantity × Price
  - Year, Month, Month Name

The cleaned dataset was saved as `clean_sales_data.csv`.

---

## 4. Sales Trend Analysis
Monthly sales trends were analyzed to identify peak and low-performing periods.

**Key Observation:**
- Sales show variation across months, indicating possible seasonal trends.

![Monthly Sales Trend](figure)
