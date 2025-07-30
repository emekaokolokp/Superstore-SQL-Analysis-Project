# 🛒 Superstore Sales Insights using SQL
## 📊 Project Overview
This project analyzes sales data from a fictional Superstore using PostgreSQL. It demonstrates how SQL can be used to extract actionable business insights from raw transactional data.
The analysis covers overall performance, regional trends, customer segments, and top products, and is suitable for business intelligence or data analytics portfolios.
---
## 🎯 Project Goals
- Analyze total sales and profit across all transactions
- Identify top-performing products and customer segments
- Track monthly sales trends for seasonality and forecasting
- Compare performance across different regions
- Practice real-world SQL skills and build a job-ready GitHub portfolio
---
## 🛠️ Tools Used
| Tool            | Purpose                                |
|-----------------|----------------------------------------|
| **PostgreSQL**  | SQL database for data storage & queries|
| **pgAdmin 4**   | GUI for PostgreSQL                     |
| **CSV**         | For importing/exporting data           |
---
## 🔍 Key Insights Extracted
- 💰 **Total Sales & Profit**: Summarized revenue and profit across all orders
- 🌍 **Regional Analysis**: Identified the most profitable and high-revenue regions
- 🏆 **Top Products**: Ranked top 10 products by total profit
- 📆 **Monthly Trends**: Revealed seasonal fluctuations in sales
- 👥 **Customer Segments**: Compared sales and customer counts across segments
- ✅ **Clean Data Workflow**: Raw CSV cleaned and imported into PostgreSQL
  ---
## ## 📊 Data Analysis Summary

The analysis was conducted using **SQL** (PostgreSQL) to explore patterns in sales, profit, customers, and product performance. Here are the main findings:

### 🔹 1. Total Sales & Profit
- **Total Sales:** \$26,020+  
- **Total Profit:** \$253.31  
- Indicates slim margins overall — this could point to discounts, high costs, or underperforming products.

🔍 **Business Insight:**  
Management needs to investigate pricing strategy and profit drivers to ensure sustainability.

---

### 🔹 2. Regional Sales Performance
- **Highest Sales:** West and East regions  
- **Lowest Sales:** Central and South regions  
- West and East also show higher profits

🔍 **Business Insight:**  
Marketing and logistics could be strengthened in underperforming regions to balance growth.

---

### 🔹 3. Top Products by Profit
- **Most profitable products** include multiple Xerox printer models
- Some top-selling products actually showed **negative or low profit**

🔍 **Business Insight:**  
Not all popular products are profitable — margin review and supply chain optimization are needed.

---

### 🔹 4. Monthly Sales Trend
- **Sales peak** in June and December, dip in February and April  
- Seasonal behavior indicates opportunities for timed promotions or inventory planning

🔍 **Business Insight:**  
Plan promotions and staffing around seasonal sales spikes to maximize ROI.

---

### 🔹 5. Customer Segment Analysis
- **Consumer** segment accounts for **83% of sales**  
- **Corporate and Home Office** segments are under-leveraged

🔍 **Business Insight:**  
A targeted B2B marketing strategy could unlock growth in Corporate and Home Office segments.

---

## 🎯 How This Helps the Company

By combining SQL data extraction with Power BI visuals, the company can:

- Identify top-performing regions and products
- Track seasonal trends to optimize inventory and staffing
- Focus marketing efforts on high-potential customer segments
- Improve profit margins by evaluating unprofitable items
- Develop a data-driven strategy for growth across markets

This dashboard provides a foundation for smarter decision-making across marketing, sales, and operations.

---
## 🗂️ Project Structure
superstore-sales-insights/
├── data/
  └── superstore_clean.csv
├── queries/
  └── superstore_sales.sql
├── results/
 ├── total_sales_profit.csv
 ├── top_products.csv
 ├── monthly_sales_trend.csv
 └── customer_segment_analysis.csv
├── README.md
