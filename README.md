# EDS 213 Group Project, Team Sea Breeze
## Juliet Cohen, Grace Lewin, Jake Eisaguirre, Connor Flynn
### Project Objective
#### Question: How does wind speed affect sea surface temperature and chlorophyll in our local Santa Barbara Channel during the year 2020?
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

#### Link to KnB Repository 
https://knb.ecoinformatics.org/view/urn%3Auuid%3A24305c72-4c9f-4406-a21b-ed818d480333


#### API
##### We plan to use the REDDAP API to pull sea surface temperature and clorophyll data from the NOAA Aquamodis Satelite. Next, we will manually pull wind speed data from the NOAA East Buoy by downloading and uncompressing the 2020 Standard Meteorological Data Files. 
##### Using R Studio, we will use the function rbind() to combine the datsets with time as the primary key, and analyze patterns between the three variables.

### Data Management Plan: In Issues
Issue #2


#### For Assignment 10/19/21 look at the Sea_Breeze.Rmd to view code

### Overview of results and further research ideas:
- We did not see strong relationships between wind speed and sea surface temperature or between wind speed and chlorophyll in the Santa Barbara Channel in 2020.
- We did see a slight trend in that the maximum sea surface temperature aligned temporally with lower wind speeds in the Santa Barbara Channel in 2020. 
- An avenue for further research could be to look at data from multiple years together to see if there are annual trends that occur repeatedly throughout years. This might show stronger trends as it would lessen the effects of abnormal wind events in specific years.
