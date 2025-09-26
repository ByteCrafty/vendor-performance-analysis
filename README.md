# vendor-performance-analysis
End-to-end vendor performance analysis in retail using Python, SQL, and Power BI. Covers data ingestion, EDA, and dashboards to track KPIs like sales, purchases, gross profit, margin, unsold capital, and brand-wise vendor insights. Helps identify top/low vendors, optimize pricing, and boost profitability.
## Project Overview
This project analyzes vendor performance in the retail and wholesale industry to help optimize profitability, inventory turnover, and vendor selection.
The analysis covers:
- Identifying top vendors contributing to sales and profit.
- Detecting underperforming brands/vendors needing price or promotional adjustments.
- Assessing the impact of bulk purchases on costs.
- Evaluating unsold capital and inventory efficiency.
- Comparing profitability across vendors to guide better sourcing decisions.

## Business Problem
Effective inventory and sales management is critical in retail/wholesale. Companies risk losses from:
- Inefficient pricing strategies
- Poor inventory turnover
- Vendor dependency
- High freight costs
This analysis provides actionable insights into vendor performance to support procurement, pricing, and sales strategy decisions.

## Tech Stack
Python → Data ingestion, preprocessing (Pandas, SQLAlchemy, Logging)
- SQL (SQLite) → Data cleaning, aggregation, KPI calculations
- Matplotlib & Seaborn → Exploratory Data Analysis (EDA) visualizations
- Power BI → Dashboard creation and visualization
- Pandas / Jupyter Notebook → Data exploration and feature creation

## Dataset
The dataset consists of multiple tables ingested from CSVs into a SQLite database:
Source:
- <a href="https://github.com/ByteCrafty/vendor-performance-analysis/blob/main/vendor_sales_summary.csv">Vendor_Sales_summary</a>
- Purchases → Purchase transactions (vendor, brand, quantity, dollars)
- Purchase_Prices → Standard cost & pricing info (unique vendor-brand)
- Vendor_Invoice → Aggregated vendor invoice data (PO-level with freight)
- Sales → Actual sales transactions (quantity sold, sales dollars, revenue)
