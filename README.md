# US 2023 Fatal Accidents Analysis Dashboard

# Project Overview

Data analysis and visualisation project investigating US fatal accidents in 2023. 

The project explores general accident statistics, fatality rates across states, and analyzes patterns in the data. Data cleaning is performed using Python. The Jupyter Notebook is accessed here: . I use SQLite queries to extract the relevant data, and the code is accessed here: . Finally, I use Power BI to visualise the most interesting and insightful findings.


# Dataset
- Source: National Highway Traffic Safety Administration
- Dataset Size: 37,000+ Rows and 80 Columns
- Year: 2023
- Key Columns:
  - STATENAME – U.S. State
  - MONTHNAME, DAY_WEEKNAME, HOUR – Temporal variables
  - FATALS – Fatalities per accident
  - PEDS – Pedestrian involvement
  - LGT_CONDNAME - Light condition
  - HOSP_HR, ARR_HOUR, NOT_HOUR – Emergency response timing
 
  # Data Analysis and Visualisation

- **Accident Trends**: Distribution by month, weekday vs weekend, and peak accident hours.
- **Geographic Insights**: States ranked by fatalities and normalized fatality rates (per 100k residents).
- **Risk Factors**: Rural vs urban comparisons, intersection/junction accidents, and impact of light/road conditions.
- **Pedestrian Safety**: Fatality ratios for pedestrian vs non-pedestrian accidents, state-wise breakdowns.
- **Response Times**: Average EMS arrival and notification delays analyzed using derived time fields.
- **Comparative Insights**: Identified states, times, and conditions most associated with high fatality risk.


