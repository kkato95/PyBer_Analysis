# PyBer_Analysis
## Overview of the Analysis
The purpose of this analysis was to manipulate and observe the ride sharing company's metrics. We analyzed the number of riders, drivers, and fares in each of the the three types of cities: 

1. Urban
2. Suburban
3. Rural

Then we observed the summation of fares in week intervals and per city type. Then created a Total Fare by City Type line graph showing the fare in each month per the 3 types of cities.

## Results

### Differences In Ride-Sharing Data Among Different Cities
As we can see in Fig. 1, the urban cities has by far first when looking at the largest number of total rides, total drivers, and total fares. Suburban drivers have the second largest numbers with 1/2 of the total fares and 1/10 the total drivers. Rural is far behind with just 1/10 of the toal fares as the Urban drivers.

A better illustrator are the Average Fare per Ride and Average Fare per Driver. The urban driver makes 10x the amount, on average, than that of the rural drivers. The average fare per ride in the urabn cities is 9.2x more expensive than the rural fare per ride and nearly 2x more expenive than suburban cities.

![pyber_summary_df](https://user-images.githubusercontent.com/99375741/160307869-ea530af2-5eb6-4e27-baba-d77603fad6e3.PNG)

### Create Multi-Line Plot to Show Total Weekly Fares Among Different Cities
As observed in the Total Fare by City Type line graph, we have plotted 3 lines representing the rural suburban, and urabn city types. The y-axis shows the total fares for each city and the x-axis shows the progression of time. Each point shows the total fares collected in each city each week. 

![PyBer_fare_summary](https://user-images.githubusercontent.com/99375741/160307750-d1bdc775-4e7c-4fe4-807e-338b120044b3.png)

Over time, the graph show the total fares collected each week in each city type remained relativly stable. The lines did not cross each other at any point in time. The ranking remains the same as the first section of the results; Urban is ranksed 1st, suburban is ranked 2nd, and rural is ranked 3 in the total fares collected each week.

## Summary - There is a statement summarizing three business recommendations to the CEO for addressing any disparities among the city types

The disperities among the different city types are glaring in nearly all segments of the ride-sharing data. Some disperities are a result of the geographical dynamics and are not inherently bad. Below are 3 business recommondation to the CEO to address the disparities in these city types:

1. The average fare per ride for urban cities is 9.2x higher than in the rural areas - CEO to higher more dirvers in the city to increase supply of drivers, causing decrease in price per fare for the rider.
2. The average fare per diver is 0.06 in the rural cities - CEO to remove drivers from rural areas because the there are many more drivers to rides than in the Urban areas.
3. The cost per ride and driver fares are much lower for rural cities even though the distance is likely higher - CEO to charge high price per mile traveled to balance out the cost in an urban city as compared to a rural city. 

