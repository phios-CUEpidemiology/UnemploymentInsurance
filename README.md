This repository contains the code and files to calculate the weekly benefit amount (WBA) replacement rate (the unemployment insurance indicator). 

This indicator was used in the paper "More robust unemployment benefits associated with reduced drug overdose mortality in the United States before and during the COVID-19 pandemic" by Martins SS, et. al.

The file "County_level_wba_calculation.RMD" is an RMarkdown file that contains annotated code that shows the calculations done to estimate the WBA replacement rate at the county level. The following files are used in this code to reproduce the WBA replacement rate calculation:

- States.xlsx, this is an excel file containing the names and abbreviations of all US states. 
- MaxWBA_2014_2021.xlsx, this file contains the calculated 
- median_household_income_county.csv, are the median household income by county
- COVID_UI.xlsx, data on when the 600 and 300 dollar COVID supplementary insurance was active in each state. 

Additionally, we included the following files:

- By Variable State UI Provisions.xlsx, which contains data on states' provisions used to calculate the WBA
- county_wbarr.xlsx shows the wba replacement rate per quarter at the county level.