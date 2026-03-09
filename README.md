# Customer Behavior Analysis

Customer analytics project that explores customer purchasing/engagement patterns using **Python**, **SQL**, and **Power BI**. The goal is to identify actionable insights such as customer segments, retention opportunities, and revenue drivers.

## Project Overview
**Objective:**  
Analyze customer behavior to answer questions like:
- Who are the highest-value customers?
- What patterns drive repeat purchases?
- Which segments are at risk of churn (if applicable)?
- How do sales/behavior trends change over time?

## Tech Stack
- **Python:** pandas, numpy, matplotlib/seaborn (add others you used)
- **SQL:** (MySQL/PostgreSQL/SQLite — specify)
- **Power BI:** Data modeling + interactive dashboards (DAX if used)

## Dataset
- **Source:** (add link/name)
- **Rows / Period:** (e.g., 500K transactions from 2019–2021)
- **Key fields:** (CustomerID, OrderID, Date, Quantity, UnitPrice, TotalAmount, Country, etc.)

> Note: If the dataset is not included in the repo, describe how to obtain it and where to place it locally.

## Workflow
1. **Data Cleaning**
   - handled missing values, duplicates, invalid records
   - standardized datatypes (dates, currency, categories)
2. **Exploratory Data Analysis (EDA)**
   - revenue trends, customer distribution, category/channel breakdown
3. **SQL Analysis**
   - KPI queries (Revenue, AOV, Repeat Rate, Cohorts/Retention, etc.)
4. **Customer Metrics**
   - Recency, Frequency, Monetary (RFM) features (if used)
   - segmentation / clustering (if used)
5. **Power BI Dashboard**
   - model relationships
   - KPI cards + trend visuals + slicers for segment/time/category

## Key KPIs (examples)
- Total Revenue
- Total Customers
- Average Order Value (AOV)
- Repeat Purchase Rate
- Customer Lifetime Value (if calculated)
- RFM Segment distribution (if used)

## Dashboard (Power BI)
Describe the pages/visuals in your report, for example:
- Executive Summary (KPIs + trend)
- Customer Segmentation
- Product/Category Performance
- Retention / Cohort Analysis (if applicable)

**File:** `PowerBI/<your-file>.pbix` (update path)

## Results / Insights
Add 3–6 quantified insights. Example format:
- **Top X% customers contribute Y% of revenue**
- **Repeat customers spend Z% more than one-time customers**
- **Sales peak during ___ (month/day)**
- **Segment A shows highest AOV but low frequency** (etc.)

## Repository Structure
```text
.
├── README.md
├── data/               # raw/processed data (if included)
├── notebooks/          # Jupyter notebooks
├── sql/                # SQL queries
├── powerbi/            # Power BI report(s)
└── reports/            # exports, images, summary docs
