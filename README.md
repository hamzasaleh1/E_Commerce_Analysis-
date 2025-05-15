# E_Commerce_Analysis-
🛒 E-Commerce Analysis Power BI Project


## 📊 Project Overview

This Power BI project presents a comprehensive analysis of an E-commerce dataset. The aim is to uncover actionable insights about customer behavior, sales performance, payment trends, and return patterns — with a strong focus on customer segmentation and churn analysis.

---

## 🎯 Project Goals

1. **Customer Segmentation & Churn**
   - Segment customers based on behavior (frequency, spend, recency).
   - Identify churn patterns and recommend strategies for retention.

2. **Product & Sales Analysis**
   - Highlight top and bottom-performing product categories.
   - Analyze sales trends, average transaction values, and return rates.

3. **Payment Method & Returns**
   - Analyze payment trends and their impact on return rates.
   - Suggest improvements to enhance customer satisfaction.

---

## 🔧 Tools & Techniques Used

- **Power BI**
- **DAX** (Measures & Calculated Columns)
- **Power Query** for data cleaning and shaping
- **Data Modeling** with star schema (Fact & Dimension tables)
- **RFM Segmentation** (Recency, Frequency, Monetary)
- **Time Intelligence** (YoY Growth, Trends, Forecasts)
- **KPI Metrics** (Churn Rate, Return Rate, Sales Trends)
- **Bookmarks & Interactive Navigation**
- **Custom Date Table**
- **Visual Filtering, Cross-Filtering & Slicers**

---

## 📁 Data Preparation Steps

- Merged data from multiple sources using Power Query.
- Cleaned and transformed the dataset (removed duplicates, detected outliers).
- Created relationships and normalized into **Fact and Dimension tables**.
- Built a custom **Date Table** for time intelligence.
- Created calculated columns and measures using **DAX**.
- Applied **RFM segmentation** for customer insights.

---

## 📌 Key Insights

### 👥 Customer Segmentation & Churn

- 🔴 **Low Spend + Low Frequency** customers have the **highest churn rate** at **20.94%**.
- 🟢 **High Spend + High Frequency** customers have the **lowest churn rate**.
- 🏆 **Champions (High F, High M, Low R)** are highly loyal and least likely to churn.
- 🆕 **New Customers** show the **highest churn**.
- 📅 **February** has the **highest churn (18.24%)**, mainly among **female customers**.
- 😠 A **positive correlation** between return rates and churn suggests dissatisfaction, especially among **younger age groups**.

### 📦 Product & Sales

- 👚 **Top Category:** Clothing ($52.9M), especially among females.
- 💳 **Top Combo:** Clothing + Credit Card = $39M.
- 💻 **Lowest Combo:** Electronics + Crypto.
- 📈 **Sales Peak:** August (~$35M).
- 📉 **Sales Drop:** November (~$25M).
- 🔁 **Return Rate:** Consistent across categories at ~40.45%.

### 💰 Payment Methods

- 💳 **Top Payment Method:** Credit Card ($140.8M).
- 🔄 **Highest Return Rate:** Credit Card among churned customers (42.59%).
- 💵 **Highest Return Combo:** Cash + Books (40.87%).
- 🪙 **Lowest Return Combo:** Crypto + Books (38.89%).
- 🏆 **Highest Transaction Year:** 2020 (50,339 transactions).
- 🪙 **Lowest Transaction Channel:** Crypto in 2023 (4,772 transactions).

---

## 📸 Dashboard Features

- **4 main pages + 1 Insights page** (with bookmarks for navigation).
- **Interactive filtering** across visuals using slicers and cross-filtering.
- **Responsive visuals** with page-level and report-level filters.
- **Forecasting** with time trend lines.
- **KPIs** like YoY growth, Churn Rate, Return Rate displayed clearly.

---



