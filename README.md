# Climate Trend Analysis (2008–2017)

This project presents an analysis of climate trends in Australia using historical weather data from 2008 to 2017. The focus is on understanding patterns in temperature and rainfall, specifically examining relationships between variables like `RainToday` and `RainTomorrow`. The final dashboard was created using Power BI to visualize insights interactively.

---

## Objective

To explore and visualize historical climate trends—primarily temperature and rainfall—over a 10-year period, and to derive actionable insights using interactive visualizations.

---

## Tools & Technologies Used

- Jupyter Notebook – for data preprocessing and cleaning
- Python (Pandas) – for handling and preparing the data
- Power BI – for creating dynamic dashboards and visualizations

---

## Dataset Description

The dataset includes daily weather observations from multiple Australian cities from 2008 to 2017. Key variables include:

- `Date`
- `Location`
- `MinTemp`, `MaxTemp`
- `Rainfall`
- `RainToday`, `RainTomorrow` (Yes/No flags)
- Other weather metrics like `Humidity`, `WindGustSpeed`, etc.

Only relevant columns were retained during preprocessing for a focused analysis.

---

## Workflow

1. Data Preprocessing (Jupyter Notebook)
   - Removed irrelevant or redundant columns
   - Handled missing values
   - Ensured proper data types (dates, numerics, etc.)
   - Filtered necessary variables for analysis

2. Dashboard Creation (Power BI)
   - Imported cleaned dataset
   - Created summary cards for key metrics (average rainfall, min/max temp)
   - Built a monthly trend line chart for rainfall and max temperature
   - Designed a clustered column chart showing relationship between RainToday and RainTomorrow
   - Added slicers for interactive filtering by year and location

---

## Results Summary

Sample Insights For Brisbane (2008–2017):
- The hottest months were January and February, while July had the lowest average temperatures.
- Rainfall was highest in summer and early autumn (January–March), then dropped significantly through winter.
- A strong correlation was observed: when it rained today (`RainToday = Yes`), the likelihood of rain tomorrow increased.
- The dashboard allows users to filter by year and location to analyze patterns across time and regions.

---

##  How to Run This Project

1. Open the Jupyter Notebook in the `Source_Code/` folder to explore the data preprocessing steps.
2. Launch the Power BI dashboard (provided in `.pbix` format inside the `Output/` folder) to interact with the visualizations.
3. Use slicers in the dashboard to switch between locations and years.

---

