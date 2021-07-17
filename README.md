# PyBer Analysis
## Overview
V. Isualize has given myself and Omar a brand-new assignment. Using your Python skills and knowledge of Pandas, create a summary DataFrame of the ride-sharing data by city type. Then, using Pandas and Matplotlib, create a multiple-line graph that shows the total weekly fares for each city type.

## Method 
Having merged the ride and city datasets, I calculated the total rides grouped by city type, driver counts by city type, and total fares by city type, 
which allowed me to then calculate the average fare by city type and average fare per driver by city type. 
The summary statistics resulting from these calculations are provided below. 

![Pyber_Ride_summary](https://github.com/cfusco77/PyBer_Analysis/blob/main/Resources/Pyber_Ride_Summary.png)

## Results 
We see that urban areas have the largest number of total rides, total drivers, and total fares; followed by suburban areas. While rural areas have the least number of total rides, total drivers, and total fares. There is a inverse relationship between these metrics and the associated costs. Average Fare per Ride and Avg Fare by Driver are the highest in rural areas, followed by suburban areas. Urban areas have the cheapest Average Fares per Ride and Average Fares per Driver. 

My hypothesis is that in urban areas where ride sharing is in higher demand, there are a greater number of drivers and therefore pricing is more compeitive. While in rural areas there are fewer drivers to meet the demand and therefore drivers can charge a higher fare. 

A second hypothesis is that in urban areas destinations are more concentrated and so trips are shorter, leading to lower average fares. Wheras in rural areas desatinations may be spread farther apart and thus individual trips longer and more costly. 

## Secondary Analysis 
Havng created a pivot table with Date as the index and city type as the column aggregated on fare, we were able to render this line chart, displayed below, which shows specifically the date range 1/1/2019 - 4/28/2019. 

![Challenge_fare_summary](https://github.com/cfusco77/PyBer_Analysis/blob/main/Challenege_fare_summary.png) 

The lines never intersect one another, which means each region type maintains its relative position largest to smallest total fare prices. 
All three regions see a spike in total fares mid Feb. Deeper analysis might reveal that total rides and/or the price of rides spike over valentines day weekend. 
Urban regions see the most volatlity in the month of March when there are seemingly weekly spikes. Deeper analysis might reveal that numbers of rides and/or ride prices surge on weekends in urban areas. 

### Summary
Based on our analysis my recommendation to the CEO is that future expansions of pyber be concentrated in urban areas where demand for rides is high and revenue opportunity appears greater. Looking at previous months should allow for a fairly accurate forecast of future performance. I would not be concerned about seasonality and employ roughly the same number of drivers as the previous month to meet ride demand.

As a test the pyber CEO might consider raising prices over weekends or on holidays. While this may reduce demand for rides by pricing out certain consumers, that revenue might be covered in the increase in avg fare per ride. 
Alternatively the CEO could lower prices over weekends or on holidays to see if some consumers are willing to take a ride service as oppossed to drive themselves if fare prices were lower. Similiarly the CEO would want to then measure if the increase in total number of rides increases profitablity and overcompensates for the lower avg fare per ride. 
