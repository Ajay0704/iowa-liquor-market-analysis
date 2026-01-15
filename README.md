# Iowa Liquor Market Behavior Analysis

This project analyzes real transaction data from the Iowa Liquor Sales dataset to understand how buying behavior changes across regions and over time. Instead of focusing on simple “top sellers,” the analysis uses SQL to surface non-obvious patterns in volume and category mix across counties and stores.

Because liquor prices in Iowa are state-controlled, margin differences are minimal. The real signal lies in **what people buy and where**. This project focuses on:

- Market growth and seasonality over time  
- Category mix by county and how it shifts year to year  
- Differences between urban and rural buying behavior  
- Store performance compared to peers in the same county  

## Data
- Source: Iowa Liquor Sales (public dataset)
- Size: Millions of transaction rows
- Fields include: date, store, county, category, item, bottles sold, sales dollars

## What Was Built
- A clean analytics layer in SQLite (`v_sales`, `v_sales_margin`)
- Business-focused SQL queries to:
  - Track monthly and yearly sales trends
  - Measure category share by county and year
  - Compare stores against local peers
  - Identify regional demand patterns and mix shifts

## Key Questions Answered
- Is the market growing or slowing over time?
- How does category preference differ by region?
- Which categories are gaining or losing share?
- Which stores underperform compared to others in the same county?

## Repository Structure
- 01_data_prep.sql
- 02_sales_trends.sql
- 03_category_mix_by_county.sql
- 04_store_benchmark.sql
- 05_regional_behavior.sql


## Why It Matters
These insights mirror real internal analytics work used by retailers, distributors, and policy teams to:
- Plan inventory by region  
- Understand changing consumer behavior  
- Identify underperforming locations  
- Track market health over time  


