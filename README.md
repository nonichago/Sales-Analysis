# Retail Sales Performance Analysis Using Python

## Project Overview

This project analyses retail sales data using Python to understand business performance, identify sales trends, evaluate product categories, and examine customer and regional performance.

The project follows a practical data analysis workflow, covering data inspection, data cleaning, exploratory data analysis (EDA), data visualisation, and business recommendations.

## Business Problem

The company wants to understand its sales performance and identify opportunities to improve revenue, customer retention, regional performance, and profitability.

The analysis answers five business questions:

1. How do sales change over time?
2. Which product categories generate the highest revenue?
3. Who are the top 10 customers by total spending?
4. Which regions generate the highest sales?
5. How does discount affect sales and profitability?

## Project Objectives

- Inspect and clean the raw sales dataset.
- Identify and remove duplicate records.
- Handle missing values and inconsistent data.
- Standardise category and region names.
- Convert columns into appropriate data types.
- Perform exploratory data analysis.
- Create visualisations to answer business questions.
- Generate actionable business insights.

## Tools and Technologies

| Tool | Purpose |
|---|---|
| Python | Data analysis |
| Pandas | Data cleaning and manipulation |
| NumPy | Numerical operations |
| Matplotlib | Data visualisation |
| Seaborn | Statistical visualisation |
| VS Code / Jupyter Notebook | Development environment |
| GitHub | Project documentation |

## Dataset Description

The dataset contains retail transaction information, including:

- Order details
- Customer information
- Product information
- Sales and profit figures
- Discounts
- Payment methods
- Sales channels
- Order status
- Geographical information

The original dataset was deliberately made messy to simulate real-world data quality challenges.

## Data Cleaning Process

The following cleaning activities were performed:

1. Removed exact duplicate records using `drop_duplicates()`.
2. Removed unnecessary spaces from text columns.
3. Standardised text formatting.
4. Corrected inconsistent product category names.
5. Standardised inconsistent region names.
6. Converted order and shipping dates into datetime format.
7. Converted numerical columns into appropriate numeric data types.
8. Standardised discount values into decimal format.
9. Identified invalid customer ages and quantities.
10. Removed records missing essential information for the analysis.
11. Created additional date columns, including Month, Year, and Month_Year.

## Exploratory Data Analysis and Business Questions

### 1. How do sales change over time?

**Visualisation:** Line Chart

Monthly sales were analysed from January 2024 to December 2025.

**Key Findings:**
- December 2024 recorded the highest monthly sales of ₦67,600.30
- March 2025 recorded the lowest monthly sales of ₦39,094.30
- Total sales across the analysis period amounted to ₦111,552,790.

**Business Insight:**

Sales fluctuated throughout the period, with December 2024 recording the strongest performance. The company should investigate the factors behind this peak and improve planning for weaker sales months.

### 2. Which product categories generate the highest revenue?

**Visualisation:** Bar Chart

Sales were grouped by product category to identify the categories contributing the most revenue.

| Category | Total Sales |
|---|---:|
| Furniture | ₦56,369,100 |
| Electronics | ₦34,635,250 |
| Accessories | ₦7,042,675 |
| Lifestyle | ₦6,912,025 |
| Stationery | ₦3,307,735 |

**Key Finding:**

Furniture generated the highest revenue, contributing approximately 50.5% of total sales.

**Business Insight:**

The company should maintain adequate inventory for high-performing categories, particularly Furniture and Electronics, while exploring ways to improve sales in lower-performing categories.

### 3. Who are the top 10 customers by total spending?

**Visualisation:** Horizontal Bar Chart

Customer sales were aggregated to identify the ten highest-spending customers.

| Customer | Total Spending |
|---|---:|
| Luka Okafor | ₦2,027,960 |
| Mariam Bello | ₦1,907,180 |
| Bola Balogun | ₦1,610,260 |
| Ifeoma Bello | ₦1,493,800 |
| Dami Umar | ₦1,438,315 |
| Rita Adebayo | ₦1,346,270 |
| Chidi Adebayo | ₦1,299,700 |
| Emeka Ojo | ₦1,285,000 |
| Uche Ibrahim | ₦1,268,560 |
| Grace Ojo | ₦1,150,975 |

**Key Finding:**

Luka Okafor was the highest-spending customer, with total purchases of ₦2,027,960.

**Business Insight:**

The company should consider customer loyalty programmes and targeted offers to strengthen relationships with its highest-value customers.

### 4. Which regions generate the highest sales?

**Visualisation:** Bar Chart

Sales were grouped by region to compare geographical performance.

| Region | Total Sales |
|---|---:|
| South West | ₦24,386,970 |
| North Central | ₦20,140,900 |
| South South | ₦18,828,260 |
| South East | ₦18,019,390 |
| North West | ₦16,981,630 |
| North East | ₦9,909,635 |

**Key Finding:**

South West recorded the highest sales, while North East recorded the lowest.

**Business Insight:**

The company should investigate the factors driving strong sales in the South West and identify opportunities to improve performance in the North East.

### 5. How does discount affect sales and profitability?

**Visualisation:** Scatter Plot

Discounts were grouped into four categories to compare total sales and profit.

| Discount Group | Total Sales | Total Profit |
|---|---:|---:|
| No Discount | ₦40,776,500 | ₦11,537,345 |
| Low Discount | ₦42,844,785 | ₦9,953,337.55 |
| Medium Discount | ₦20,140,200 | ₦3,546,631.63 |
| High Discount | ₦4,210,200 | ₦498,187.48 |

**Key Findings:**
- Low-discount orders generated the highest total sales.
- Orders without discounts generated the highest total profit.
- High-discount orders generated the lowest total profit.

**Business Insight:**

The company should review its discount strategy to ensure that promotional activities increase sales without unnecessarily reducing profitability.

The findings show an association between discount levels and profitability; they do not establish that discounts alone caused the differences.

## Overall Project Findings

- Total sales amounted to ₦111,552,790.
- Furniture was the highest-revenue product category.
- South West was the highest-performing region.
- December 2024 recorded the highest monthly sales.
- Luka Okafor was the highest-spending customer.
- Orders without discounts generated the highest total profit.

## Business Recommendations

1. **Improve seasonal planning:** Investigate the factors behind strong December sales and prepare inventory and marketing strategies for high-demand periods.
2. **Prioritise profitable categories:** Maintain adequate stock of high-performing product categories.
3. **Strengthen customer retention:** Develop loyalty initiatives for high-spending customers.
4. **Improve regional performance:** Explore opportunities to increase sales in lower-performing regions.
5. **Review discount policies:** Monitor the effect of promotional discounts on total profit before introducing larger discounts.

## Conclusion

This project demonstrates how Python can be used to transform raw retail sales data into meaningful business insights.

Through data cleaning, exploratory data analysis, and visualisation, the project identified sales trends, high-performing product categories, valuable customers, regional performance, and the relationship between discounts and profitability.

The findings provide a foundation for better inventory planning, customer retention, regional marketing, and pricing decisions.

