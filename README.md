# ⚡ Electric Vehicle Data Analysis Dashboard

<div align="center">

![EV Dashboard Preview](clip/EV%20dashboard.png)

<br/>

[![Tableau](https://img.shields.io/badge/Built%20with-Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)](https://www.tableau.com/)
[![Data](https://img.shields.io/badge/Dataset-150%2C407%20Vehicles-4CAF50?style=for-the-badge&logo=databricks&logoColor=white)]()
[![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Live-brightgreen?style=for-the-badge)]()

**A comprehensive Tableau dashboard analyzing Electric Vehicle adoption trends, model distribution, geographic spread, and CAFV eligibility across the United States.**

[📊 View Dashboard](#) • [📁 Dataset](#dataset) • [🚀 Getting Started](#getting-started) • [📬 Contact](#contact)

</div>

---

## 🔍 Overview

This project delivers an interactive **Electric Vehicle (EV) Data Analysis Dashboard** built in Tableau. It explores real-world EV registration data to uncover patterns in adoption rates, brand dominance, geographic distribution, and clean alternative fuel vehicle (CAFV) eligibility.

> 💡 **Key Insight:** Tesla alone accounts for **52.7%** of all registered EVs, with Model Y and Model 3 leading the charts — while Washington state dominates with **150,078** registered vehicles.

---

## 📊 Dashboard Highlights

| Metric | Value |
|--------|-------|
| 🚗 Total Vehicles | **150,407** |
| ⚡ Avg. Electric Range | **67.83 Miles** |
| 🔋 Total BEV Vehicles | **116,741** (77.62%) |
| 🔌 Total PHEV Vehicles | **33,666** (22.4%) |
| ✅ CAFV Eligible | **62,884** (41.81%) |
| ❓ CAFV Unknown | **69,696** (46.34%) |

---

## 📈 Visualizations Included

```
📌 KPI Cards         →  Avg. Electric Range | Total Vehicles | BEV vs PHEV split
📅 Line Chart        →  Total Vehicles by Model Year (2011–2024)
🗺️ Choropleth Map    →  Total Vehicles by US State
🏆 Bar Chart         →  Top 10 Manufacturers by Vehicle Count
🍩 Donut Chart       →  CAFV Eligibility Breakdown
📋 Ranked Table      →  Top 10 Models with Make, EV Type & % Share
```

---

## 🏆 Top 10 Makes

| Rank | Make | Vehicles | Market Share |
|------|------|----------|-------------|
| 🥇 | Tesla | 68,938 | 52.70% |
| 🥈 | Nissan | 13,496 | 10.32% |
| 🥉 | Chevrolet | 12,023 | 9.19% |
| 4 | Ford | 7,601 | 5.81% |
| 5 | BMW | 6,439 | 4.92% |
| 6 | Kia | 6,197 | 4.74% |
| 7 | Toyota | 5,218 | 3.99% |
| 8 | Volkswagen | 4,074 | 3.11% |
| 9 | Volvo | 3,536 | 2.70% |
| 10 | Jeep | 3,289 | 2.51% |

---

## 🚗 Top Models

| Model | Make | Type | Vehicles | Share |
|-------|------|------|----------|-------|
| Model Y | Tesla | BEV | 28,501 | 18.95% |
| Model 3 | Tesla | BEV | 27,707 | 18.42% |
| Leaf | Nissan | BEV | 13,186 | 8.77% |
| Model S | Tesla | BEV | 7,609 | 5.06% |
| Bolt EV | Chevrolet | BEV | 5,731 | 3.81% |

---

## 📁 Dataset

| Field | Description |
|-------|-------------|
| `Model Year` | Year of vehicle manufacture |
| `Make` | Vehicle manufacturer |
| `Model` | Vehicle model name |
| `EV Type` | BEV (Battery Electric) or PHEV (Plug-in Hybrid) |
| `Electric Range` | Max range on electric power (miles) |
| `State` | US state of registration |
| `CAFV Eligibility` | Clean Alternative Fuel Vehicle eligibility status |

> 📌 Data sourced from **Washington State Department of Licensing** — publicly available EV registration records.

 
---

 
 

<div align="center">

⭐ **If you found this useful, please star the repository!** ⭐

 

</div>
