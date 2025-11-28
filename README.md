# Air-Quality-Comparison-Madrid-vs-Delhi-Dashboard

## Introduction
Air quality is a major concern in cities worldwide due to urbanization and industrial activities. This project compares air pollution in Madrid, Spain and Delhi, India from 2015 to 2020. Using Power BI, we visualized trends in key pollutants such as PM2.5, PM10, NOx, CO, SO₂, and O₃, and classified air quality using the Air Quality Index (AQI).

The study highlights differences in air pollution levels between the two cities, helping users understand patterns, seasonal changes, and health impacts. The goal is to provide a clear and interactive way to explore air quality data and promote awareness of environmental challenges.

## Dataset 
Two datasets obtained from Kaggle were used:

1. **Madrid Dataset:** ["2001–2022 Hourly Dataset of Pollution in Madrid"](https://www.kaggle.com/datasets/ignacioqg/20012022-hourly-dataset-of-pollution-in-madrid)  
2. **Delhi Dataset:** ["Air Quality Data in India (2015–2020)"](https://www.kaggle.com/datasets/rohanrao/air-quality-data-in-india)

The datasets include hourly or daily readings of key pollutants like PM2.5, PM10, NO, NO2, NOx, CO, SO2, and O3.

To make the datasets compatible for comparison:

- Madrid dataset was filtered using Python to include only 2015–2020 data.

- Delhi dataset was filtered using Python to select only records from Delhi city (city_hour.csv).

- Both datasets were further filtered in Python to include only matching features/pollutants for consistent analysis.

Monthly averages were calculated to smooth short-term variability, and an Air Quality Index (AQI) classification was applied based on PM2.5 levels, ranging from Good to Hazardous, to provide a clear overview of air quality in both cities.

- Delhi shows higher pollution levels, often reaching Hazardous and Very Poor categories.

- Madrid maintains lower pollution levels, mostly in Good and Moderate categories.

These cleaned and filtered datasets were used to create visual comparisons and trends in Power BI dashboards.
