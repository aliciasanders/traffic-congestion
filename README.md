# Traffic Congestion

This is my Capstone 1 project for Springboard's Data Science bootcamp.

Predicting Traffic Congestion Based On Prevalence and Utilization of Ridesharing Services and Public Transportation in Chicago, Illinois

## Data Wrangling

The first part of the project is data acquisition and wrangling. The three datasets I use can be downloaded as csv files (or other formats) from https://data.cityofchicago.org/. The datasets I use are:

1. Transportation Network Providers - Trips: https://data.cityofchicago.org/Transportation/Transportation-Network-Providers-Trips/m6dm-c72p
2. CTA - Ridership - 'L' Station Entries - Daily Totals: https://data.cityofchicago.org/Transportation/CTA-Ridership-L-Station-Entries-Daily-Totals/5neh-572f
3. Chicago Traffic Tracker - Historical Congestion Estimates by Region - 2018-Current: https://data.cityofchicago.org/dataset/Chicago-Traffic-Tracker-Historical-Congestion-Esti/kf7e-cur8


After downloading these 3 datasets, use data-wrangling.ipynb to clean the datasets, and then to process the data into one combined dataset, indexed on datetime and the regions as defined by the congestion dataset.
