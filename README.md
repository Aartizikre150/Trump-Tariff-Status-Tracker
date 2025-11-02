# 🇺🇸 Trump Tariff Status Tracker (Power BI)

A newsroom-style interactive dashboard mapping and analyzing **2025 U.S. tariffs** by **country, product, legal authority,** and **effective date** built in Power BI.  
It visualizes shifting trade dynamics and provides insight into global tariff impact zones.

<p align="center">
  <img src="https://github.com/Aartizikre150/Trump-Tariff-Status-Tracker/blob/main/Images/Tariff.jpg?raw=1" width="800px" alt="Trump Tariff Status Tracker Banner" style="border-radius:10px;box-shadow:0 4px 12px rgba(0,0,0,.15);">
</p>

---

## ⚡ Quick Start

1️⃣ **Import data**  
   Load your dataset (or use `data/sample_tariffs.csv`) into Power BI.

2️⃣ **Power Query setup**  
   - Open **Power Query Editor**  
   - Paste code from [`powerbi/StatusColumn_PowerQuery.m`](powerbi/StatusColumn_PowerQuery.m)  
   - This script generates the dynamic `Status` column for tariff tracking.

3️⃣ **Data Category Mapping**  
   In **Data View**, set:  
   - **Geography → Data Category → Country/Region**

4️⃣ **Map Visualization (by Squillion)**  
   Configure:  
   - **Location → `Geography`**  
   - **Legend → `Status`**  
   - **Tooltip → `Rate`, `Target`, `Date in effect`, `Legal authority`**

5️⃣ **Apply Dashboard Theme**  
   - Go to **View → Themes → Browse → `powerbi/theme.json`**

---

## 🌍 Dashboard Preview

<p align="center">
  <img src="https://github.com/Aartizikre150/Trump-Tariff-Status-Tracker/blob/main/Images/Dashboard.png?raw=1" width="800px" alt="Power BI Tariff Dashboard Screenshot" style="border-radius:10px;box-shadow:0 4px 12px rgba(0,0,0,.15);">
</p>

---

## 📰 Headlines & Insights

| Headline | Summary |
|-----------|----------|
| 🟢 **U.S. Slashes Small-Parcel Tariffs on China from 120% → 54%** | The cut eases consumer import costs while maintaining strategic pressure. |
| 🔴 **Canada Faces Steepest North American Tariffs (35%)** | Highlights intra-USMCA tensions over sector reciprocity. |
| 🟡 **Southeast Asia Emerges as Mid-Tier Target Zone (18–25%)** | A shift from single-country disputes to regional containment. |
| ⚪ **Global Tariff Baseline Set at 10%** | Establishes a universal minimum — no country is fully exempt. |

---

## 🔍 Tech Stack

- **Power BI** — Interactive visualization and mapping  
- **Power Query (M)** — Data transformation and automation  
- **CSV Data Model** — Lightweight import/export  
- **JSON Themes** — Custom color and typography control  

---

## 🌎 About This Project

This Power BI dashboard delivers a **real-time lens on 2025 U.S. trade tariffs**, combining policy tracking, geographic data visualization, and contextual analysis.  
It’s designed for journalists, policymakers, and analysts monitoring trade shifts and geopolitical effects.

---

✨ *Turning complex tariff data into global insight maps.*
