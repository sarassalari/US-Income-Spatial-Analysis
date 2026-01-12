# US-Income-Spatial-Analysis
A thematic spatial analysis of 2019 US Median Household Income by county using QGIS and US Census data.
# US Median Household Income Spatial Analysis (2019)

## Project Overview
This project visualizes socioeconomic disparities across the United States at the county level. I utilized **QGIS** to perform data joining and thematic cartography to identify income trends.

## Technical Workflow
* **Projection:** Re-projected from WGS84 to **USA Contiguous Albers Equal Area Conic (ESRI:102003)** to ensure accurate area representation and professional aesthetics.
* **Data Joining:** Performed an attribute join between US Census Bureau TIGER/Line county shapefiles and ACS 5-Year Estimate CSV data using **FIPS codes** as the unique identifier.
* **Symbology:** Applied a **Graduated Symbology** using the **Natural Breaks (Jenks)** classification method with 5 classes to minimize intra-class variance.
* **Layout:** Created a professional map composition including scale bars, legends, and specialized map insets for Alaska and Hawaii.

## Tools Used
* **QGIS 3.x**
* **US Census Bureau API/Data**

## Final Result
<img width="3507" height="2480" alt="US_income_map" src="https://github.com/user-attachments/assets/fe4c67fb-eb25-4c0b-a4d0-2da146e686f5" />
