# Average Temperature Project

<h2>Global Temperature Trends Analysis</h2>
This project utilizes SQL within Google BigQuery to analyze historical weather patterns. By querying the NOAA Global Surface Summary of the Day (GSOD) public dataset, the project extracts yearly temperature averages to identify long-term climate trends.

<h2>Project Overview</h2>
The primary goal of this script is to aggregate vast amounts of daily weather station data into a concise yearly format. This processed data is designed to be used in visualization tools like Looker or Tableau to create time-series dashboards.

<h2>Data Source</h2>
Dataset: bigquery-public-data.noaa_gsod

Table: gsod* (Wildcard table covering historical records)

Provider: National Oceanic and Atmospheric Administration (NOAA)

<h2>Tech Stack & Logic:</h2>
Languages: SQL 

Selection: Retrieves the calendar year and calculates the mean temperature.

Wildcard Query: Uses the * suffix to query across all yearly tables in the NOAA GSOD dataset simultaneously.

Aggregation: Groups results by year to consolidate millions of daily records into single annual data points.

Sorting: Orders the results chronologically for seamless time-series mapping.







![image](https://github.com/aaronvillalobos4/SQL-Looker-Project1/assets/32658264/a5667905-49f6-46fe-ab3c-ad68cfba752e)



