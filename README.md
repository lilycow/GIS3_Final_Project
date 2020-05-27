# GIS 3 Final Project: Predicting Manhattan Home Sales 🏠
by Lily Cao 

For my GIS 3 final project, I wanted to train a model to predict housing prices in Manhattan, New York. 

# **Goals & Objectives** 📌
Though my ultimate goal was to train a model to best predict Manhattan home sales, I also had smaller goals integral to the process. I wanted to include external independent variables not provided by the sales dataset and did so by calculating how many high schools, food vendors, parks, and subway stations were located within a buffer of each home. I also created a fifth independent variable that ranked neighborhood locations based on median incomes. By the end of the project, I will have a) a trained model; b) maps to visualize the predictions; c) prediction results for new data on Manhattan home sales, whether that be from this month or a couple years ago. 

The main reason I chose this topic was to better understand how real estate companies like Zillow estimate homes that are not even on the market. These companies and real estate agents likely use a wide array of models to determine their respective predictions, especially since every type of property and locations has its own specifics. Though the final model will be most useful for people who are thinking of putting their houses on the markets, it will also be useful for those who are considering moving to Manhattan and want to find the best valued home. Furthermore, housing prices are an important indicator of the economy. The data I am using is on rolling sales from the last 12 months (April 2019 – March 2020). The coronavirus outbreak will change or is already changing the real estate market and so building a model of data from this timeline will hopefully give insight into housing prices in the midst of this outbreak

# **Data** 📑
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
7) Neighborhood Tabulation Areas (NTA): https://data.cityofnewyork.us/City-Government/Neighborhood-Tabulation-Areas-NTA-/cpf4-rkhq
    * Read in as shapefile
    
# **Figures** 🗺
See the "Figures" folder for maps and plots.

# **Code** 💻
See the "Code" folder for the following HTML files:
1) Data Cleaning and Wrangling
2) Feature Selection
3) Model Training
4) Results
5) Results for New Data

# **Future Work**❓

# **Timeline** ⏱
- [X] Clean property data
- [X] Create indpendent variables from the 5 other datasets (schools, healthy stores, farmers' markets, parks, subway stations) and merge with property data *May 9th*
- [X] Feature selection with Boruta *May 16th*
- [X] Train various models and pick the one with the smallest MAE *May 23th*
- [X] Map prediction results vs actual in Manhattan *May 30th*
- [ ] Get and map prediction results for new data *June 6th*
- [ ] Clean up files and repository. Write final report. *June 6th*

