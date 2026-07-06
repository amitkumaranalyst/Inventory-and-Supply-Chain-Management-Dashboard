# 📦 Inventory and Supply Chain Management Dashboard (Power BI)

An interactive Power BI dashboard analyzing inventory health, warehouse efficiency, transportation costs, and order fulfillment performance across regions and product categories.

![Dashboard Preview](Inventory_and_Supply_Chain_Dashboard.png)

## 📊 Project Overview

This dashboard was built to help supply chain and operations teams monitor key inventory KPIs, identify regional cost inefficiencies, and track order fulfillment health at a glance. It consolidates data across **4 regions** (North, South, East, West) and **4 product categories** (Accessories, Clothing, Electronics, Furniture).

## 🎯 Key Metrics Tracked

| Metric | Value | What It Means |
|---|---|---|
| Warehouse Utilization | 34.08% | Current warehouse capacity in use (gauge target: 75%) |
| Days Sales of Inventory (DSI) | 15.56 days | Avg. number of days inventory is held before sale |
| Inventory Turnover Ratio | 23.47 | How efficiently inventory is sold/replaced over a period |

## 🔍 Key Insights

- **Warehouse capacity is underutilized** — running at ~34% against a 75% target, suggesting room for consolidation or reduced storage overhead.
- **Order fulfillment is strong overall**: of all orders tracked, 838 were fulfilled vs. 248 pending and 114 canceled — a healthy fulfillment rate, though the pending bucket is worth monitoring.
- **Units sold grew sharply from 2020 to 2022** (54.9K → 191.8K) and have since plateaued (~195K-198K in 2023-2024), indicating the business may be entering a maturity phase after rapid growth.
- **Transportation costs are fairly evenly distributed** across regions, with the West region trending slightly higher across most categories.
- **Lead times are consistent across categories** (4-5K days aggregate), with Accessories showing the lowest cumulative lead time.
- **Inventory levels by category/region** show Electronics and Clothing carrying the highest stock volumes, useful for identifying potential overstock or understock risk by region.

## 🛠️ Tools & Techniques Used

- **Power BI Desktop** — data modeling, DAX measures, interactive visuals
- **Interactive slicers** — filter by Region and Category
- Visuals used: KPI cards, gauge chart, clustered bar/column charts, donut chart, area/line chart

## 📁 Repository Contents

```
├── README.md
├── Inventory_and_Supply_Chain_Dashboard.pbix   # Power BI source file
├── Inventory_and_Supply_Chain_Dashboard.pdf     # Exported report (static view)
├── Inventory_and_Supply_Chain_Dashboard.png     # Dashboard preview image
└── data/                                        # (optional) source dataset if shareable
```

## 🚀 How to Use

1. Clone this repo
2. Open `Inventory_and_Supply_Chain_Dashboard.pbix` in Power BI Desktop
3. Use the Region and Category slicers to explore the data interactively

## 👤 Author

**[Your Name]**
Supply Chain / Data Analytics
[LinkedIn](#) • [Portfolio](#) • [Email](#)

