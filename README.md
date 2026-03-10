# 📊 Retail Sales Dashboard — Excel & Interactive Web

> **A comprehensive 3-year (2022–2024) Retail Sales Analytics Dashboard built in Microsoft Excel with an interactive HTML/JS version.**

---

## 🖼️ Dashboard Preview

![Retail Sales Dashboard](dashboard_preview.png)

> *Excel Dashboard with slicers for Region, Channel, Year & Pack Type | Dark theme with pivot-driven charts*

---

## 📁 Project Overview

This project analyzes **190,000+ sales transactions** from a retail FMCG business spanning **2022 to 2024**, covering categories like Yogurt, Milk, ReadyMeal, SnackBar, and Juice across multiple brands, regions, and channels.

The dashboard was built entirely in **Microsoft Excel** using:
- Pivot Tables & Pivot Charts
- Slicers (Region, Channel, Year, Pack Type)
- Conditional Formatting
- Custom dark theme design

An **interactive HTML version** was also built using **Chart.js** for web deployment.

---

## 📌 Key Metrics Tracked

| Metric | Value |
|---|---|
| 💰 Total Revenue | ₹44,13,495 |
| 📦 Total Units Sold | 8,41,569 |
| 🚚 Delivered Quantity | 76,13,956 |
| 🏪 Stock Available | 66,97,576 |
| 📅 Data Range | Jan 2022 – Dec 2024 |
| 🔢 Total Records | 1,90,757 rows |

---

## 📊 Dashboard Sections

### 1. 🗓️ Month-on-Month Trend
- Revenue & Units Sold trend across all 12 months
- Peak month: **July** (₹4,57,613)
- Line + Bar combo chart

### 2. 📅 Yearly Performance
- Year-wise comparison: 2022, 2023, 2024
- Revenue, Units, Delivered Qty, Stock Available

### 3. 🛍️ Category Level Analysis
- 5 categories: Yogurt, Milk, ReadyMeal, SnackBar, Juice
- **Yogurt** is the top revenue generator (₹18.2L)

### 4. 🏷️ Brand Level Revenue & Units
- 14 brands analyzed
- Bar chart with dual axis (Revenue + Units)

### 5. 🗺️ Contribution of Revenue by Region
- 3 regions: PL-North, PL-Central, PL-South
- Near-equal split (~33% each) — balanced regional distribution

### 6. 📡 Revenue Share by Channel
- Channel-wise revenue breakdown
- Discount vs E-commerce vs Retail

### 7. 🎯 Promotion vs Non-Promotion Analysis
- Monthly comparison of promotional vs regular sales
- Promo revenue share: **~24.6%** of total

### 8. 🔑 Slicers / Filters
- **Region**: PL-Central | PL-North | PL-South
- **Channel**: Discount | E-commerce | Retail
- **Year**: 2022 | 2023 | 2024
- **Pack Type**: Carton | Multipack | Single

---

## 🗂️ Dataset Columns

```
date | sku | brand | segment | category | channel | region |
pack_type | price_unit | promotion_flag | delivery_days |
stock_available | delivered_qty | units_sold | Year | Month |
Month_name | revenue
```

---

## 🛠️ Tools & Technologies

| Tool | Usage |
|---|---|
| Microsoft Excel | Main dashboard, Pivot Tables, Charts, Slicers |
| HTML + CSS + JavaScript | Interactive web version |
| Chart.js | Web charts (Bar, Line, Doughnut, Pie) |
| Python (pandas, openpyxl) | Data preprocessing & validation |

---

## 📂 File Structure

```
📦 Retail-Sales-Dashboard
├── 📊 Sales_Dataset.xlsx          # Excel dashboard (main file)
├── 📄 Sales_Dashboard.html        # Interactive web version
├── 📄 README.md                   # Project documentation
└── 📁 screenshots/
    ├── dashboard_top.png
    └── dashboard_bottom.png
```

---

## 🔍 Key Insights

- 📈 **2023 was the best year** with ₹18.8L revenue — a **169% jump** from 2022
- 🥛 **Yogurt dominates** category mix at 41% of total revenue
- 🌍 **All 3 regions perform equally** — no regional dependency (healthy distribution)
- 🎯 **Promotional campaigns contribute ~25%** of revenue, showing good ROI on promotions
- 📅 **Q2 & Q3 (Apr–Aug) are peak seasons** — ideal for stocking and campaign planning
- 🏷️ **MiBrand3 and YoBrand4** are top revenue-driving brands

---

## 🚀 How to Use

### Excel Version
1. Download `Sales_Dataset.xlsx`
2. Open in Microsoft Excel (2016 or later recommended)
3. Use the **slicers** on the dashboard to filter by Region, Channel, Year, Pack Type
4. All charts update dynamically based on slicer selection

### Web Version
1. Download `Sales_Dashboard.html`
2. Open in any modern browser (Chrome, Firefox, Edge)
3. Fully interactive — hover over charts for tooltips

---

## 💡 Skills Demonstrated

`Data Analysis` `Excel Dashboarding` `Pivot Tables` `Data Visualization`
`Business Intelligence` `FMCG Analytics` `HTML/CSS/JS` `Chart.js`
`Python` `pandas` `Retail Analytics` `KPI Tracking`

---

## 👨‍💻 About This Project

This dashboard was created as part of a **retail sales analytics project** to demonstrate end-to-end data analysis skills — from raw transactional data (190K+ rows) to an executive-level interactive dashboard.

The goal was to provide actionable insights for:
- 📦 Inventory planning
- 🎯 Promotional strategy
- 🌍 Regional performance tracking
- 📅 Seasonal demand forecasting

---

## 📬 Connect With Me

If you found this project useful or have feedback, feel free to connect!

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat&logo=linkedin)](https://linkedin.com/in/YOUR-PROFILE)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-black?style=flat&logo=github)](https://github.com/YOUR-USERNAME)

---

⭐ **If you found this helpful, please star this repository!**
