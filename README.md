# PyBer Analysis

## Overview of Project
PyBer is a ride-sharing app company valued at $2.3 billion.  The CEO has assigned this project to analyze all the rideshare data from January to early May of 2019 and create a compelling visualization.  In order to produce a summary, perform analysis and make recommendations python and Pandas will be used to create a summary DataFrame of the ride-sharing data by city type and Pandas and Matplotlib will be used to create a multi-line graph that shows the total weekly fares for each city type.  Rider and city type data .csv files have been provided as the data source.  The final deliverable is a written report that summarizes how the data differs by city type and how these differences can be used by decision-makers at PyBer.

### Purpose
The purpose of this project is to use images from the summary DataFrame and multi-line chart and describe the differences in ride-sharing data among the different city types.  Based on the results business recommendations need to be made to the CEO for addressing any disparities among the city types.

## Results

### Ride-Share Results
There are three ride-share areas, urban, suburban and rural.  As would be expected number of rides and total fares are highest in the urban area as the population and ride-share demand is highest and the lowest number of rides and fares are in the rural area.  The suburban area falls in the middle.  A concern from a business standpoint is the disproportionate number of drivers in the urban area based on ride-share demand and compared to the other two areas.  This in turn results in a much lower average fare per driver in the urban area compared to the other two regions.  The results are as follows:

![Ride_Share_Summary](https://raw.githubusercontent.com/JBro-Birds/PyBer_Analysis/master/analysis/Ride_Share_Summary.png)

Total Fare by City Type Line Chart:

![Total_Fare_By_City_Type_Line_Chart](https://raw.githubusercontent.com/JBro-Birds/PyBer_Analysis/master/analysis/Total_Fare_By_City_Type_Line_Chart.png)

## Summary

### Recommendations
There are three business recommendations for addressing disparities among city types.
* Eliminate a number of urban drivers.  There are too many urban drivers based on demand which in turn is lowering the average fare per driver.  The lower average fare per driver is going to discourage urban drivers and create business issues in the future.  Eliminating a number of urban drivers will lower company costs.
* Create and implement a driver-by-area flexibility model based on periods of higher demand by area.  Based on driver home addresses have rural and suburban drivers 
swap areas when needed and likewise have suburban and urban drivers swap areas.  This type of flexibility will increase driver morale by increasing their average fare by driver and increase company efficiencies.
* Revise ride-share pricing structure with rates based on demand by area.  Since there is a much greater demand in the urban area compared to the rural area this will create less fare per ride disparity between urban and rural riders. 
