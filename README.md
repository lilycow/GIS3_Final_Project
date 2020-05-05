# GIS3 Final Project: Predicting Manhattan Home Sales 🏠

**Current Progress:** https://htmlpreview.github.io/?https://raw.githubusercontent.com/lcao21/GIS3_Final_Project/master/Progress/5%3A5.html

# **Data Sources** 📑
1) NYC Property Rolling Sales: https://www1.nyc.gov/site/finance/taxes/property-rolling-sales-data.page 
    * Titled "manhattan.csv" in the data folder
2) NYC School Locations: https://data.cityofnewyork.us/Education/2019-2020-School-Locations/wg9x-4ke6
    * Titled "schools.csv" in the data folder
3) NYC Healthy Stores: https://data.cityofnewyork.us/Health/Recognized-Shop-Healthy-Stores/ud4g-9x9z
4) NYC Farmers' Markets: https://data.cityofnewyork.us/dataset/DOHMH-Farmers-Markets/8vwk-6iz2
5) NYC Parks: https://data.cityofnewyork.us/Recreation/Open-Space-Parks-/g84h-jbjm
6) NYC Subway Stations: https://data.cityofnewyork.us/Transportation/Subway-Stations/arq3-7z49

# **Timeline and Process** ⏱
- [X] Clean property data
- [ ] Create indpendent variables from the 5 other datasets (schools, healthy stores, farmers' markets, parks, subway stations) and merge with property data *May 9th*
- [ ] Feature selection with Boruta and/or Random Forest *May 16th*
- [ ] Train various models and pick the one with the smallest MAE *May 23th*
- [ ] Map prediction results vs actual in Manhattan *May 30th*
- [ ] Map prediction results vs actual in another borough *June 6th*
- [ ] Get and map prediction results for new data *June 6th*

## **(1) Data Cleaning and Wrangling**
**Libraries Used:** data.table, stringr, ggmap, OpenStreetMap, tmaptools, dplyr, lubridate, ggplot2, ggrepel, tidyverse, osmdata, sf, rgeos, rgdal,

**Geocomputation Operations Used:** st_as_sf(), ggmap(), geom_point(), proj4string(), subset(), st_intersection(), merge(), get_stamenmap(), st_transform(), st_buffer(), group_by(), as.numeric()

![alt text](https://github.com/lcao21/GIS3_Final_Project/blob/master/Maps%20and%20Graphs/homesbysaleprice.png =100x100)

## **(2) Feature Selection**

## **(3) Model Training**

## **(4) Results** 

## **(5) Another Borough and New Data** 

