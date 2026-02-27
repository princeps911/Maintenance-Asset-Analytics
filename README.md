# Asset Reliability & NPT Analytics Dashboard (Power BI)

##  Project Overview
This project is a comprehensive Reliability and Maintenance (R&M) dashboard designed for the Upstream Oil & Gas sector. It transforms raw CMMS (Maintenance) and Production data into actionable insights focused on reducing **Non-Productive Time (NPT)** and optimizing maintenance strategies.

The dashboard focuses on the "Three Pillars" of Reliability Engineering:
1. **Executive Overview:** Financial impact of downtime and YTD production goals.
2. **Failure Analysis:** Utilizing the 80/20 rule (Pareto) to identify systemic "Bad Actors."
3. **Maintenance Strategy:** Quantifying the ROI of Preventive vs. Corrective work.

## 📊 Key Features & Visuals
* **Pareto Analysis:** Identification of the top 20% of failure modes causing 80% of downtime.
* **Reliability Scatter Plot:** Mapping assets by MTBF vs. Maintenance Cost to find "Money Pits."
* **NPT Impact Calculation:** Integration of production netback prices to quantify lost revenue ($/bbl).
* **Root Cause Hierarchy:** Treemap visualization of systemic failure triggers (e.g., Lubrication, Corrosion).
* **Mobile-Ready Layout:** Optimized view for field supervisors and on-site engineers.

## 🛠 Tech Stack
* **Power BI Desktop:** Report authoring and data visualization.
* **DAX (Data Analysis Expressions):** Advanced measures for Cumulative %, MTBF, and Deferred Production Value.
* **Power Query (M):** Data cleaning and Star-Schema modeling (Fact_WorkOrders, Dim_Date, Dim_Assets).

## 📈 Engineering Best Practices Applied
* **ISO 14224 Standards:** Alignment with industry-standard failure classification.
* **YTD Tracking:** Year-to-Date performance vs. Target (95% Uptime).
* **Sync Slicers:** Seamless navigation across the "Executive," "Engineer," and "Financial" views.

---
*Created by Prince Akpobasa*
