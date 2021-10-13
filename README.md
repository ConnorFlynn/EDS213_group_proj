# EDS 213 Group Project, Team Sea Breeze
## Juliet Cohen, Grace Lewin, Jake Eisaguirre, Connor Flynn
### Project Objective
#### Question: How does wind speed affect sea surface temperature and chlorophyll in our local Santa Barbara Channel?
### Methods
#### Data Sources: 
##### 1. NOAA Aquamodis Satelite (8 Day Composite SST) temp
Metadata: https://coastwatch.pfeg.noaa.gov/erddap/info/erdMWsstd3day_LonPM180/index.html
##### 2. NOAA Bouy Data (East Buoy) wind 
#### API
##### We plan to use the REDDAP API to pull sea surface temperature data from the NOAA Aquamodis Satelite. Next, we will manually pull wind speed data from the NOAA East Buoy by downloading and uncompressing the 2020 Standard Meteorological Data File.
##### Using R Studio, we will use the function rbind() to combine the datsets with time as the primary key, and analyze patterns between the two variables.

