# Maison Lumière Global Skincare & Beauty E-Commerce Dashboard

> A 3-page Power BI dashboard suite that tracks sales performance, market efficiency, and product profitability across segments, regions, and product categories for a global skincare and beauty brand.

<img width="1791" height="1389" alt="Global Skincare and Beauty E-commerce Dashboard" src="https://github.com/user-attachments/assets/7e1273db-48f3-4358-8b28-3fc23ef4a011" />

---

## 📋 Table of Contents

- [Overview](#overview)
- [Dashboard Pages](#dashboard-pages)
  - [Sales & Profit Performance](#1-sales-&-profit-performance)
  - [Market Performance & Efficiency](#2-market-performance-&-efficiency)
  - [Product Performance & Profitability](#3-product-performance-&-profitability)
- [Key Metrics & KPIs](#key-metrics--kpis)
- [Relationship Model](#relationship-model)
- [Dataset Schema](#dataset-schema)
- [File Structure](#file-structure)
- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [Usage & Filters](#usage--filters)
- [Insights Summary](#insights-summary)

---

## Overview

The **Maison Lumière Global Skincare & Beauty E-Commerce Dashboard** is a Power BI report built to monitor sales performance, market efficiency, and product profitability for a global beauty e-commerce store. It equips sales managers, category analysts, regional leads, and marketing teams with the data needed to track revenue and profit trends, evaluate discount strategies, benchmark market and regional performance, and identify top-performing products all from a single dashboard.

### 🎯 Business Objectives

- Track total and segmented sales and profit performance against prior year (YoY)
- Identify which customer segments, markets, and regions generate the most revenue and profit
- Understand seasonal patterns in profit margin across months and years
- Analyse the impact of discounting on profit margin and net sales by product
- Monitor sales growth rate trends by market, region, and country
- Benchmark product-level performance across categories, margins, and discount exposure

---

## Dashboard Pages

### 1. Sales & Profit Performance

> *Tracks sales, profit, volume, and margin trends across segments and time periods.*

<img width="1368" height="867" alt="Sales   Profit Performance" src="https://github.com/user-attachments/assets/3a6bccc8-4b4e-4feb-a1ed-1329fac0038f" />

#### KPI Cards

| KPI | Value |
|-----|-------|
| **Total Sales** | $6,517,674 |
| **Sales Volume** | 277,778 |
| **Total Profit** | $1,065,414 |
| **Profit Margin %** | 16.35% |

#### Visuals

**Total Sales and Total Profit by Year : Combo Chart** *(Drill down to quarter and month)*
- Revenue bars overlaid with a Total Profit trend line, with YoY % change labels on each bar
- Tracks business growth trajectory across 2020–2023
- Sales grew consistently YoY: 2020 (▲14.9%), 2021 (▲16.3%), 2022 (▲3.3% / 0.7%), 2023 (▲3.0%)
- 2023 shows the largest total profit bar with a -1.8% dip, signalling margin compression at peak revenue

**Seasonal Profit Margin % : Heatmap Matrix**
- Monthly profit margin % displayed by year (2020–2023) across all 12 months
- Darker cells highlight peak margin months; supports identifying seasonal profitability patterns
- 2020 shows higher margins early in the year; margins trend lower in 2023 across most months

**Total Sales by Segment : Donut Chart + Table**
- Corporate leads with $3.84M, followed by Consumer ($2.15M) and Self-Employed ($0.53M)
- YoY growth: Corporate ▲50.83%, Consumer ▲49.35%, Self-Employed ▲55.35%

**Total Profit by Segment : Donut Chart + Table**
- Corporate leads profit at $608.52K (▲36.16% YoY)
- Consumer generates $365.38K (▲33.94% YoY); Self-Employed at $91.51K (▲39.12% YoY)

**Profit Margin % by Segment : Donut Chart + Table**
- Self-Employed holds the highest margin at 17.26% (▼10.44% YoY)
- Consumer follows at 17.02% (▼10.32% YoY); Corporate at 15.84% (▼9.73% YoY)
- All three segments show declining margins YoY, despite growing revenue

---

### 2. Market Performance & Efficiency

> *Analyses sales, profit, and efficiency trends by market, region, and country.*

<img width="1368" height="867" alt="Market Performance   Efficiency Dashboard" src="https://github.com/user-attachments/assets/f13c6373-b350-4f88-9d13-2332a3d0e6e7" />

#### KPI Cards

| KPI | Value | Detail |
|-----|-------|--------|
| **Primary Sales Driver** | Asia Pacific | 28.1% \| $1,830,674 |
| **Primary Volume Driver** | Asia Pacific | 27.9% \| 77,582 units |
| **Primary Profit Driver** | Europe | 31.1% \| $331,322 |
| **Highest Margin Market** | Europe | 22.3% \| $331,322 |

> **Sub-cards** surface the leading segment and product within each KPI (e.g. Corporate driving 17.0% of Asia Pacific sales; Herbal Essences Bio driving 0.2% of Asia Pacific volume).

#### Visuals

**Total Sales and Total Profit by Market : Combo Chart** *(Drill down to region and country)*
- Asia Pacific leads total sales at $1.83M with $229K total profit
- Europe follows at $1.48M / $331K highest profit despite lower sales than Asia Pacific
- Africa is the smallest market at $0.49M / $66K in profit
- Drill-down exposes region and country level contribution within each market

**Monthly & Yearly Sales Growth Trends : Heatmap Matrix**
- Year × Month grid showing sales growth % per cell
- 2021 shows the strongest growth year with consistent positive values across months
- 2023 growth decelerates significantly, with many months in the single digits or negative

**Regional Performance Table**
- Ranks all regions by Total Sales, Total Sales YoY %, Total Profit, Total Profit YoY %, Profit Margin %, and Profit Margin YoY %
- Southern US leads at $1,326,577 (▲47.85% YoY), with Profit Margin of 15.67% (▼7.29% YoY)
- Western Europe follows at $762,855 (▲54.22% YoY), with the highest regional profit of $171,513
- Southeastern Asia shows the weakest margin at 1.67% (▼62.13% YoY) despite ▲60.89% sales growth
- Western Asia is the only region with a negative profit: ($14,566.50)

**Sales Growth Rate % by Market : Bar Chart** *(Drill down to region and country)*
- Europe leads growth at 57.70%, followed by Africa (50.63%), Asia Pacific (49.50%), USCA (48.01%), and LATAM (48.01%)
- Drill-down enables country-level growth benchmarking within each market

---

### 3. Product Performance & Profitability

> *Analyses sales, profit, discounts, and margins to identify top-performing products.*

<img width="1367" height="866" alt="Product Performance   Profitability Dashboard" src="https://github.com/user-attachments/assets/8051017e-39bc-4cef-bbfb-74597b7e520c" />

#### KPI Cards

| KPI | Value | Detail |
|-----|-------|--------|
| **Primary Sales Driver** | Herbal Essences Bio | 1.0% \| $67,640 |
| **Primary Volume Driver** | Herbal Essences Bio | 0.6% \| 1,780 Units |
| **Primary Profit Driver** | Herbal Essences Bio | 0.9% \| $9,090 |
| **Highest Margin Product** | Aveda Stress-Fix Bath Soak | 50.0% \| $26 |

> **Sub-cards** surface the top segment and market within each KPI (e.g. Corporate driving 58.5% of Herbal Essences Bio sales; Europe driving 26.3%).

#### Visuals

**Profit Decomposition Tree : Hierarchy Visual**
- Breaks total profit of $1,065,413.65 down by Category → Product → Market → Region → Country → Segment
- Body Care leads at $1,046,285.70, with Hair Care ($7,518.19), Face Care ($7,282.95), Home & Accessories ($2,772.86), and Make Up ($1,553.96) trailing significantly
- Herbal Essences Bio is the top product at $9,089.68 in profit

**Net Sales by Product : Bar Chart**
- Herbal Essences Bio dominates at $56K net sales
- Rose Gold Petal Studs ($26K), Sterling Wave Earrings ($25K), Golden Blaze Necklace ($25K), and Gold Spectrum Anklet ($24K) follow

| Metric | Value |
|--------|-------|
| **Net Sales** | $5.57M |
| **Discount Rate** | 14.62% |
| **Discount Amount** | $952.59K |

**Product Performance Table**
- Ranks products within each category by Total Sales, Total Sales YoY %, Total Profit, Total Profit YoY %, Profit Margin %, and Profit Margin YoY %
- Herbal Essences Bio: $67,640 (▲69.85%), Profit Margin 13.44% (▼6.28%)
- Gold Spectrum Anklet: $27,004, Profit Margin 22.01% (▲8.72% YoY)
- Sterling Frost Ring: $26,772, Total Profit -$539.32 (▼150.55%) — the only product with negative profit

**Discount Amount vs Profit Margin % : Scatter Chart**
- x-axis: Discount Amount per product; y-axis: Profit Margin %
- Products clustered at high discount amounts tend to show lower or negative margins
- Herbal Essences Bio and Sterling Wave Earrings appear at upper-right: high sales and moderate discount exposure
- Several products (e.g. Bvlgari Acqua Di Gio, Maybelline Color Tattoo) sit at extreme negative margins with high discount amounts, flagging profitability risk

---

## Key Metrics & KPIs

| KPI | Definition |
|-----|-----------|
| **Total Sales** | Gross revenue across all orders and segments in the selected period |
| **Sales Volume** | Total units sold across all orders |
| **Total Profit** | Net profit after cost of goods across all orders |
| **Profit Margin %** | Total Profit ÷ Total Sales, expressed as a percentage |
| **Net Sales** | Total revenue after returns, discounts, and allowances |
| **Discount Rate** | Mean discount rate applied across all discounted orders |
| **Discount Amount** | Total dollar value of discounts applied across all orders |
| **Total Sales YoY %** | Current year total sales vs. prior year total sales |
| **Total Profit YoY %** | Current year total profit vs. prior year total profit |
| **Profit Margin YoY %** | Change in profit margin % vs. the same period in the prior year |
| **Sales Growth Rate %** | Period-over-period sales growth expressed as a percentage |
| **Primary Sales Driver** | Market, region, or product contributing the highest share of total sales |
| **Primary Profit Driver** | Market, region, or product contributing the highest share of total profit |
| **Highest Margin Market / Product** | The market or product with the highest profit margin % |

---

## Relationship Model

| From (FK) | To (PK) | Join Column |
|-----------|---------|-------------|
| FactSales.CustomerID | DimCustomers.CustomerID | CustomerID |
| FactSales.ProductID | DimProducts.ProductID | ProductID |
| FactSales.Country | DimGeographt.Country | Country |
| FactSales.OrderDate | DimDate.Date | Date |

---

## Dataset Schema

| Column | Type | Description |
|--------|------|-------------|
| `OrderID` | Integer | Unique identifier for each order |
| `OrderDate` | Date | Date the order was placed |
| `CustomerID` | String (FK) | References Customers table |
| `ProductID` | Integer (FK) | References Products table |
| `CountryID` | Integer (FK) | References Countries table |
| `UnitPrice` | Decimal | Unit price at time of order |
| `Quantity` | Integer | Number of units ordered |
| `Discount` | Decimal | Discount applied (0.0 – 1.0 scale) |
| `TotalSales` | Decimal *(Calculated)* | Gross revenue for the order line |
| `TotalProfit` | Decimal *(Calculated)* | Revenue minus cost for the order line |
| `NetSales` | Decimal *(Calculated)* | Total Sales after discounts, returns, and allowances |
| `ProfitMargin %` | Decimal *(Calculated)* | Total Profit ÷ Total Sales |
| `DiscountAmount` | Decimal *(Calculated)* | UnitPrice × Quantity × Discount rate |
| `Category` | String | Product category (Body Care, Hair Care, Face Care, etc.) |
| `Product` | String | Individual product name |
| `Market` | String | Market (Asia Pacific, Europe, USCA, LATAM, Africa) |
| `Region` | String | Region (e.g. Southern US, Western Europe) |
| `Country` | String | Country |
| `Segment` | String | Customer (Corporate, Consumer, Self-Employed) |
| `Year / Month / Quarter` | Integer / String | Date dimensions for time-intelligence DAX measures 

---

## File Structure

```
maison-lumiere-beauty-dashboard/
│
├── 📊 Global_Skincare_and_Beauty_E-commerce_Dashboard.pbix     # Main Power BI file
│
├── 📁 screenshots/
│   ├── Sales_and_Profit_Performance.png
│   ├── Market_Performance_and_Efficiency.png
│   └── Product_Performance_and_Profitability.png
│
├── 📂 data/
│   └── Global_Skincare_Beauty_Dataset.xlsx                     # Source data file
│
└── 📄 README.md                                                # This file
```

---

## Getting Started

### Prerequisites

| Tool | Version | Purpose |
|------|---------|---------|
| [Power BI Desktop](https://powerbi.microsoft.com/desktop/) | Latest | Open & edit `.pbix` |
| Microsoft Excel | 2016+ | View/edit source dataset (if applicable) |

### Installation & Setup

1. **Clone or download the repository**
   ```bash
   https://github.com/M1deTheAnalyst/Maison-Lumi-re-Global-Skincare-Beauty-E-Commerce-Dashboard.git
   ```

2. **Open the dashboard**
   - Launch **Power BI Desktop**
   - Go to `File → Open` and select `Global_Skincare_and_Beauty_E-commerce_Dashboard.pbix`

3. **Verify data source connection**
   - Navigate to `Home → Transform Data → Data Source Settings`
   - Update the path to your local source dataset if prompted
   - Click `Refresh` to load the latest data

4. **Refresh data**
   ```
   Home → Refresh
   ```

---

## Usage & Filters

The dashboard includes a slicer pane on all pages supporting the following filters:

- **Year** : Filter to a specific year range
- **Market / Region / Country** : Focus on a specific geographic market
- **Product / Category** : Isolate performance by category
- **Customer Segment** : Filter by Corporate, Consumer, or Self-Employed

### Navigation

Use the **left-hand page navigator** to switch between:
- `Sales & Profit Performance` : top-line revenue, profit, volume, and segment breakdown
- `Market Performance & Efficiency` : market, regional, and country-level sales and profit trends
- `Product Performance & Profitability` : product-level sales, margin, and discount analysis

Use the **RESET button** (top-right of each page) to clear all active slicer selections at once.
Use the **Filter icon** (top-right of each page) to open or collapse the slicer pane.

### Drill-Down Interactions

Several visuals support drill-down for deeper analysis:

| Visual | Primary Level | Drill-Down Level |
|--------|--------------|-----------------|
| Sales & Profit by Year | Year | Quarter → Month |
| Sales & Profit by Market | Market | Region → Country |
| Sales Growth Rate by Market | Market | Region → Country |
| Monthly Sales Growth Heatmap | Year | Month |
| Profit Decomposition Tree | Category | Product → Market → Region → Country → Segment |

> **Tip:** Click the drill-down arrow icon in the top-right corner of any visual to activate drill mode, then click a data point to go deeper. Use the **Up arrow** to return to the parent level.

---

## Insights Summary

1. **Revenue has grown consistently, but margins are under pressure** : Total sales of $6.52M reflect strong YoY growth across all three customer segments (Corporate ▲50.83%, Consumer ▲49.35%, Self-Employed ▲55.35%). However, all segments show declining profit margins YoY, with Corporate margin falling to 15.84% (▼9.73%). Growth is not translating into proportional profit improvement.

2. **Asia Pacific drives volume; Europe wins on profitability** : Asia Pacific is the largest market by sales ($1.83M) and volume (77,582 units), yet Europe generates a higher profit ($331K vs. $229K) and commands the highest margin at 22.3%. This suggests Asia Pacific may be over-discounting or serving lower-margin product mix relative to Europe.

3. **Herbal Essences Bio carries the product portfolio** : Across all three pages, Herbal Essences Bio is the top driver of sales, volume, and profit, yet its margin sits at only 13.44% (▼6.28% YoY). This heavy reliance on a single product with a declining and below-average margin represents a concentration and profitability risk.

4. **Discounting is eroding nearly $1M in potential revenue** : The total discount amount across all products is $952.59K against a 14.62% average discount rate. Products such as Bvlgari Acqua Di Gio and Maybelline Color Tattoo sit at deeply negative profit margins on the scatter chart, directly attributable to heavy discounting with insufficient volume uplift to compensate.

5. **Western Asia is the only unprofitable region** : Despite generating $275,454 in total sales (▲45.61% YoY), Western Asia records a negative total profit of -$14,566.50, with a profit margin of -5.29% and a staggering ▲247.40% profit YoY change driven by losses deepening, not improving. Immediate review of pricing, cost structure, or market exit should be considered.

6. **Southeastern Asia shows volume growth masking a margin collapse** : Despite leading all regions in sales growth at ▲60.89% YoY, Southeastern Asia's profit margin has collapsed to 1.67% a ▼62.13% YoY decline. High growth paired with near-zero margins signals unsustainable market penetration strategy likely driven by aggressive discounting.

7. **Sterling Frost Ring is the only product in active loss** : With a total profit of -$539.32 (▼150.55% YoY), this is the only product currently destroying value. Its profit margin of -2.01% combined with its downward trajectory warrants urgent pricing intervention or discontinuation review.

8. **Europe is the fastest-growing and most profitable market** : Europe leads all markets in both sales growth rate (57.70%) and profit generation ($331,322 at 22.3% margin). It represents the clearest opportunity for investment, account expansion, and premium product focus.

9. **Body Care dominates the category hierarchy but margin is thin** : Body Care accounts for virtually all recorded profit in the decomposition tree ($1,046,285.70 of $1,065,413.65 total). However, individual product margins within Body Care vary sharply from 50.0% (Aveda Stress-Fix Bath Soak) down to negative territory suggesting significant opportunity for mix optimisation within the category.

10. **Self-Employed segment holds the highest margin despite the smallest revenue share** : At 17.26% profit margin, Self-Employed outperforms both Corporate and Consumer segments, despite contributing only $530,187 in total sales. This segment may be underinvested relative to its margin quality and deserves targeted growth attention.

---

## Author

**M1deTheAnalyst**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/m1detheanalyst)
[![GitHub](https://img.shields.io/badge/GitHub-Profile-181717?style=for-the-badge&logo=github)](https://github.com/M1deTheAnalyst)
[![X](https://img.shields.io/badge/X-Folllow-000000?style=for-the-badge&logo=twitter&logoColor=white)](https://x.com/M1deTheAnalyst)

---

*Built with ❤️ using Power BI | Data-driven decisions for sales, operations, and category teams*
