# PyBer_Analysis

## Overview of the Analysis
In this project, I combined two data spreadsheets to analyze ride data across a variety of cities. I spliced two datasets together, the city_data and ride_data spreadsheets, with the help of Python to reach the solutions asked for in the prompt. In this analysis, I looked at ride counts per city type, average cost per ride in each city type, average fare per person/driver, and cummulative fares by city type. In general, "Urban" cities tended to bring in more money because they had more people, while "Rural" cities had a lower total fare because of their smaller population sizes. In the results to come, I will specifically state the findings for each of these results.

## Results
Using Python, I was able to create a table displaying the total rides, drivers, profits, and costs among the three major city types. From the data, we can see that the total number of rides in "Urban" cities amounts to 1,625 rides, while the total number of rides in the "Rural" was only 125. The total number of drivers in the "Urban" was also significantly higher than the amount in "Suburban" or "Rural" areas.  However, because of the lack of drivers in the less populated "Rural" and "Suburban" areas, the prices tended to be much higher in these areas because there were less people available to drive. The results of these findings are more specifically illustrated in the figure I developed below from the dataset.

### PyBer Summary
![PyBer_Summary_df](Analysis/PyBer_Summary_df.PNG)

One of the things I wanted to determine based off the datset was the shear amount of cashflow going on between each city type. In the results above, we saw that the "Urban" cities had many more drivers and total rides, but the smaller "Suburban" and "Rural" areas charged more per ride. To determine the total fare amount per city type, I developed the chart below to further analyze. Based on the chart below, we can see total fare in larger city types is much higher. "Urban" cities pull in a greater total fare than "Suburban" cities. These "Suburban" cities also pull in much more total fare than "Rural" cities.

### PyBer Fare Summary
![PyBer_fare_summary](Analysis/PyBer_fare_summary.png)

## Summary
Based on the data shown above, we can see that cities with more people tend to have more rides and bring in more total fares. However, drivers in smaller cities tend to make more money per ride than the driver in a larger city. To address these issues I have thought of several recommendations:

### Recommendations:
1) Decrease the number of total drivers in the "Urban" city, so that workers make more money per ride. These drivers should be able to charge more money because there will be a lower supply of drivers and a high demand for them. 

2) If the company is looking to expand, the more populous "Urban" areas are where people tend to use the ride system more often. Cornering the market in higher density populations will be a recipe for success in growing our business model in the eventual case of trying to merge, sell out, or continue growing.

3) Drivers in "Rural" and "Suburban" areas tend to make much more money per ride than the average driver in the "Urban". Creating a system which takes money from the driver each ride may work better for our company, as we can take more profit from each individual drive.
