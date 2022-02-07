# Ride Share Analysis
## Project Overview

In this analysis I worked with a dataset holding ride-sharing data. First I created a summary dataframe that displayed metrics for each of the three city types (rural, urban, suburban). Then I utilized the pivot and resample functions to create a new dataframe that showed week-by-week total ride-share fares by city type.  Lastly I used the Pandas plot method to create a line chart that displayed the results from the week-by-week analysis. I used python on jupyter notebook along with the Pandas and Mathplotlib dependencies to conduct my analysis.  

## Results
### Summary DataFrame

![Summary_pyber](https://user-images.githubusercontent.com/95651156/152724141-d0de15c3-b95b-48b0-951a-fcd2863aaeba.png)

#### Key Takeaways

* A majority of the total ride-share volume is concentrated in urban areas, with well over half the total rides occuring in urban cities
* Suburban cities  ranked second in total ride volume, but still had 1000 less rides than urban cities
* Rural, suburban and urban rank 1st to 3rd in average fare per ride and 3rd to 1st in total drivers, which indicates a negative relationship between population size and fares
* Average fare per driver appears to be negatively correlated with population size as it is highest in rural areas and lowest in urban areas

### Week-by-Week Line Chart

![PyBer_fare_summary](https://user-images.githubusercontent.com/95651156/152725532-d4d5b374-d9a2-4db4-bb6e-a8b07214ea2b.png)

* There is no crossover on the graph: In each week urban cities tallied the most total fares, suburban cities tallied the second most total fares, and rural cities tallied the least total fares
* There was more variability in total fares per week for suburban and urban cities compared to rural cities 

## Summary

###  3 Business Recommendations for CEO
* Consider temporarily subsidizing fare discounts in rural areas so people in these smaller cities consider trying the ride-share app for the first time and get to experience its convenience
* * People from rural areas that visit urban or suburban cities are more likely to use the app if they've used it prior
* Consider raising prices for rides in urban and suburban cities to reflect the greater demand in these areas for rides
* * This wil help lower the disparity in fare price between the three city types
*   Collect data that tracks fare price vs. trip length for each city type
* * This will make it easier to understand how much discrepancies in fares are due to supply/demand factors compared to trip length

