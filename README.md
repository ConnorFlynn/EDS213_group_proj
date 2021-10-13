# EDS 213 Group Project, Team Sea Breeze
## Juliet Cohen, Grace Lewin, Jake Eisaguirre, Connor Flynn
### Project Objective
#### Question: How does wind speed affect sea surface temperature and chlorophyll in our local Santa Barbara Channel?
### Methods
#### Data Sources: 
##### 1. [NOAA Aquamodis Satelite (8 Day Composite SST) temp](https://coastwatch.pfeg.noaa.gov/erddap/griddap/erdMWsstd3day_LonPM180.graph?sst%5B(last)%5D%5B(0.0)%5D%5B(33.1125):(34.9)%5D%5B(-120.6625):(-118.875)%5D&.draw=surface&.vars=longitude%7Clatitude%7Csst&.colorBar=%7C%7C%7C%7C%7C&.bgColor=0xffccccff )
[Metadata](https://coastwatch.pfeg.noaa.gov/erddap/info/erdMWsstd3day_LonPM180/index.html)

##### 2. [NOAA Bouy Data (East Buoy) wind](https://www.ndbc.noaa.gov/station_history.php?station=46053)
[Metadata](https://www.ndbc.noaa.gov/measdes.shtml)
#### API
##### We plan to use the REDDAP API to pull sea surface temperature data from the NOAA Aquamodis Satelite. Next, we will manually pull wind speed data from the NOAA East Buoy by downloading and uncompressing the 2020 Standard Meteorological Data File.
##### Using R Studio, we will use the function rbind() to combine the datsets with time as the primary key, and analyze patterns between the two variables.

[Sea_Breeze_NCEAS_Data_Provenance](https://docs.google.com/spreadsheets/d/19nLfPOXQPWDb65sirY04yWkPs-oYS9otppxUtECR_8U/edit?usp=sharing)
