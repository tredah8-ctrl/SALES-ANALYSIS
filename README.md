#  📊 Sales Case Study Dashboard

## Project Overview

This project analyzes a simulated retail sales dataset containing daily trading information for a single product sold by a large retail store. The objective was to transform raw transactional data into meaningful business insights by calculating key performance metrics, identifying sales trends, evaluating profitability, and assessing the effectiveness of promotional pricing.

The project demonstrates an end-to-end data analytics workflow, including data exploration, data cleaning, SQL transformations, metric development, dashboard design, and business recommendations.

---

## Business Objectives

The analysis aims to answer the following business questions:

* What is the daily sales price per unit?
* What is the average unit sales price?
* What is the daily gross profit percentage?
* What is the daily gross profit percentage per unit?
* Which promotional periods can be identified?
* What is the Price Elasticity of Demand (PED) during promotional periods?
* Does the product perform better when sold at a promotional price?

---

## Dataset

The dataset contains daily aggregated sales information with the following fields:

* **Date** – Trading date
* **Sales** – Total sales revenue (Rand)
* **Cost Of Sales** – Total cost of goods sold (Rand)
* **Quantity Sold** – Total units sold

---

## Data Preparation

Before analysis, the dataset was explored and cleaned by:

* Understanding the business requirements
* Examining the dataset structure
* Checking data types
* Identifying missing values
* Checking for duplicate records
* Validating sales, cost, and quantity values
* Creating reusable SQL Common Table Expressions (CTEs)
* Engineering new analytical features

---

## Metrics Developed

The following business metrics were calculated:

* Sales Price Per Unit
* Average Unit Sales Price
* Gross Profit
* Gross Profit Percentage
* Gross Profit Per Unit
* Gross Profit Percentage Per Unit
* Running Total Sales
* Running Total Gross Profit
* Average Daily Sales
* Average Daily Quantity Sold

---

## SQL Techniques Used

This project demonstrates practical SQL skills including:

* SELECT Statements
* Common Table Expressions (CTEs)
* Aggregate Functions
* Mathematical Calculations
* CASE Statements
* Date Functions
* GROUP BY
* ORDER BY
* Filtering
* Derived Columns
* Business Metric Calculations

---

## Dashboard Features

The interactive dashboard includes:

* Executive KPI Cards
* Daily Sales Trend
* Gross Profit Trend
* Monthly Sales Analysis
* Quantity Sold Analysis
* Pricing Analysis
* Profitability Analysis
* Running Total Sales
* Running Total Gross Profit
* Sales by Day of Week
* Weekend vs Weekday Analysis
* Interactive Filters
* Dynamic Insights
* Business Recommendations

---

## Key Insights

The analysis helps identify:

* High and low sales periods
* Daily pricing trends
* Profitability performance
* Loss-making days
* Potential promotional periods
* Customer demand response to pricing
* Overall sales performance over time

---

## Business Recommendations

Based on the analysis, recommendations include:

* Monitor products with declining profit margins.
* Optimize pricing strategies to maximize profitability.
* Use promotions strategically where demand is price-sensitive.
* Increase inventory during peak sales periods.
* Investigate causes of loss-making days.
* Continuously monitor pricing and sales trends to support business decisions.

---

## Tools & Technologies

* SQL
* Databricks
* Git & GitHub
* Power BI / Tableau / Lovable (Dashboard Development)
* Microsoft Excel

---

## Project Workflow

1. Business Understanding
2. Data Exploration
3. Data Cleaning
4. Data Validation
5. Feature Engineering
6. Metric Development
7. SQL Analysis
8. Dashboard Design
9. Business Insights
10. Business Recommendations

---

## Repository Structure

```text
Sales-Case-Study/
│
├── Dataset/
│   └── Sales Case Study.xlsx
│
├── SQL/
│   ├── Data_Cleaning.sql
│   ├── CTE_Analysis.sql
│   ├── Metrics.sql
│
├── Dashboard/
│   ├── Dashboard.pbix (or dashboard screenshots)
│   └── Dashboard Images/
│
├── README.md
└── LICENSE
```

---

## Learning Outcomes

Through this project, I strengthened my skills in:

* Data exploration
* SQL querying
* Data cleaning
* Business metric calculations
* Sales and profitability analysis
* Dashboard development
* Data storytelling
* Business decision support

---

## Author

**Hitekani Masingi**

Aspiring Data Analyst passionate about transforming raw data into meaningful insights through SQL, analytics, and interactive dashboards.
