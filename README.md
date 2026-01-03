# ⚡ EV Charging Station Demand Analysis

## 📌 Project Overview
The rapid growth of Electric Vehicles (EVs) has increased the need for efficient and data-driven charging infrastructure planning.  
This project analyzes EV charging station usage data to identify **demand patterns across time, location, user behavior, and charger types**, enabling informed decision-making for sustainable EV infrastructure development.

The analysis was performed using **Python for data analysis** and **Power BI for interactive visualization**.

---

## 🎯 Business Questions Answered
This project focuses on answering the following real-world business questions:

1. Which hours have the highest charging demand?
2. Peak vs Off-Peak demand comparison
3. Which cities have the highest EV charging demand?
4. Energy demand by city (kWh)
5. Weekday vs Weekend charging behavior
6. Demand by user type
7. Charger type utilization
8. Monthly demand trend (Time-Series)

---

## 📊 Dataset Description
The dataset contains EV charging session records collected from multiple charging stations.

**Key attributes include:**
- Charging start and end time
- Energy consumed (kWh)
- Charging duration and charging rate
- Charging station location (city)
- User type (Commuter, Casual Driver, Long-Distance Traveler)
- Charger type (Slow, Fast, Standard)
- Battery capacity and distance driven

After cleaning, the dataset contains **~1,100+ valid charging sessions** suitable for demand analysis.

---

## 🧹 Data Cleaning & Feature Engineering
The following steps were performed using Python:
- Converted charging timestamps to datetime format
- Removed records with missing critical energy and charging values
- Created time-based features (hour, weekday, month, year)
- Classified sessions into Peak and Off-Peak periods
- Created demand and energy KPIs for analysis
- Prepared Power BI–ready analytical tables

---

## 📈 Exploratory Data Analysis & Insights
Key analytical insights include:
- Charging demand peaks during specific early morning and weekday hours
- Off-Peak charging dominates overall usage
- Urban cities generate the highest charging demand and energy consumption
- Commuters are the primary users of charging infrastructure
- Slow chargers are utilized more frequently, followed by fast chargers
- Monthly trends indicate variation and potential seasonality in demand

---

## 📊 Power BI Dashboard
An interactive Power BI dashboard was developed to visualize insights for non-technical stakeholders.

**Dashboard includes:**
- KPI cards summarizing demand metrics
- Hourly charging demand trends
- Peak vs Off-Peak comparison
- City-wise charging and energy demand
- User type and charger type utilization
- Interactive slicers for dynamic analysis

---

## 🛠️ Tools & Technologies
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Google Colab
- Power BI
- CSV Dataset

---



## 💡 Business Value
- Supports EV infrastructure expansion planning
- Helps identify peak demand periods for load management
- Enables city-level prioritization for charging stations
- Assists in optimizing charger type allocation
- Encourages data-driven energy and sustainability decisions

---

## 📌 Conclusion
This project demonstrates how EV charging data can be transformed into actionable insights using Python and Power BI. The analysis highlights real-world demand patterns and provides valuable guidance for EV infrastructure planning and energy optimization.

---

## ⚠️ Disclaimer
This project is created for academic and portfolio purposes using publicly available data.  
It does not represent real operational metrics of any specific EV charging provider.

