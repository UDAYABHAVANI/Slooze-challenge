# Slooze-challenge
# Slooze Take-Home Challenge – Inventory, Purchase & Sales Optimization

## 🔍 Project Overview

This repository contains my submission for the Slooze Data Science & Analytics take-home challenge. The challenge revolves around analyzing inventory, purchase, and sales data to derive insights and optimize processes using Snowflake.

All data processing and analysis were performed using **Snowflake SQL**, leveraging Snowflake’s compute power, scalability, and analytical functions to explore the data and deliver insights across six key objectives.

---

## 🎯 Objectives Implemented

### ✅ 1. Demand Forecasting
- Used historical sales data from the `SALES` table.
- Created a view to aggregate and forecast monthly product demand using time-based patterns.

### ✅ 2. ABC Analysis
- Categorized inventory based on sales revenue using Pareto (80/20) logic.
- Classified into A (high-value), B (moderate), C (low-value) segments.

### ✅ 3. EOQ (Economic Order Quantity)
- Estimated ideal order quantities using sales volume, price, and ordering assumptions.
- Helps reduce total ordering and holding costs.

### ✅ 4. Reorder Point Analysis
- Calculated reorder thresholds using lead time and daily demand.
- Aimed at preventing stockouts and ensuring continuity.

### ✅ 5. Lead Time Analysis
- Measured average supplier lead times using purchase order and receiving dates.
- Supports procurement efficiency.

### ✅ 6. Additional Insights
- Identified top-performing vendors and stores.
- Analyzed seasonal and volume trends using date-based aggregations.

---

## 🗂️ Project Structure

snowflake/
├── README.md
├── setup_instructions.md
├── snowflake_queries/
│ ├── step1_demand_forecasting.sql
│ ├── step2_abc_analysis.sql
│ ├── step3_eoq_analysis.sql
│ ├── step4_reorder_point.sql
│ ├── step5_lead_time_analysis.sql
│ └── step6_additional_insights.sql
├── data_samples/
│ ├── sales_sample.csv
│ ├── purchases_sample.csv
│ └── inventory_sample.csv



---

## 🏗️ How to Run


