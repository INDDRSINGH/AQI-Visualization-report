# AQI Visualization Report – Power BI

![DatabaseSchema](https://github.com/INDDRSINGH/AQI-Visualization-report/blob/main/AQI%20logo.jpg)

##  Project Overview  
This project visualizes Air Quality Index (AQI) trends using Power BI. It presents key air pollution metrics and pollutant patterns across time and locations using interactive dashboards, enabling data-driven environmental insights.

## Dashboard Preview [here](https://github.com/INDDRSINGH/AQI-Visualization-report/blob/main/Air%20Quality%20dashboard.pdf)

##  Business Objectives  
- Track KPIs such as average PM2.5, PM10, NO2, SO2, CO, O₃ across cities and months.  
- Compare AQI levels between locations and seasonal trends  
- Highlight critical pollution spikes or exceedances over standard thresholds  
- Deliver clear, actionable visual insights for policymakers, researchers, and public awareness  

##  Tools & Technologies  
- **Power BI Desktop** for dashboard development  
- **Power Query** for data ingestion and cleanup  
- **DAX (Data Analysis Expressions)** for calculated measures and trending KPIs  
- **Excel/CSV data source** 

##  Dashboard Features  
- **Time trend analysis:** Line charts showing AQI and pollutant trends over months or years  
- **Category breakdown:** Stacked visuals of AQI categories (Good, Moderate, Poor, etc.)  
- **Pollutant comparisons:** Bar/column charts for PM2.5, PM10, CO, NO2, etc.  
- **Geographical differentiation:** (If applicable) selection tools to compare cities or zones  
- **KPI Cards:** Highlight average AQI and pollutant levels using DAX measures  
- **Interactive slicers:** Filter visualization by city, date, or pollutant type  


##  Sample Dataset  
- Example dataset includes daily or monthly AQI and pollutant levels for multiple cities  
- Variables include PM2.5, PM10, NO₂, SO₂, CO, O₃, Date, and Location  


##  Data Processing  
- Imported raw data via Power Query and performed transformations (e.g., formatting dates, handling missing values)  
- Created custom DAX measures for:
  - Average AQI per city and time period  
  - Percent of days where AQI exceeded health thresholds  
  - Ranking cities by PM₂.₅ levels or pollutant proportions

##  Insights & Takeaways  
- Seasonal spikes in PM₂.₅ and PM₁₀ (e.g., increased particulate matter in winter months)  
- Certain cities persistently exceed AQI safety thresholds  
- Patterns such as a higher frequency of "Unhealthy" days in specific zones  
- Correlation between pollutants observed (e.g., CO and NO₂ increasing in tandem)

