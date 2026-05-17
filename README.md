# 🛒 RetailSense — Sales Intelligence & Analytics Dashboard

<div align="center">

![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Data Analytics](https://img.shields.io/badge/Data_Analytics-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen?style=for-the-badge)

**A full-scale retail sales intelligence project built entirely in Microsoft Excel**  
*Covering data analysis, interactive dashboards, statistical modelling, and business storytelling*

</div>

---

## 📌 Project Overview

**RetailSense** is a comprehensive Excel-based analytics project built on a dataset of **250 retail transactions** across **50 unique customers**, **5 regions**, and **3 product categories**.

The goal was to extract meaningful business intelligence using advanced Excel features — from formula-based analysis to interactive dashboards and statistical regression.

---

## 🗂️ Project Structure

```
RetailSense/
│
├── 📋 Raw Data          → Cleaned dataset with calculated columns
├── 🔬 Analysis          → 8 sections of formula-based analysis
├── 📊 Visualizations    → 3 standalone pivot charts
├── 🎛️ Dashboard         → Interactive pivot dashboard with slicers & KPIs
├── 🔀 What-If           → Scenario Manager + Goal Seek
├── 📉 Regression        → Linear Regression via ToolPak
├── 📝 Insights          → Final report with storytelling
└── 📋 Scenario Summary  → Auto-generated scenario summary table
```

---

## 🔄 Project Workflow

```
Raw Data (250 rows)
        │
        ▼
┌─────────────────┐
│  Data Cleaning  │  → Date formatting, Calculated columns
│  & Preparation  │     (Days as Customer, Transaction Age)
└────────┬────────┘
         │
         ▼
┌─────────────────┐
│    Analysis     │  → Date/Time, FILTER, SUMIF GroupBy,
│    (8 Sections) │     TEXT functions, Timestamp, Compare Lists
└────────┬────────┘
         │
    ┌────┴────┐
    ▼         ▼
┌────────┐  ┌──────────┐
│What-If │  │Regression│  → Scenario Manager, Goal Seek
│Analysis│  │ ToolPak  │     Linear Regression (R²=0.698)
└────┬───┘  └────┬─────┘
     │            │
     └─────┬──────┘
           ▼
┌─────────────────────┐
│  Visualizations     │  → Bar, Line, Pie Charts
│  & Dashboard        │     Slicers, Timeline, KPI Indicators
└──────────┬──────────┘
           │
           ▼
┌─────────────────────┐
│   Final Insights    │  → Business storytelling + recommendations
│   & Reporting       │
└─────────────────────┘
```

---

## ✨ Key Features

| Feature | Description | Status |
|--------|-------------|--------|
| 📅 Date & Time Functions | TODAY, NOW, DATEDIF, EOMONTH | ✅ |
| 🔍 FILTER Function | Multi-value dynamic filtering | ✅ |
| 👥 GroupBy Analysis | High-Value Customers via SUMIF | ✅ |
| 🔤 TEXT Functions | Abbreviations, Initials, Short Codes | ✅ |
| 🕐 Timestamp | Iterative calculation timestamp | ✅ |
| 📋 Compare Two Lists | COUNTIF-based list matching | ✅ |
| 🎯 Scenario Manager | Best / Base / Worst case projections | ✅ |
| 🎯 Goal Seek | Target revenue quantity analysis | ✅ |
| 📉 Linear Regression | Unit Price → Revenue (R²=0.698) | ✅ |
| 🎛️ Interactive Dashboard | Pivot Tables + Charts + Slicers | ✅ |
| ⏱️ Timeline Filter | Date-based pivot filtering | ✅ |
| 📊 KPI Indicators | 4 KPIs with conditional formatting | ✅ |
| 🎨 Icon Formatting | Arrow icons on value segments | ✅ |
| 📝 Final Report | 8 business insights with storytelling | ✅ |

---

## 📊 Dashboard

> **Interactive dashboard with slicers, timeline, KPI indicators and pivot charts**

![Dashboard](screenshots/dashboard.png)

- 🗺️ **Revenue by Region** — Horizontal bar chart comparing all 5 regions; East leads at ₹59,288.39
- 🥧 **Revenue by Category** — Pie chart showing Electronics at 75% of total revenue
- 🏆 **Top 10 Customers** — Ranked bar chart with Mark Carter at ₹15,659.65
- 📋 **KPI Indicators** — Total Revenue, AOV, Transactions, Unique Customers — all On Target
- ⏱️ **Timeline** — Month-level date filter covering Apr 2024 – Apr 2025
- 🔘 **Slicers** — Region, Customer Segment, Category

---

## 🔬 Analysis Sheet

> **8 clearly labeled sections covering all required Excel functions**

- **Date & Time Functions** — TODAY, NOW, DATEDIF, EOMONTH used to compute today's date, current time, days since first transaction (762), and last day of current month.

  ![Date Time](screenshots/date-time-functions.png)

- **Key Summary Metrics** — Total Revenue ₹2,29,192.47 · 251 Transactions · AOV ₹916.77 · 50 Unique Customers · Most sold product: Bookshelf.

  ![Key Metrics](screenshots/key-summary-metrics.png)

- **High Value Customers (GroupBy with SUMIF)** — SUMIF aggregation with icon conditional formatting (green/orange/red arrows) to classify customers as High Value or Regular.

  ![High Value](screenshots/high-value-customers.png)

- **FILTER Function** — Dynamic multi-column filter extracting all Premium segment customer transactions in real time.

  ![Filter Function](screenshots/filter-function-premium-customers.png)

- **Compare Two Lists** — COUNTIF-based matching of North region customers vs Premium customers, returning matched names or "No match".

  ![Compare Lists](screenshots/compare-two-lists.png)

- **TEXT Functions (Abbreviations)** — LEFT, MID, FIND, UPPER used to generate customer initials (e.g. P.B.) and 3-letter product short codes (e.g. MON, LAP, BOO).

  ![Text Functions](screenshots/text-functions-abbreviations.png)

- **Timestamp** — Auto-generated timestamp using iterative calculation to record when the sheet was last refreshed.

  ![Timestamp](screenshots/timestamp-generated.png)

---

## 📈 Visualizations

> **3 standalone pivot charts for data storytelling**

| Chart | Type | Insight |
|-------|------|---------|
| Revenue by Region | Bar Chart | East leads with ₹59,288.39 |
| Monthly Revenue Trend | Line Chart | Peak in Jan 2025 at ₹25,799.15 |
| Revenue by Category | Pie Chart | Electronics = 75% of revenue |

- **Revenue by Region** — East dominates at ₹59,288.39 (25.9%); South is lowest at ₹36,398.75 (15.9%).

  ![Revenue Region](screenshots/revenue-by-region-chart.png)

- **Monthly Revenue Trend** — Peaked in Jan 2025 at ₹25,799.15; notable dip in Nov 2024 at ₹12,309.44.

  ![Monthly Revenue](screenshots/monthly-revenue-trend.png)

- **Revenue by Category** — Electronics ₹1,71,756.05 (75%), Furniture ₹49,097.68 (21%), Appliances ₹8,338.74 (4%).

  ![Revenue Category](screenshots/revenue-by-category.png)

---

## 🔀 What-If Analysis

> **Scenario Manager + Goal Seek for business projections**

![What If](screenshots/what-if-analysis.png)
![Scenario Summary](screenshots/scenario-summary.png)

- **Scenario Manager Results:**

| Scenario | Unit Price | Quantity | Discount | Projected Revenue |
|----------|-----------|----------|----------|------------------|
| 🟢 Best Case | ₹1,100 | 20 | 10% | ₹19,800 |
| 🟡 Base Case | ₹899 | 10 | 10% | ₹8,091 |
| 🔴 Worst Case | ₹599 | 5 | 20% | ₹2,396 |

- **Goal Seek Result** — To achieve ₹50,000 revenue at ₹500 unit price with 10% discount → **1,112 units needed**.

---

## 📉 Linear Regression

> **Unit Price → Total Revenue | R² = 0.698**

![Regression](screenshots/linear-regression-output.png)

- **Regression Equation:** `Total Amount = -14.34 + (3.14 × Unit Price)`

| Metric | Value | Interpretation |
|--------|-------|---------------|
| Multiple R | 0.835 | Strong positive correlation |
| R Square | 0.698 | Unit Price explains 69.8% of revenue variation |
| Significance F | 2.03E-66 | Model is highly statistically significant |
| Coefficient | 3.14 | Every ₹1 increase in price → ₹3.14 more revenue |

---

## 🔍 Final Insights Report

> **Key business findings with storytelling**

![Insights](screenshots/final-insights-report.png)

- East region generates highest revenue at ₹59,288 — contributing 25.9% of total revenue
- Electronics is the top performing category with ₹1,71,756 revenue — 75% of total sales
- Mark Carter is the highest spending customer with ₹15,659 in total purchases
- Bookshelf is the most frequently purchased product across all transactions
- Average order value of ₹916.77 suggests customers prefer mid to high range products
- Regression analysis shows Unit Price explains 69.8% of revenue variation — strong predictor
- Premium segment customers account for majority of high value transactions
- Goal Seek analysis shows 1,112 units needed to achieve ₹50,000 revenue target

---

## 📂 Dataset Overview

| Column | Description |
|--------|-------------|
| Transaction_ID | Unique transaction identifier |
| Date | Transaction date |
| Customer_ID | Unique customer identifier |
| Customer_Name | Full name of customer |
| Product_ID | Unique product identifier |
| Product_Name | Name of product purchased |
| Category | Electronics / Furniture / Appliances |
| Quantity | Units purchased (1–5) |
| Unit_Price | Price per unit (₹59–₹899) |
| Payment_Method | Cash / Credit Card / Debit Card / PayPal |
| Region | Central / East / North / South / West |
| Customer_Segment | Basic / Standard / Premium |
| Customer_Since | Date customer first registered |
| Total_Amount | Total transaction value |

---

## 🛠️ Tools & Techniques Used

```
Microsoft Excel (Desktop + Online)
├── Formulas          → SUMIF, COUNTIF, INDEX/MATCH, FILTER, UNIQUE, DATEDIF
├── Text Functions    → LEFT, MID, FIND, UPPER
├── Data Analysis     → ToolPak (Linear Regression)
├── What-If Tools     → Scenario Manager, Goal Seek
├── Pivot Features    → PivotTables, PivotCharts, Slicers, Timeline
├── Formatting        → Conditional Formatting, Icon Sets, Number Formats
└── Charts            → Bar, Line, Pie with Data Labels
```

---

## 📁 Files in This Repository

| File | Description |
|------|-------------|
| `RetailSense_-_Sales_Intelligence___Analytics_Dashboard.xlsx` | Main project file with all sheets |
| `README.md` | This documentation file |
| `screenshots/` | All sheet screenshots |

---

## 👨‍💻 Author

**Harshal Vora**  
📧 Connect on [GitHub](https://github.com/HarshalVara86)

---

<div align="center">

⭐ **If you found this project useful, please star the repository!** ⭐

*Built with 💪 and a lot of Excel formulas*

</div>
