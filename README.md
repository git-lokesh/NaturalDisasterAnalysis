# Natural Disaster Analysis

## Problem Statement
Natural disasters occur frequently across the United States and cause significant impact on lives, infrastructure, and resources. However, raw disaster declaration data is complex and difficult to analyze directly. This project aims to analyze US natural disaster declaration data to understand trends, affected regions, and disaster types, and to support better preparedness and planning through data-driven insights.

## Dataset Description
The dataset used in this project is sourced from the FEMA (Federal Emergency Management Agency) Disaster Declarations dataset. It contains historical records of natural disaster declarations across the United States from 1953 to 2024.

The dataset includes key attributes such as disaster type (e.g., Hurricane, Fire), affected state and county, declaration date, incident start/end dates, and related program indicators. The data represents real-world operational records and was cleaned and prepared using Power Query before analysis.

## Key Performance Indicators (KPIs)
To provide an immediate snapshot of disaster impact, the dashboard tracks the following high-level metrics:
* **Total Disasters:** The cumulative count of all disaster declarations in the selected period (Current Total: 3,167+).
* **Most Impacted State:** The single state with the highest frequency of disaster declarations (Identified as **Texas**).
* **Peak Year:** The historical year with the highest volume of declared disasters.
* **Most Frequent Disaster Category:** The specific type of event (e.g., Severe Storms) that occurs most often.

## Dashboard Pages
The report is divided into two analytical views to separate high-level trends from granular geographic data.

### 1. Executive Summary & Trends (Overall Analysis)
This page focuses on temporal patterns and categorical breakdowns.
* **Trend Analysis (Line Chart):** Visualizes the sharp increase in disaster frequency from 1953 to the present day.
* **Seasonality (Bar Chart):** Breaks down disaster counts by month, identifying **September** as the peak month for severe weather events.
* **Category Breakdown (Donut Chart):** Shows the percentage split of disaster types (e.g., Storms vs. Fires vs. Floods).
* **Global Filters:** Includes a "Between" slicer for custom time periods (e.g., 1990–2010) and a disaster type selector.

### 2. Geospatial Risk Analysis (Geographical Focus)
This page is dedicated to location-based risk assessment using drill-down capabilities.
* **Risk Heatmap:** A filled map of the USA that uses color intensity to highlight high-risk states (Dark Blue/Red for high frequency).
* **Drill-Down Capability:** Allows users to click on a state (e.g., Texas) to see specific data for that region.
* **Top Counties:** A ranked bar chart displaying the specific counties within the selected state that suffer the most frequent disasters (e.g., Harris County).

## Key Insights
* **Geographic Hotspots:** Texas and California consistently rank as the most disaster-prone states due to their size and exposure to multiple disaster types (Hurricanes and Wildfires).
* **Seasonal Danger Zones:** September is the most active month for disaster declarations, driven largely by the Atlantic hurricane season.
* **Rising Frequency:** There is a clear upward trend in the number of declared disasters over the last two decades compared to the mid-20th century.
* **Dominant Disaster Types:** Severe Storms and Floods account for the majority of all FEMA declarations, significantly outnumbering geological events like Earthquakes.

## Recommendations
- Use historical disaster trends to improve response planning  
- Strengthen monitoring of frequently occurring disaster types  
- Focus preparedness efforts on high-frequency disaster regions  
- Use trend analysis as a foundation for future predictive modeling  

## Tools Used
* **Power BI:** Used for data visualization, DAX measures, and UI design (Custom "Innovate" Dark Mode Theme).
* **Power Query:** Used for ETL processes, including merging state codes to full names and correcting date hierarchies.
* **Python (Jupyter Notebook):** Used for initial data inspection and Exploratory Data Analysis (EDA).
* **VS Code & GitHub:** Used for project management and version control.