# Project Goal
This project is to collect Hong Kong residential sales & rental data from public platforms and perform an analysis / build models to answer the following questions: 
1. What are the typical types of residential properties in Hong Kong
2. What are the factors driving rental / sales price
3. Historically, which type of residential property has the best return in sales value (wip)

# Data Source
https://hk.centanet.com/

# Approach
- Web scraping residential properties' sales and rental price deal data (web scraping - centanet.ipynb)
- Map the address using Google Map API to latitude and longitude, and locate it into Hong Kong census regions / areas (data cleansing - map coordinates.ipynb)
- Build segmentation to classify properties into groups based on its attributes (cluster.ipynb)
- Visualize the data in Tableau ([Link](https://public.tableau.com/app/profile/yifei23/viz/HongKongResidentialPropertiesAnalysis2023-07/Story1?publish=yes]))

# Note
Only part of the data is captured from Jan 2022. Recent data is not yet captured and code is for reference only. 



#Reference
*2019 District Council Ordinary Election Constituency Boundaries:
https://data.gov.hk/en-data/dataset/eac-eacpsi01-dcca-boundaries-2019/resource/089bdc90-f86e-4139-9e3f-4d7a1854f0ea
Coordinates Transformation API:
https://data.gov.hk/en-data/dataset/hk-landsd-openmap-coordinates-transformation-api/resource/8348cb81-8268-4de7-9cab-f614d535f10a*