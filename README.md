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
# 🧊 Slooze Inventory Optimization & Sales Analytics Challenge

## 🔍 Project Overview

This project presents a complete analytics solution for the **Slooze Data Science & Analytics Take-Home Challenge**, focusing on inventory control, purchase optimization, and sales insights using **Snowflake Cloud Data Warehouse**.

All analysis was conducted using **Snowflake SQL**, and visualizations were built with **Snowsight Dashboards** for live interaction.

---

## ✅ Access Credentials (Snowflake Reader Account)

You can view **all queries, tables, and dashboards** using the provided Reader Account below:

- 🔐 **Login URL**: [https://nniisdz-slooze_reader_admin.snowflakecomputing.com](https://nniisdz-slooze_reader_admin.snowflakecomputing.com)
- 👤 **Username**: `slooze_reader_admin`
- 🔑 **Password**: `StrongPassword123`

> _Please use the Snowsight interface for easiest navigation and dashboard access._

---

## 🧊 Snowflake Details

- 📚 **Database**: `SLOOZE_DB`
- 📁 **Schema**: `SLOOZE_SCHEMA`
- ⚙️ **Warehouse**: `COMPUTE_WH`
- 📄 **All analysis done via SQL views and shared dashboards.**

---

## 📊 Dashboards (Click to View)

| Step | Dashboard | Link |
|------|-----------|------|
| 1️⃣ | **Demand Forecasting** | [View Dashboard](https://app.snowflake.com/nniisdz/fv95175/#/demand-forecast-dashboard-dNLS8M6ov) |
| 2️⃣ | **ABC Analysis** | [View Dashboard](https://app.snowflake.com/nniisdz/fv95175/#/abc-analysis-dashboard-dOzgVUcei) |
| 3️⃣ | **EOQ Analysis** | [View Dashboard](https://app.snowflake.com/nniisdz/fv95175/#/eoq-analysis-dashboard-dDPjYtaRC) |
| 4️⃣ | **High Margin Products** | [View Dashboard](https://app.snowflake.com/nniisdz/fv95175/#/high-margin-products-dashboard-dDfZFvh8I) |
| 5️⃣ | **Lead Time Analysis** | [View Dashboard](https://app.snowflake.com/nniisdz/fv95175/#/lead-time-analysis-dashboard-dBpfVmSuy) |
| 6️⃣ | **Monthly Sales - Top Brands** | [View Dashboard](https://app.snowflake.com/nniisdz/fv95175/#/monthly-sales-top-brands-dashboard-dY76haIGY) |

---

## 📂 Views Available

All analysis steps were implemented as **Snowflake SQL Views**:

- `DEMAND_FORECAST_VIEW`
- `ABC_ANALYSIS_VIEW`
- `VW_EOQ_ANALYSIS`
- `VW_REORDER_POINT_ANALYSIS`
- `VW_HIGH_MARGIN_PRODUCTS`
- `VW_LEAD_TIME_ANALYSIS`
- `VW_VENDOR_EFFICIENCY_SCORE`
- `VW_MONTHLY_SALES_TOP_BRANDS`

You can `SELECT * FROM <view_name>` to inspect each model.

---

## 🚀 How to Explore

1. Log in using the credentials above.
2. Navigate to the `SLOOZE_DB` → `SLOOZE_SCHEMA`.
3. Use the **Dashboards** tab in Snowsight to access each visual analysis.
4. Use the **SQL Editor** to explore the source tables or views.

---

## 📬 Submission Contact

Please reach out for any questions:

📧  purugulaudayabhavani@gmail.com 
🔗 [LinkedIn](https://www.linkedin.com/in/udaya-bhavani-p-1a6151281)

---

## 💡 Bonus

All transformations are done in Snowflake using scalable SQL.  
This approach is cloud-native, performant, and ideal for real-time analytics!

---


