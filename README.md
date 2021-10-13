# Surfs Up
## Overview
We are to determine if the Surf & Ice Cream Shop can be sustained year-round. We are given temperature readings by 9 different stations in Oahu, Hawaii for the motnhs of June & December. We are then tasked to analyze temperature patterns during for said months and compare key differences between the two. If deemed unsustainable, we can then opt for a seasonal business.

## Results

<div align="center"> 

![alt-text-1](https://raw.githubusercontent.com/RobC30/surfs_up/main/Resources/jun.png) ![alt-text-2](https://raw.githubusercontent.com/RobC30/surfs_up/main/Resources/dec.png) 
 <br>

 ___June (left) vs. December (right)___
</div>

Based on a total of __3,217__ temperature readings across 9 stations in Oahu, Hawaii, we can see differences between the months of June & December. Comparing the two month's quartile statistics, there is an average of __-6%__ change in June's temperature vs. December, which is understandable as it is generally cooler on the latter part of a year. If we are to plot a histogram, the frequency of 72 degree temperature seems to be consistent during December therefore it might while in June, it is spread out as a bell-curve. Even though temperatures dropped in December, it might still be viable to keep the shop open all year-round.

<br>

<div align="center"> 

![image](https://raw.githubusercontent.com/RobC30/surfs_up/main/Resources/hist.png)
</div>


## Summary
For additional queries, it might be a good idea to incorporate the temperature readings to its respective stations. This will help us determine where to open our surf & ice cream shop business. We can also merge our data in a dataframe to create heatmaps using coordinates in combination with Weather Map API for a better visualization. See image below for the foundations of the analysis


![image](https://raw.githubusercontent.com/RobC30/surfs_up/main/Resources/station_temps.png)


![image](https://raw.githubusercontent.com/RobC30/surfs_up/main/Resources/stations_heatmap.png)