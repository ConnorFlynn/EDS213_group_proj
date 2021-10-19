# EDS 213 Group Project, Team Sea Breeze
## Juliet Cohen, Grace Lewin, Jake Eisaguirre, Connor Flynn
### Project Objective
#### Question: How does wind speed affect sea surface temperature and chlorophyll in our local Santa Barbara Channel?
### Methods
#### Data Sources: 
##### 1. [NOAA Aquamodis Satelite (8 Day Composite SST) temp](https://coastwatch.pfeg.noaa.gov/erddap/griddap/erdMWsstd3day_LonPM180.graph?sst%5B(last)%5D%5B(0.0)%5D%5B(33.1125):(34.9)%5D%5B(-120.6625):(-118.875)%5D&.draw=surface&.vars=longitude%7Clatitude%7Csst&.colorBar=%7C%7C%7C%7C%7C&.bgColor=0xffccccff )
[Satellite Metadata](https://coastwatch.pfeg.noaa.gov/erddap/info/erdMWsstd3day_LonPM180/index.html)

##### 2. [NOAA Bouy Data (East Buoy) standard meterological 2020](https://www.ndbc.noaa.gov/station_history.php?station=46053)
[Buoy Metadata](https://www.ndbc.noaa.gov/measdes.shtml)

##### 3. [NOAA Buoy Data (Santa Monica) standard meterological 2020](https://www.ndbc.noaa.gov/station_history.php?station=46025)
[Buoy Metadata](https://www.ndbc.noaa.gov/measdes.shtml)

##### 4. [NOAA Buoy Data (West Bouy) standard meterological 2020](https://www.ndbc.noaa.gov/station_history.php?station=46054)
[Buoy Metadata](https://www.ndbc.noaa.gov/measdes.shtml)




#### API
##### We plan to use the REDDAP API to pull sea surface temperature and clorophyll data from the NOAA Aquamodis Satelite. Next, we will manually pull wind speed data from the NOAA East Buoy by downloading and uncompressing the 2020 Standard Meteorological Data Files. 
##### Using R Studio, we will use the function rbind() to combine the datsets with time as the primary key, and analyze patterns between the three variables.

### Data Management Plan: In Issues
Issue #2


#### For Assignment 10/19/21 look at the Seabreeze.Rmd to view code
