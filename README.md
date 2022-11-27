

# PyBer_Analysis

#### Analysis on ridesharing data using Pandas, NumPy, and Matplotlib Libraries. 

## Overview of the Analysis
The purpose of this project is to produce a complete analysis with visualizations to help PyBer improve access to ridesharing services and determine affordability for underserved neighborhoods. 
For this project, I will be working with ridesharing data from different cities located in urban, suburban, and rural areas. 

## Resources
- Data sources:
  - city_data.csv
  - ride_data.csv

- Software used are:
  - Python 3.8.1
  - Jupyter Notebook
  - Pandas, NumPy, Matplotlib, and SciPy Libraries 

## Results

First and foremost, ridesharing services are priced based on demand and supply. Obviously, there are more rides and drivers in urban cities as there are more people concentrated in the big cities than suburban and rural communities respectively. 

![Pyber_Summary](https://github.com/Adpetfem83/Pyber_Analysis/blob/main/Images/Pyber_Summary.png)


The above result shows that even though rural areas have less rides, their fares are relatively more expensive. Also, there are less drivers available in this type of cities. Suburban cities are in the midpoint between the other two. Their fares are average price and their number of rides range in between 10 to 25 rides per city. Again, they have more drivers available than rural areas but less than urban cities. And lastly, urban cities happen to have lower fare prices but a lot more rides.


The total number of rides from the urban, suburban and the rural areas is 2,375, and 68.4% of the total rides and the market, come from urban areas, only 5.3% come from rural areas. Additionally, urban areas happen to have more drivers than the rural areas. In fact, urban areas have 8 times more drivers than rural. The presence of drivers in the suburban areas is also not as large as urban. There is clear imbalance in driver distribution across city types. 



As for fares, urban areas have the majority with a 63%. Suburban and rural still have a relatively big part of the whole as their fares are more expensive.  

![Fares_by_City_Type](https://github.com/Adpetfem83/Pyber_Analysis/blob/main/Images/Fare_by_city_type.png)

Meanwhile, the multi-line graph above shows the weekly fares for all three city types from January 2019 to April of the same year. The graph reveals that the sum of fares for urban cities was more than $1800 which is more than 3 times the max value for the rural cities. The sum of fares for suburban cities was less than $1500 throughout. Even though we concluded that the fares were more expensive in rural areas, this graph still happens to address that urban sum of fares was relatively a lot higher. This is because the sum of fares accounts for all the rides made during that time, we can then conclusively state that urban cities had a lot more drivers and rides. 

## Summary

In conclusion, some recommendations that could be made to PyBer are as follows:

#-In order to increase market presence in suburban and rural areas, PyBer needs to contract more drivers. As it can be seen from the summary table above, the suburban and rural areas have more rides than the drivers. The first recommendation would be to create incentives for drivers in these areas that can bring that count up. Assuming there is enough demand and the utilization rate for these current drivers is very high, having more drivers would increase revenue by a lot as fares are very highly priced in rural cities.
#-The second recommendation would consist on creating the same incentives but for suburban cities as their driver and ride counts is still opaqued by urban. Again, this would significantly increase revenue as fares are higher in suburban cities and having more rides would maximize profit.
#-Lastly, I would recommend to decrease the driver count in urban cities by a small amount as they account for almost 81% of the total PyBer drivers. It is important that we balance that percentage so that there are more drivers in the other areas, specially rural. By doing this, we would also bring the average fare price in urban areas higher as there might be less supply to cover for that large demand. Again, this would have to be a small change for the system not to collapse for not enough PyBers in urban cities. 
