# 📱 Mobile Retail Sales Analytics Dashboard

A 3-page **Power BI dashboard** analyzing mobile phone retail sales across cities, brands, payment methods, and time — covering 3,800+ transactions from 2021 to 2024.

## 🚀 Overview

This project turns raw mobile-phone sales transaction data into an interactive Power BI dashboard covering three linked views — **Overview**, **MTD/QTD/YTD Report**, and **Same Period Last Year** — so a retail business can track sales performance city-by-city, model-by-model, and year-over-year, all from one report.

## 🧩 Data Source

| File | Description |
|---|---|
| `Mobile_Sales_Raw_Data.xlsx` | 3,835 transaction records — Transaction ID, Date, Brand, Mobile Model, Units Sold, Price Per Unit, Customer Name/Age, City, Payment Method, Customer Ratings |
| `Mobile_Retail_Sales_Analytics_Dashboard.pbix` | The Power BI dashboard file built on top of the raw data |

**Coverage:** 19 cities across India · 5 brands (Apple, Samsung, OnePlus, Vivo, Xiaomi) · 15 mobile models · 4 payment methods (UPI, Debit Card, Credit Card, Cash) · October 2021 – 2024

## 📌 Key Metrics

- 💰 **Total Sales:** 769M (₹76.92 Cr)
- 📦 **Total Quantity Sold:** 19K units
- 🧾 **Total Transactions:** 4K
- 💵 **Average Price per Unit:** ₹40.11K

## 🖥️ Dashboard Pages

### 1. Overview
KPI cards (Total Sales, Quantity, Transactions, Avg Price), month slicer panel, Total Sales by City (bar chart), Total Quantity by Month (trend line), geographic map of city-wise sales, Customer Ratings (Good/Average/Poor), Payment Transaction Method (pie chart), Total Sales by Day (weekly pattern), and Total Sales by Mobile Model.

### 2. MTD, QTD & YTD Report
Total Sales & QTD by Month, Total Sales & YTD by Year (2022-2024), and Total Sales & MTD by Day — all as dual-line trend charts comparing running totals against actual sales.

### 3. Same Period Last Year
Total Sales vs. Same Period Last Year broken down by Year, Month, Quarter, and Day — enabling direct year-over-year comparison at every time granularity.

All three pages share the same **Mobile Model, Payment Method, and Date** filters at the top.

## 🔍 Key Insights

- **Delhi and Mumbai dominate sales**, together contributing over 40% of total revenue, while the remaining 17 cities each contribute under 5%.
- **All 5 brands are almost evenly matched** — the gap between the top brand (Apple) and the bottom (Xiaomi) is just ~11%, showing no single brand dominates the market.
- **Payment method usage is nearly identical across all four options** (UPI, Debit, Credit, Cash), each holding roughly a 24-26% share — customers show no strong channel preference.
- **Saturday is the strongest sales day and Wednesday the weakest**, a consistent ~10% gap useful for staffing or promotional timing.
- **2022 was the peak year**, with 2023 close behind; 2024 shows a noticeable decline worth investigating against business context.
- **61% of units sold carry a "Good" (4-5 star) customer rating**, but nearly 1 in 5 units are tied to a "Poor" rating — a gap worth digging into by model or city.

## 🛠️ Tools & Techniques Used

- Power BI (data modeling, DAX measures for MTD/QTD/YTD and Same-Period-Last-Year calculations)
- Geographic map visual (Bing Maps) for city-wise sales
- Dual-axis trend charts comparing running totals vs. period sales
- KPI cards, pie chart, bar charts, and rating-band visualization

## 📂 How to Use

1. Download `Mobile_Retail_Sales_Analytics_Dashboard.pbix` along with `Mobile_Sales_Raw_Data.xlsx`
2. Open the `.pbix` file in Power BI Desktop
3. Use the **Mobile Model, Payment Method, and Date** filters, or the month buttons on the left, to slice the data
4. Switch between the **Overview**, **MTD/QTD/YTD Report**, and **Same Period Last Year** tabs for different views

## 🎯 What I Learned / Practiced

- Building time-intelligence DAX measures (MTD, QTD, YTD, Same Period Last Year)
- Designing a multi-page retail dashboard with consistent cross-page filters
- Using geographic visuals to surface city-level concentration risk
- Turning transaction-level data into brand, payment, and rating-based business insights

## 📬 Connect

If you found this useful, feel free to connect or drop feedback!

---
⭐ If you like this project, don't forget to star/share it!
