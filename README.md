# PyBer_Analysis
Colombia Data Week 5 Challenge, using matplotlib to visual ride sharing data.

## Overview of the analysis
The purpose of this analysis is to determine how ride sharing data varies by city type. The three city types are urban, suburban, and rural. ride sharing is more popluar in urban and suburban areas leading to a few trends; there are far more rides and drivers in urban cities and the fares are typically higher in rural areas per driver. Investing more money or resources in urban areas makes the most sense as the ride sharing programs are more robust and make more sense in densely populated areas.  


## Results
Dividing the data between the three city types allows for differences in ride sharing trends for those areas. The first table summarizes some statistics for each city type showing that there are far more drivers giving far more rides in urban centers. With only 79 drivers in rural areas those drivers have higher average fares. The table summarizes some key statistics to represent the differences in ride sharing trends between city types:

![Screen Shot 2022-05-14 at 11 52 13 AM](https://user-images.githubusercontent.com/99676466/168443120-153c6f08-c26b-495c-8d63-dfacbf702116.png)


The total fares therefore add up to the most money in urban centers due to the volume of rides with rural areas only producing around 7% of total fares and 125 rides to the 1,625 in urban areas. 

![Screen Shot 2022-05-14 at 11 49 30 AM](https://user-images.githubusercontent.com/99676466/168443041-eba45606-8368-4fe4-9914-4e2e0fe6238c.png)



![Screen Shot 2022-05-14 at 11 48 58 AM](https://user-images.githubusercontent.com/99676466/168443017-9c2983fa-e455-4b9c-81cd-374872f4286f.png)

The data can be broken down further to be viewed over time. Each week has different fare totals for each city type, though the rural fares stay more consistent week to week than the other two city types. Using a pivot table the data is displayed by weeks and city types:

![Screen Shot 2022-05-14 at 11 43 48 AM](https://user-images.githubusercontent.com/99676466/168442887-8b42c773-544a-4e06-9341-470521b69826.png)

A multiple line chart helps show the total fares by city type over time in 2019. There is an obivous spike in rides in all three city types at the end of February, likely related to President Day weekend travel or activities. 

![Screen Shot 2022-05-14 at 11 45 23 AM](https://user-images.githubusercontent.com/99676466/168442926-202e5012-0ff6-40a8-8d01-522c5bf18eb1.png)

## Summary
Three recommendations based on the analysis for addressing the disparities between the three city types are as follows:
1. While the average fare per driver is pretty high in rural areas, there are not enough rides overall to generate much in total fares. There are likely not enough people interested in ride sharing in rural areas, but suburban areas could see an increase in rides with some targeted marketing in that area.
2. It is recommended to inclrease rates a bit in urban centers where there is the most demand; this may further increase the number of drivers and total fares.
3. It is recommended that more data is collected to determine the average ride distance and incorporate this into decision making about the city types and disparities between rates and rides. 
