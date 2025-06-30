# 🚗 Mobility | EV Market Readiness & Implications for Autonomous Vehicles

This project explores global electric vehicle (EV) adoption trends from 2010 to 2024 to assess how market maturity and infrastructure readiness could influence autonomous vehicle (AV) deployment. Using Tableau and a dataset from the IEA (International Energy Agency), I visualized EV growth, sales share by powertrain, and regional market strength to highlight where AV scalability may be most feasible.


🔗 *[View Tableau Dashboard Here!!](https://public.tableau.com/views/EVMarketReadinessAVImplications/Dashboard1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)*


---

## 🎯 Project Objective

- Visualize EV growth across countries and years
- Identify top-performing EV markets and tech trends (BEV vs. PHEV)
- Draw data-backed implications for AV readiness based on infrastructure maturity

---

## 🛠️ Tools Used

- **Tableau** – Interactive dashboard design  
- **Google Sheets** – Data cleanup and pivot  
- **Pandas** – Initial preprocessing of IEA data
- **Jupyter Notebook** - Data cleaning, feature engineering, and visualizations

---


## 📊 Sample Dataset Features

| Column              | Description                           |
|---------------------|----------------------------------------|
| `region`              | Country or region name                            |
| `category`           | Always "Historical"  |
| `parameter`          | Metric type (e.g., EV sales, EV stock share)      |
| `mode`          | Always "Cars"            |
| `Powertrain`   | BEV, PHEV, etc.       |
| `year`   | 2011–2024        |
| `unit`   | Vehicles or percent depending on metric        |
| `value`   | Actual measurement        | 

---

## 📊 Dataset Summary

The dataset contains EV sales data (2011–2024) by:
- **Region**
- **Powertrain Type** (EV, BEV, PHEV)
- **Metrics**: EV sales, EV stock, EV stock share (%), EV sales share (%)

> Source: [IEA – Electric Vehicle Data](https://www.kaggle.com/datasets/jainaru/electric-car-sales-2010-2024)

---

## 📈 Tableau Dashboard Features

▶ **EV Sales Over Time**  
Compare cumulative EV sales growth by country across years

▶ **Global EV Stock Share Map**  
Visualize which regions lead in EV penetration

▶ **Sales Share by Powertrain**  
Track how BEVs and PHEVs compete in each market

▶ **Top 10 Countries by EV Sales (2023/2024)**  
Rank current leaders by total sales

▶ **Dynamic Filters**  
Filter by Year, Country, and Powertrain type


---

## 🔍 Sample Insights

- **China, the U.S., and select EU nations** dominate both in total EV sales and EV stock share
- **BEVs have overtaken PHEVs** in most top markets by 2020
- **EV sales share** is now above 25% in many markets, signaling mainstream adoption
- Countries with **early, steep EV growth curves** also show signs of AV-favorable infrastructure (charging, grid readiness, regulatory momentum)

---

## 🚀 AV Readiness: What EV Trends Tell Us

| Signal                        | Why It Matters for AVs                                  |
|------------------------------|----------------------------------------------------------|
| 📈 Fast EV Adoption           | Indicates consumer trust in non-traditional drivetrains |
| 🗺️ High EV Stock Share        | Suggests existing infrastructure can support AV fleets   |
| 🔌 BEV Dominance              | Pairs well with AV's energy optimization needs          |
| 🌍 Geographic Clustering      | AV testing often overlaps with EV rollout hubs          |
| 🏛️ Government-Backed Growth  | Signals regulatory alignment for AV deployment          |

> High-EV countries may be **first-movers** in the AV rollout because of overlapping infrastructure, policy priorities, and maturing consumer behavior around new vehicle technologies.

---
