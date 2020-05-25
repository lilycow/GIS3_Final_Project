# GIS3 Final Project: Predicting Manhattan Home Sales 🏠

# **Data Sources** 📑
1) NYC Property Rolling Sales: https://www1.nyc.gov/site/finance/taxes/property-rolling-sales-data.page 
    * Titled "manhattan.csv" in the data folder
2) NYC School Locations: https://data.cityofnewyork.us/Education/2019-2020-School-Locations/wg9x-4ke6
    * Titled "schools.csv" in the data folder
3) NYC Healthy Stores: https://data.cityofnewyork.us/Health/Recognized-Shop-Healthy-Stores/ud4g-9x9z
    * Titled "healthystores.csv" in the data folder
4) NYC Farmers' Markets: https://data.cityofnewyork.us/dataset/DOHMH-Farmers-Markets/8vwk-6iz2
    * Titled "farmersmarkets.csv" in the data folder
5) NYC Parks: https://data.cityofnewyork.us/Recreation/Open-Space-Parks-/g84h-jbjm
    * Read in as geojson file
6) NYC Subway Stations: https://data.cityofnewyork.us/Transportation/Subway-Stations/arq3-7z49
    * Read in as geojson file

# **Timeline and Process** ⏱
- [X] Clean property data
- [X] Create indpendent variables from the 5 other datasets (schools, healthy stores, farmers' markets, parks, subway stations) and merge with property data *May 9th*
- [X] Feature selection with Boruta *May 16th*
- [X] Train various models and pick the one with the smallest MAE *May 23th*
- [ ] Map prediction results vs actual in Manhattan *May 30th*
- [ ] Map prediction results vs actual in another borough *June 6th*
- [ ] Get and map prediction results for new data *June 6th*
- [ ] Clean up files and repository. Write final report. *June 6th*

## **(1) Data Cleaning and Wrangling**
**File:** https://htmlpreview.github.io/?https://github.com/lcao21/GIS3_Final_Project/blob/master/Progress/Data_Clean.html

**Packages:** formattable, data.table, stringr, ggmap, tmaptools, dplyr, lubridate, ggplot2, ggrepel, tidyverse, osmdata, sf, rgeos, rgdal, geojsonsf

**Geocomputation Operations:** st_as_sf(), ggmap(), geom_point(), proj4string(), subset(), st_intersection(), merge(), get_stamenmap(), st_transform(), st_buffer(), group_by(), as.numeric()

## **(2) Feature Selection**

**File:** https://htmlpreview.github.io/?https://github.com/lcao21/GIS3_Final_Project/blob/master/Progress/Feature_Selection.html

**Packages:** formattable, Boruta, corrplot

## **(3) Model Training**

**File:** https://htmlpreview.github.io/?https://github.com/lcao21/GIS3_Final_Project/blob/master/Progress/Model_Training.html

**Packages:** formattable, caret, Metrics, dplyr, randomForest, gbm

## **(4) Results** 

## **(5) Another Borough and New Data** 

