# PyBer_Analysis

# Project Overview

1. Create a bubble chart that showcases the average fare versus the total number of rides with bubble size based on the total number of drivers for each city type, including urban, suburban, and rural.
2. Determine the mean, median, and mode for the following:
  - The total number of rides for each city type. 
  - The average fares for each city type. 
  - The total number of drivers for each city type.
4. Create box-and-whisker plots that visualize each of the following to determine if there are any outliers: 
  - The number of rides for each city type. 
  - The fares for each city type. 
  - The number of drivers for each city type.
 4. Create a pie chart that visualizes each of the following data for each city type:
  - The percent of total fares. 
  - The percent of total rides.
  - The percent of total drivers.


# Resources
  - Data Source: PyBer.ipynb, 
  - Software: Python 3.10.5, Pandas, Jupyter Notebook, Matplolib, Numpy


# Challenge Overview

The CEO of Pyber has requested the team to create a summary DataFrame of the ride-sharing data by city type. Then, using Pandas and Matplotlib, the team will create a multiple-line graph that shows the total weekly fares for each city type.

# Results

## Summary DataFrame by City Type
<img width="617" alt="data-Module-5-Challenge-Challenge_Summary_DataFrame (1)" src="https://user-images.githubusercontent.com/105765150/177683769-b12f96e8-309d-4a2f-916e-ff649f268892.png">
The data frame above indicates a vast difference in the number of rides between urban, suburban, and rural cities. The number of drivers in urban areas is about five times that of suburban cities and 31 times that of rural towns. Similarly, the number of rides per driver favors rural and suburban drivers over urban ones. The income suggested that the Average Fare per Ride is 20% lower than in suburban towns and 30% lower in urban cities than in rural ones. The ratio is 3.3:1 for rural vs. urban and 2.4:1 for suburban vs. urban, which indicates that rural drivers perform better than Suburban and Urban drivers in terms of Average Fare per Driver. Hence, Urban cities generate the most revenue for PyBer, customers in metropolitan cities pay less per ride; therefore, drivers earn less, and rural areas seem underserved, and customers in those areas face more expensive fares than in Urban or Suburban cities.

![data-5-1-challenge-average-fare-each-city](https://user-images.githubusercontent.com/105765150/177684082-db3c8f0f-600d-469d-bc6a-4a772995b456.png)
The chart above illustrates that from January to May, the income from the Pyber service stayed the same. Urban cities generate the most revenue, followed by suburban and rural ones. The average connection between urban and suburban cities is 2:1, while the exact relationship between urban and rural towns is 9:1. The outcome is not surprising, given that cities are expected to generate more revenue because they are bigger and have more customers than suburban or rural locations.

## Conclusion
To reduce  disparities between Urban, Suburban, and Rural cities, the team has recommended Pyber:
  -  Focus on data points  span the entire year and provide insights into yearly trends.
  -  Conduct research to confirm if there is enough demand in this market segment to justify investing in hiring more drivers.
  -  Increase the number of drivers in each area.
