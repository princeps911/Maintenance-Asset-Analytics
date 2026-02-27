# Asset Reliability & NPT Analytics Dashboard (Power BI)

<p align="center">
  <img src="Screenshots/Executive%20Overview.png" width="900" alt="Executive Overview">
</p>

---

## 📌 Project Overview
This project is a comprehensive **Reliability and Maintenance (R&M) dashboard** designed for the Upstream Oil & Gas sector. It transforms raw CMMS (Maintenance) and Production data into actionable insights focused on reducing **Non-Productive Time (NPT)** and optimizing maintenance strategies.

The dashboard focuses on the **"Three Pillars"** of Reliability Engineering:
1. **Executive Overview:** Financial impact of downtime and YTD production goals.
2. **Failure Analysis:** Utilizing the 80/20 rule (Pareto) to identify systemic "Bad Actors."
3. **Maintenance Strategy:** Quantifying the ROI of Preventive vs. Corrective work.

---

## 📊 Key Features & Visuals

### 1. Failure Analysis (Pareto & Root Cause)
<p align="center">
  <img src="Screenshots/Failure%20Analysis.png" width="850" alt="Failure Analysis">
</p>

* **Pareto Analysis:** Identification of the top 20% of failure modes causing 80% of downtime.
* **Root Cause Hierarchy:** Treemap visualization of systemic failure triggers (e.g., Lubrication, Corrosion).
* **Deep-Dive Matrix:** Drill-down capabilities from Asset level to specific failure mechanisms.

### 2. Strategy & Cost Deep Dive
<p align="center">
  <img src="Screenshots/Cost%20&%20Strategy.png" width="850" alt="Cost and Strategy">
</p>

* **Reliability Scatter Plot:** Mapping assets by MTBF vs. Maintenance Cost to identify "Money Pits."
* **NPT Impact Calculation:** Integration of production netback prices to quantify lost revenue ($/bbl).
* **Mobile-Ready Layout:** Optimized view for field supervisors and on-site engineers.

---

## 🛠 Tech Stack
* **Power BI Desktop:** Report authoring and data visualization.
* **DAX (Data Analysis Expressions):** Advanced measures for `Cumulative %`, `MTBF`, and `Deferred Production Value`.
* **Power Query (M):** Data cleaning and Star-Schema modeling (`Fact_WorkOrders`, `Dim_Date`, `Dim_Assets`).

## 📈 Engineering Best Practices Applied
* **ISO 14224 Standards:** Alignment with industry-standard failure classification.
* **YTD Tracking:** Year-to-Date performance vs. Target (95% Uptime).
* **Sync Slicers:** Seamless navigation across the Executive, Engineer, and Financial views.

---
*Created by Prince Akpobasa*
