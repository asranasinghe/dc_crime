# README

## Project Title: Analysis of DC Violent Crime, MPD Headcount, and D.C. Law 24-345

### Overview:

This repo provides information regarding data, methodology, and other contexual information regarding the following __[post](https://x.com/sebbystats/status/1746682052508876838?s=20)__ on X: . The post includes a graphic that showcases the relationship between violent crime rates in Washington, DC, the headcount of the Metropolitan Police Department (MPD), and the impact of D.C. Law 24-345, titled "Comprehensive Policing and Justice Reform Amendment Act of 2022." Enacted on January 19, 2023, this legislation introduces comprehensive reforms to policing and justice practices in the District of Columbia.

### Data Sources:

1. __[DC Crime Card](https://crimecards.dc.gov/all:crimes/all:weapons/dated::01012010:01012024/citywide:heat)__
   - Utilized historical datasets containing information on violent crime rates in Washington, DC.
   - Data found under /data/dc-crimes-search-results.csv

2. __[MPD Staffing Reports](https://mpdc.dc.gov/node/1653316)__
   - Collected data on the sworn office headcount of the Metropolitan Police Department.
   - Monthly reports available from October 2017 onwards.
   - "Sworn total" of each monthly report was compiled and saved under /data/mpd_staffing.csv

### Usage Instructions:

1. Download data

2. Run dc_crime_analysis.ipynb, which will read in datasets above, and output data/dc_crime_output.csv.

3. Visualize in platform of your choice. 
