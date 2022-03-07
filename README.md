# PyBer Analysis

## Overview
Ridesharing services have grown in popularity year after year. The main way to understand the market however would be to perform a market analysis which would help uncover trends. Pybear is the company where data would be extracted from and analyzed 

### Purpose
Through analysis and visualizations of the data provided, the information gathered will help aid PyBear be more strategical in their approach to the market and determine the best price points and affordability.


### Resources Utilized to Complete Analysis
* **CSV Files:** 
[city_data.csv]( https://github.com/YannMusz/PyBer_Analysis/blob/main/Resources/city_data.csv), [ride_data.csv]( https://github.com/YannMusz/PyBer_Analysis/blob/main/Resources/ride_data.csv)
* **Jupyter Notebook Files:**: 
[PyBer.ipynb]( https://github.com/YannMusz/PyBer_Analysis/blob/main/PyBer.ipynb), 
[PyBer_Challenge.ipynb]( https://github.com/YannMusz/PyBer_Analysis/blob/main/PyBer_Challenge.ipynb)
* **Python**: Python v3.7.6, Dependencies: Pandas Library and Matplotlib Library

## Results

### Overview of City Types
The chart below shows the relationship between city type and the number of rides per city, the total number of drivers per city and the average fare paid per city. The circle size correlates with driver count per city.

![Fig1](https://github.com/YannMusz/PyBer_Analysis/blob/main/Analysis/Fig1.png)

### Ride Counts by City Type

Ride counts by city type is visualized using a box-and-whisker plot and a pie chart. The box-and-whisker plot shows that the urban ride count data includes an outlier with 39 rides in one city. In rural cities, the average number of rides is approximately 4 times lower than urban cities and 3.5 times lower than suburban cities. The pie chart conveys similar information, with each pie wedge representing a city and the percentage of its total rides. 

![Fig2](https://github.com/YannMusz/PyBer_Analysis/blob/main/Analysis/Fig2.png)
![Fig6](https://github.com/YannMusz/PyBer_Analysis/blob/main/Analysis/Fig6.png)

### Driver Counts by City Type
We can see that on average the number of urban drivers is 9 times more elevated than the number of rural drivers and it also shows that the number of suburban drivers is 4 times higher than the number of rural ones. No outliers were shown through the data.

![Fig4](https://github.com/YannMusz/PyBer_Analysis/blob/main/Analysis/Fig4.png)
![Fig7](https://github.com/YannMusz/PyBer_Analysis/blob/main/Analysis/Fig7.png)

### Fare Counts by City Type
Fare counts by city type is expressed through the number of fares per city type, the percentage of total fares by city type and the total weekly fares for each city type. The box-and-whisker plot does not show any outliers; however, it shows that the average fare for rides in rural cities is higher ($36) than those in urban cities ($25) and suburban cities ($31).The pie chart shows that urban cities have the highest percentage of total fares with 62.7% of rides, whereas suburban cities have 30.5% total fares and rural cities have 6.8%.

![Fig3](https://github.com/YannMusz/PyBer_Analysis/blob/main/Analysis/Fig3.png)
![Fig5](https://github.com/YannMusz/PyBer_Analysis/blob/main/Analysis/Fig5.png)
![PyBer_Fare_Summary](https://github.com/YannMusz/PyBer_Analysis/blob/main/Analysis/PyBer_fare_summary.png) 

## Summary
The following changes and recommendations could be made.
1.	Having more data that spanned more than a third of the year could be deemed benefitial and help understand long terms trends within the riders. 
2.	Running an analysis on the demographics of the riders could offer further knowledge on different characteristics/habits of a population. 
3.	Providing incentives to keep loyal customers and drivers and attract new ones, will help drive business and strengthen bonds  with existing riders and drivers. 
