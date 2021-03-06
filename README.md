# Social Distancing Analysis
We want to explore the effectivenss of social distancing, how active people are, and what the driving forces behind their social distancing decisions are in the Ontario, Canada.

This is a Python, MySQL, Tableau project. Python is used to clean, process raw data, and conduct feature engineering. After these initial works, a MySQL database with cleaned data is built for storage purpose. Finally, an [interactive Tableau storyboard](https://public.tableau.com/shared/8ZYP78GZM?:display_count=y&:origin=viz_share_link) is built for presentation. 

## Data Sources
- Google COVID-19 Community Mobility Reports https://www.google.com/covid19/mobility/
- Government of Canada's Weather Data https://climate.weather.gc.ca/historical_data/search_historic_data_e.html
- Ontario covid cases https://data.ontario.ca/dataset/status-of-covid-19-cases-in-ontario/resource/ed270bb8-340b-41f9-a7c6-e8ef587e6d11
- ontario lockdown timeline info https://globalnews.ca/news/6859636/ontario-coronavirus-timeline/

## Data Cleaning
- All files that begin with "ON_" are cleaned files and ready for next steps. 

## Machine Learning Feature Selection
- "All in one.ipynb" contains all feature selection algorithm, as well as a pearson correlation chart. 
