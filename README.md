# 🚌 TSRTC GAMYAM – Public Transport Analytics Dashboard

![Tableau](https://public.tableau.com/app/profile/lakshmi.sai.sree.matta/vizzes)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Domain](https://img.shields.io/badge/Domain-Data%20Analytics-blue)

---

## 📌 Project Overview

**TSRTC GAMYAM** (meaning *"Accessible Journey"* in Telugu) is an interactive Public Transportation Analytics Dashboard built in **Tableau Public**, designed to analyze and visualize the operational performance of **Hyderabad's TSRTC (Telangana State Road Transport Corporation)** bus network.

The dashboard provides data-driven insights into route efficiency, passenger trends, delay patterns, and ETA accuracy — enabling transit authorities and analysts to make informed decisions for improving public transport services.

---

## 📊 Dashboard Highlights

| Metric | Value |
|---|---|
| 🧍 Total Passengers Served | 1,035,419 |
| 🚌 Total Trips Operated | 16,644 |
| ⏱️ Overall Average Delay | 6 minutes |
| ✅ On-Time Performance | 48% |

---

## 🖥️ Visualizations

### 1. 📋 KPI Summary Panel
Displays four high-level performance metrics at a glance — Overall Average Delay, On-Time Performance Rate, Total Passengers, and Total Trips.

### 2. 📉 Delay by Route (Horizontal Bar Chart)
Compares average delay minutes across key Hyderabad bus routes:
- Ameerpet → Shamirpet
- Charminar → ECIL
- Dilsukhnagar (highest delay corridor)
- Koti → Gachibowli
- LB Nagar → Miyapur
- Mehdipatnam and more

### 3. 🕐 Peak Hours (Bar Chart – Day of Week)
Visualizes passenger volume distributed across each day of the week. **Friday** emerges as the busiest operational day.

### 4. 📈 Route Trends (Line Chart)
Tracks **daily passenger counts** from January to July 2024, revealing ridership fluctuations and seasonal demand patterns across the network.

### 5. 🎯 ETA Accuracy (Scatter Plot)
Maps **ETA Error (minutes)** against **Arrival Delay (minutes)** for each route, categorized into three accuracy bands:
- ✅ Accurate (±3 mins)
- ⚠️ Acceptable
- ❌ Inaccurate

---

## 🔍 Key Insights

- 🔴 **Dilsukhnagar corridor** has the highest average delay (~5+ minutes)
- 📉 Only **48% of trips** run on time across the network
- 📅 **Friday** is the peak operational day with highest passenger volume
- 🗺️ Several routes show **high ETA inaccuracy**, indicating room for GPS and prediction system improvement
- 📈 Ridership shows consistent weekly cycles with minor seasonal dips

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| **Tableau Public** | Dashboard design & interactive visualization |
| **Microsoft Excel / CSV** | Data source management |
| **Python** | Synthetic data generation & preprocessing |
| **SQL** | Data querying and transformation |

---

## 📁 Project Structure

```
SUM-GAMYAM/
│
├── data/
│   └── tsrtc_transport_data.csv       # Synthetic TSRTC dataset
│
├── sql/
│   └── queries.sql                    # SQL queries used for analysis
│
├── dashboard/
│   └── sum_gamyam_dashboard.twbx      # Tableau Packaged Workbook
│
└── README.md
```

---

## 🚀 How to View

1. Download the `.twbx` file from the `dashboard/` folder
2. Open it with **Tableau Public** (free) or **Tableau Desktop**
3. Interact with filters for Route Name, Route ID, Hour, and ETA Accuracy bands

> 🔗 *Or view it directly on* **[https://public.tableau.com/app/profile/lakshmi.sai.sree.matta/viz/PublicTransportAnalyticsDashboard/Dashboard1](#)** 

---

## ⚠️ Disclaimer

> This dataset is **synthetic** and modeled on real-world Hyderabad TSRTC route structures for portfolio demonstration purposes only. It does not represent actual operational data of TSRTC.

---

## 👩‍💻 Author

**Lakshmi Sai Sree** — B.Tech CSE, Vidya Jyothi Institute of Technology (VJIT), Hyderabad  
📧 [https://www.linkedin.com/in/laxmisaisree/](#) | 🌐 [https://public.tableau.com/app/profile/lakshmi.sai.sree.matta/vizzes](#) | 
💻 [https://github.com/lakshmi123-hub](#)

---

*Made with ❤️ and data in Hyderabad, Telangana*
