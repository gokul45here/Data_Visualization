# Data-Analyst-Task-2: Superstore Sales Insights – 2025

## 📊 Project Overview
This project involves conducting a sales performance analysis using a Superstore sales dataset (or equivalent) to create a comprehensive dashboard in Power BI. The goal is to provide actionable insights into regional performance, product categories, and sales trends.

## 🔑 Key Deliverables
* **Data Preparation:** Cleaning, transformation, and creation of new metrics (`Profit Margin`, `Year`, `Discount Percentage`).
* **Dashboard:** A visually cohesive dashboard featuring 6 key charts for sales storytelling.
* **Insights:** Specific text-based narratives below each visual, summarizing the key findings.

## 📈 Key Metrics & Calculations
* **Order Date:** Used to create trend analysis (`Year`, `Month/Year`).
* **Category:** Used `PRODUCTLINE` as a proxy.
* **Region:** Used `COUNTRY` as a proxy.
* **Profit (Assumption):** Calculated as `SALES * 0.20` (assuming a 20% Gross Profit Margin, as true profit/COGS data was missing).
* **Profit Margin:** Calculated as `Profit / Sales`.
* **Discount Percentage:** Calculated as `(MSRP - PRICEEACH) / MSRP`.

## 🖼️ Dashboard Visuals & Core Insights

| Visual | Proxy Field | Insight Example (As found in the analysis) |
| :--- | :--- | :--- |
| **Sales by Region** | COUNTRY | The **USA** dominates the market, contributing over 35% of total global sales. |
| **Sales & Profit by Category** | PRODUCTLINE | **Classic Cars** drive the majority of the business, accounting for 30% of total sales. |
| **Monthly Sales Trend** | ORDERDATE | Sales show high seasonality, peaking sharply in **Q4 (Oct/Nov)** each year. |
| **Customer Segment vs Profit** | DEALSIZE | The **Medium Deal Size** segment contributes the highest total profit. |
| **Top 10 Products by Sales** | PRODUCTCODE | The top 10 products account for 25% of all sales. |
| **Sales vs Discount** | DISCOUNT\_PERCENTAGE | High-discount orders contributed a higher *total* profit compared to low-discount orders, driven by volume. |

## 🛠️ Tools Used
* **Data Analysis:** Python (Pandas) for initial cleaning and DAX (Power BI) for metric creation.
* **Visualization:** Power BI Desktop.
* **Repository:** GitHub.
