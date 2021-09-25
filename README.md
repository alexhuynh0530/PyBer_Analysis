# An Analysis of Ride-Sharing Data Using Python

## Overview of Project

### Purpose

This is an analysis of ride-sharing data given by PyBer, a python based ride-sharing app company. We use the data using pandas libraries, Jupyter notebook, and matplotlib to create a variety of charts that showcase relationships between types of cities and number of drivers and riders, as well as, the percentage of total fares, riders, and drivers by type of city. The analysis and visualizations we produce will help PyBer access ride-sharing services and determine affordability for underserved neighborhoods.
 
In addition, we will describe the differences in ride-sharing data among the different city types and provide business recommendations to the CEO for addressing any disparities among the city types.

## Results

### Differences in ride-sharing data among the different city types

As seen in the figure below, among the different 3 city types (Rural, Suburban, and Urban), urban cities had the most total rides, total drivers, and total fares while rural cities had the least in all 3 categories. However, the opposite correlation is seen with average fare per ride and average fare per driver where urban cities have the lowest average in both categories and rural cities have the highest.

![pyber_summary_df.png](https://github.com/alexhuynh0530/PyBer_Analysis/blob/main/Resources/pyber_summary_df.png)

Looking at the multiple-line chart below of total fares by city type from January 2019 to April 2019, you can see that urban cities had the highest total fares for all 4 months while rural cities had the lowest, which matches our analysis from the chart above. You can also see that the third week of February had a peak in fares from all city types, with the exception of rural cities having a slightly higher peak at the beginning of April. The beginning of the year seems to be the lowest point for both urban and suburban cities with suburban cities having another equally low point after the first week of April. For rural cities, the lowest point can be seen after the first week of January and the second week of February. 

![PyBer_fare_summary.png](https://github.com/alexhuynh0530/PyBer_Analysis/blob/main/Resources/PyBer_fare_summary.png)

## Summary

In summary, here are 3 business recommendations for addressing any disparities among the city types:

- Adding more drivers concentrated in urban areas since they receive more traffic, furthermore you could analyze specific cities within city types to see high traffic areas to add more drivers in those areas as well.
- Lower fare prices for rural cities to increase the incentive of using ride-sharing services more often.
- Price increases in peak seasons coupled with promotions to draw in customers to use PyBer during those peak weeks.

