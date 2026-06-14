# Regional_sales_analysis using_python_powerbi
# EDA Regional Sales Analysis 📊

## Overview

This project presents an end-to-end Exploratory Data Analysis (EDA) of Acme Co.'s U.S. regional sales data from 2014–2018. The objective is to uncover revenue drivers, profitability trends, customer behavior, regional performance, and business opportunities through data cleaning, feature engineering, visualization, and business-focused insights.

---

## Business Problem

Acme Co. wants to understand:

* Which products, customers, channels, and regions generate the highest revenue and profit.
* How sales performance varies across time and geography.
* Whether pricing strategies impact profitability.
* Which markets offer the greatest growth opportunities.
* How actual performance aligns with budget expectations.

---

## Project Objectives

* Analyze sales and profitability trends.
* Identify top-performing products and customers.
* Evaluate regional and state-level performance.
* Understand channel contribution to revenue.
* Detect anomalies and outliers.
* Generate actionable business recommendations.

---

## Dataset

The analysis combines multiple business datasets:

| Dataset              | Description                     |
| -------------------- | ------------------------------- |
| Sales Orders         | Transaction-level sales records |
| Customers            | Customer information            |
| Products             | Product catalog                 |
| Regions              | Geographic mappings             |
| State Region Mapping | State-to-region relationships   |

### Key Features

* Order Number
* Order Date
* Customer Name
* Product Name
* Quantity
* Unit Price
* Revenue
* Cost
* State
* Region
* Sales Channel
* Budget

---

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Plotly
* Jupyter Notebook

---

## Project Workflow

### 1. Data Ingestion

* Loaded multiple Excel sheets.
* Imported customer, product, sales, and region datasets.
* Verified schema consistency.

### 2. Data Cleaning

* Removed duplicate records.
* Standardized column names.
* Corrected data types.
* Handled missing budget values.
* Validated merged datasets.

### 3. Data Wrangling

Merged:

* Sales ↔ Customers
* Sales ↔ Products
* Sales ↔ Regions

Created a unified analytical dataset.

### 4. Feature Engineering

Generated new business metrics:

* Total Cost
* Profit
* Profit Margin %
* Monthly Periods
* Regional Aggregations

---

## Exploratory Data Analysis

### Time-Series Analysis

* Monthly Revenue Trend
* Seasonality Detection
* Revenue Stability Assessment

### Product Analysis

* Top 10 Products by Revenue
* Top 10 Products by Profitability
* Product Pricing Distribution

### Customer Analysis

* Top Customers by Revenue
* Customer Segmentation
* Revenue vs Profit Margin Analysis

### Channel Analysis

* Revenue Contribution by Channel
* Average Profit Margin by Channel

### Geographic Analysis

* Sales by Region
* Sales by State
* U.S. Revenue Choropleth Map

### Profitability Analysis

* Profit Margin Distribution
* Profit vs Pricing Analysis
* Cost Drivers

### Statistical Analysis

* Correlation Matrix
* Revenue Distribution
* Outlier Detection

---

## Key Insights

### Revenue Performance

* Revenue remained relatively stable between $23M–$26M monthly.
* Sales peaks were observed during late spring and summer months.

### Regional Insights

* West region generated the highest revenue.
* South and Midwest showed strong performance.
* Northeast presented expansion opportunities.

### Product Performance

* Products 25 and 26 were major revenue contributors.
* Several mid-tier products displayed strong growth potential.

### Customer Insights

* Top customers contributed disproportionately to overall revenue.
* Revenue concentration risk exists among key accounts.

### Channel Performance

* Wholesale accounted for over half of total revenue.
* Export channel delivered the highest average profit margins.

### Profitability

* Strong positive relationship between revenue and profit.
* Pricing significantly influences profitability outcomes.

---

## Business Recommendations

1. Expand high-margin export operations.
2. Increase investment in top-performing regions.
3. Develop growth campaigns for mid-tier products.
4. Reduce dependency on a small group of key customers.
5. Optimize pricing strategies for low-margin products.
6. Leverage successful product pricing models across categories.
7. Explore expansion opportunities in underperforming states.
8. Investigate sales declines during low-performing periods.
9. Improve customer retention initiatives.
10. Monitor and manage pricing outliers.

---

## Correlation Findings

| Variable Pair        | Correlation          |
| -------------------- | -------------------- |
| Revenue ↔ Profit     | Strong Positive      |
| Unit Price ↔ Revenue | Very Strong Positive |
| Unit Price ↔ Cost    | Very Strong Positive |
| Quantity ↔ Revenue   | Moderate Positive    |

---

## Project Structure

```text
EDA_Regional_Sales_Analysis/
│
├── EDA_Regional_Sales_Analysis.ipynb
├── Sales_data(EDA Exported).csv
├── README.md
│
├── images/
│   ├── monthly_sales_trend.png
│   ├── regional_sales.png
│   ├── state_choropleth.png
│   ├── top_products.png
│   └── correlation_heatmap.png
│
└── reports/
    └── business_insights.pdf
```

---

## Skills Demonstrated

### Data Analysis

* Exploratory Data Analysis
* Business Intelligence
* Statistical Analysis

### Python

* Pandas
* NumPy

### Data Visualization

* Matplotlib
* Seaborn
* Plotly

### Business Analytics

* Revenue Analysis
* Profitability Analysis
* Customer Analytics
* Regional Analytics

---

## Project Outcome

This analysis transformed raw transactional data into actionable business insights, enabling data-driven decision-making across product strategy, customer management, pricing optimization, and regional expansion planning.

---

### Author

**Aryan Yadav**

* Aspiring Data Analyst
* SQL | Python | Power BI | Data Analytics
* Portfolio Project: Regional Sales Analysis & Business Intelligence Dashboard 🚀
