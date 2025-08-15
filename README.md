# Public Transport Demand in Ireland (THA24)

This project analyses weekly and yearly trends in public transport usage in Ireland, using the **NTA THA24 dataset** (CC-BY-4.0).  
The analysis was carried out in **Python** (for cleaning and preparation) and **Tableau** (for interactive dashboarding).

---

## **Project Overview**
The objective was to explore passenger journeys by mode of transport over time, identify seasonal and yearly patterns, and understand changes in mode share.

---

## **Data Source**
**Dataset:** NTA THA24 – Passenger Journeys (CC-BY-4.0)  
**Time Period:** 2019–2023  
**Modes Included:**
- All public transport (excluding LUAS)
- Dublin Metro Bus
- Bus (excluding Dublin Metro)
- Rail

---

## **Data Preparation**
Python was used to:
- Clean and transform raw CSV files from NTA
- Standardise column names
- Create aggregated datasets:
  - **Weekly trends**
  - **Yearly totals**
  - **Mode share per year**

Key libraries: `pandas`, `matplotlib`, `numpy`

---

## **Visualisations**
The Tableau dashboard consists of three charts:

1. **Weekly Public Transport Journeys by Mode**  
   - Line chart showing weekly passenger journeys from 2019–2023
   - Vertical dashed lines marking the start of each year

2. **Yearly Passenger Journeys by Mode**  
   - Clean, minimal line chart showing yearly totals in millions

3. **Mode Share by Year (Stacked)**  
   - Stacked bar chart showing annual share (%) for each mode
   - Inline percentage labels for clarity

---

## **How to View the Dashboard**
You can view the Tableau Public dashboard here:  
https://public.tableau.com/views/PublicTransportDemandinIrelandTHA24/Dashboard1?:language=en-GB&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link
---

## **Insights**
- Clear COVID-19 impact in 2020–2021 with sharp drops across all modes
- Gradual recovery in 2022, nearing or surpassing pre-pandemic levels in 2023
- Dublin Metro Bus consistently holds the largest share, though slightly decreasing post-pandemic
- Rail shows steady recovery, especially in 2022–2023

---

## **Author**
**Sinah Behsangar**  
MSc Data Analytics | Python | SQL | Tableau | Machine Learning  
