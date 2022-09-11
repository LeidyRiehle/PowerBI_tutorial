# Power BI Tutorial
Learn how to use Power BI,"an interactive data visualization software product developed by Microsoft with primary focus on business intelligence" analyzing San Diego Drinking Water public data.

# You will learn:
- A basic understanding of Power BI Desktop and using the Query Editor
- Importing data and changing data types
- Creating new columns (introducing DAX)
- Building a dynamic chart using the data model

# Prerequisites and Preparation:
Install Power BI Desktop. 
<br> Here is the link with the instructions: https://youtu.be/D_Uq4K-BKBE
<br> No programming or dashboard experience is required!

# San Diego Drinking Water public data:

https://data.sandiego.gov/datasets/drinking-water-sample-sites/

Sample Sites: sample_sites_datasd_v1.csv

https://data.sandiego.gov/datasets/monitoring-of-indicator-bacteria-in-drinking-water/

Latest Drinking Water Tests (Bacteria):
latest_indicator_bac_tests_datasd_v1.csv

All Drinking Water Tests (Bacteria):
indicator_bacteria_tests_datasd_v1.csv

# Steps

1) Connect files and open Power Query Editor
2) Turn the first row in indicator_bacteria_tests_datasd_v1 query into the column names
3) If latest_indicator_bac_tests_datasd_v1 data is not included in
indicator_bacteria_tests_datasd_v1 append data. If data is included then delete table.
4) Delete unrequired columns
5) Merge Queries. Select all fields from table indicator_bacteria_tests_datasd_v1 and add matching fields from sample_sites_datasd_v1. Remove “nulls”
6) Load the queries into the data model.
7) Go to Model and link latest_indicator_bac_tests_datasd_v1 data to sample_sites_datasd_v1
8) Create a map using Latitude and Longitude fields.
9) Show in the map all the areas where Coliform was present during the last year.
10) Add to the report a table identifying zone names
11) Add table identifying zones with coliform during years 2021 and 2022. Include the date sampled. 
