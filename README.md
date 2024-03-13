Cyclistic Case Study
Overview
This repository contains a case study analyzing the Cyclistic bike-share data. Cyclistic is a fictional bike-sharing company based in Chicago. 
The analysis aims to provide insights into customer behavior and usage patterns to inform marketing and operational strategies.

Data Source
The data used for this analysis was provided by Cyclistic and consists of trip records spanning multiple months from 2023 to 2024. 
Each trip record includes information such as ride duration, start and end locations, rider type (member or casual), and ride details 
(e.g., ride ID, rideable type).

Analysis
The analysis is conducted using SQL queries in Google BigQuery and visualizations are created in Tableau. The following aspects are explored:

Total rides and distinct rides by rider type (member vs. casual) over time
Average ride duration by rider type
Average distance per ride by rider type
Average start and end locations by rider type
The analysis aims to identify differences in usage patterns between member and casual riders and 
provide actionable insights for Cyclistic's marketing and operational teams.

Files
cyclistic_analysis.sql: SQL queries used for data extraction and analysis in Google BigQuery.
cyclistic_dashboard.twb: Tableau workbook containing visualizations of the analysis results.

How to Use
Data Extraction: Run the SQL queries in [cyclistic_analysis.sql](https://console.cloud.google.com/bigquery?project=kane-415618&ws=!1m4!1m3!8m2!1s35271655562!2se95776e3bcb0426ea9c8aed80d3f06a3) 
to extract and analyze the Cyclistic data in Google BigQuery.
Visualization: Open [cyclistic_dashboard.twb](https://public.tableau.com/app/profile/chris.hussey/viz/CyclisticRideData_17102851034360/Dashboard1#1) 
in Tableau to view the visualizations of the analysis results.
Interpretation: Review the visualizations and analysis findings to gain insights into customer behavior and usage patterns.
Actionable Insights: Use the insights from the analysis to inform marketing campaigns, pricing strategies, and operational decisions at Cyclistic.

Additional Notes
The analysis can be further extended to include additional metrics or segments for a more comprehensive understanding of Cyclistic's customer base and operational performance.
Regular updates to the analysis and visualizations can provide ongoing insights and support data-driven decision-making at Cyclistic.
