This repository contains the code and files to calculate the weekly benefit amount (WBA) replacement rate (the unemployment insurance indicator). 

This indicator was used in the paper "More robust unemployment benefits associated with reduced drug overdose mortality in the United States before and during the COVID-19 pandemic" by Martins SS, et. al.

The file "County_level_wba_calculation.RMD" is an RMarkdown file that contains annotated code that shows the calculations done to estimate the WBA replacement rate at the county level. The following files are used in this code to reproduce the WBA replacement rate calculation:

- states_and_abbreviations.xlsx, which is an excel file containing the names and abbreviations of all US states. 
- max_allowed_WBA_2014_2021.xlsx contains the maximum allowed WBA by a state per year and quarter. The maximum allowed WBA was calculated based on state's statuses, provisions, policies, and supplemental payments to eligible unemployed workers during the 2020 COVID-19 pandemic.
- median_household_income_county.csv are the median household income by county from the U.S. Census Bureau American Community Survey.
- supplemental_COVID_UI.xlsx contains data on the 600 and 300 dollar COVID supplementary unemployment insurance and when it was active in each state. 

Additionally, we included the following files:

- state_UI_provisions.xlsx contains data on states' provisions, statuses, policies, and rules used to calculate the maximum allowed WBA.
- county_wbarr.xlsx shows the wba replacement rate per quarter at the county level.