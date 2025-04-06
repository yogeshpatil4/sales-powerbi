# 📊 Sales Performance & Customer Insights Dashboard

## 📜Contents
1. [Project Overview](#-project-overview)
2. [Objective](#-objective)
3. [Dataset Description](#-dataset-description)
4. [Data Cleaning & Transformations](#-data-cleaning--transformations)
5. [Key Insights](#-key-insights)
6. [Challenges & Learning](#-challenges--learning)
7. [Dashboard Screenshots](#-dashboard-screenshots)
8. [Conclusion](#-conclusion)

## 📌 Project Overview
This Power BI project analyzes sales performance and customer behavior using a structured dataset. The dashboards provide key insights into revenue, product performance, and customer trends to help businesses make data-driven decisions.

## 🎯 Objective
The primary objectives of this project are:
- To analyze **sales performance** across different products, states, and time periods.
- To segment **customers** based on age groups, purchasing patterns, and geography.
- To track **revenue trends**, monthly differences, and MoM growth.
- To improve **business decision-making** by providing clear, interactive insights.

## 📂 Dataset Description
The project uses three main datasets:
- **Customer Data (`customer_dim.csv`)** – Contains customer demographics, segments, and purchase history.
- **Product Data (`product_dim.csv`)** – Includes product details, with duplicate and invalid price data removed.
- **Sales Transactions (`sales_transactions.csv`)** – Sales records with a newly added `revenue` column for analysis.

## 🛠 Data Cleaning & Transformations
- **Customer Table:** Added `city`, `state`, `age group`, `customer segment`, and `customer quantity segment`.
- **Product Table:** Removed duplicate products and invalid price entries.
- **Sales Transactions Table:** Added `revenue` column.
- **Date Table:** Created a separate date table for time-based analysis.
- **Dashboard Enhancements:** Included total sales, total quantity sold, and total orders, along with their monthly differences and Month-over-Month (MoM) growth.

## 📊 Key Insights
### Sales Performance Dashboard
- **Total Revenue:** $32.06M
- **Top 5 Products by Revenue:** MacBook Pro, iPhone, ThinkPad Laptop, Google Phone, 34-inch Ultrawide Monitor
- **Revenue Trends:** Highest in December ($4.29M), lowest in January ($1.69M)
- **Top States by Revenue:** California ($12.74M), New York ($4.34M), Texas ($4.27M)
- **MoM Growth Analysis:** Revenue saw a peak increase of **15% in December**, while the largest decline was **10% in February**.

### Customer Insights Dashboard
- **Total Customers:** 141K
- **Repeat Customers:** 22%
- **Customer Segmentation:** Majority of customers belong to the **'High-Value'** and **'Frequent Buyers'** segments.
- **Age Group Analysis:** Highest spending comes from the **25-34** age group.
- **Average Revenue per Customer:** $228

## 🚧 Challenges & Learning
### Challenges Faced:
- Handling **duplicate and invalid** product prices.
- Ensuring **data accuracy** while creating new customer segments.
- Designing **efficient calculations** for MoM growth and revenue differences.

### Key Learnings:
- Effective **data transformation** techniques for Power BI.
- Importance of **data validation** to maintain report accuracy.
- Advanced **DAX formulas** for dynamic metrics and trend analysis.

## 📷 Dashboard Screenshots
### Sales Performance Dashboard
![Sales Performance Dashboard](https://github.com/yogeshpatil4/sales-powerbi/blob/main/images/Screenshot%202025-04-06%20090656.png)

### Customer Insights Dashboard
![Customer Insights Dashboard](https://github.com/yogeshpatil4/sales-powerbi/blob/main/images/Screenshot%202025-04-06%20090712.png)

## 🎯 Conclusion
This Power BI project provides a comprehensive analysis of sales performance and customer behavior. By leveraging interactive dashboards, businesses can gain valuable insights into revenue trends, customer demographics, and product performance. The project enhanced skills in data cleaning, segmentation, and advanced Power BI functionalities, making it a valuable learning experience.

---
✨ *Developed with Power BI by [Yogesh Patil]*
