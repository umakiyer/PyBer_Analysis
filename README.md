# PyBer_Analysis

## Overview of Analysis
* Using the city data & ride date, create DataFrame of teh ride-sharing data by city type.
* Create multiple-line graph for the total weekly fares for each city type.

## Ride-sharing summary DataFrame by city type:
* Read the rida data & city data into the data frame.
* Merged the rida data & city data to create a new dataframe.
* Retrived  the total number of rides by city type by using the 'groupby' on the city type.
* Retrieved the total number of drivers for each city type from City data file.
* Retrieved the sum of teh fares by city type.
*  The average fare per ride was calculated by dividing the total fares by total number of rides.
* The average fare by driver for each city type was calculated by dividing the total fares by number of drivers.
* Created and formatted new data frame with the above data:

![image](Images/Pyber_data_frame.PNG)

## Created a multiple line plot showing the total weekly of the fares for each type of city:
* Created a dataframe for the sum of the fares for each date ,using 'groupby' function with two indices city type and date.
* Reset the index on the dataframe using the 'reset_index' function.
* Changed the data type of date from object to datetime object using the datetime function
* Created pivot table with date as index, type for columns, fares for values.
* Converted the date index into date type
* Created new dataframe by using the 'resample' function by week and got the sum of the fares for each week.
* The object oriented approch was used to plot the multiple line graph for each 
city type as shown below.

![Multiple-Line_Plot](analysis/PyBer_fare_summary.PNG)

## Result of the analysis:
* The Urban city has lower average fare compared to suburban & rural cities.
* The total number of rides in the urban city is relatively higher compared to suburban & rural cities
* The average fare per ride & per driver is relatively more for the rural city.

## Summary
 1.
 2.
 3.
 












