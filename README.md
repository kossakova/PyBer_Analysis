# PyBer ride-sharing servises analysis

## Overview of the analysis
On the first week of a new job as data analyst at PyBer, I was given an assignment to perform an exploratory analysis on data in some very large data in CSV files. PyBer is a Python based ride-sharing app company that values $2.3 billion. We wrote a Python script using Jupiter Notebook, Pandas library and Matplotlib. In this analysis we showcased the relationship between types on city, number of drivers and share riding fares, as well as the summary of total fares, riders and drivers by type of city.


## Results
We created a summary DataFrame and multiple-line graph of rides-sharing data to show the total weekly fares for each city-type. 
![pyber_summary_df](https://github.com/kossakova/PyBer_Analysis/blob/main/Screenshots/pyber_summary_df.png)

Our summary DataFrame consists of data for three cities: Rural, Suburban and Urban. We determined a total number of rides, drivers and fares, as well as the average fares per ride and average fares per driver for each city. Our summary DataFrame shows us that Urban city has the most significant total of fares out of all 3 different city types ($39,854), Rural on the other hand is the least with total fares of $4,327. Our findings also show as that Urban city has major number of drivers and rides. However, Rural city shows to surpass the Urban city prices for average fare per ride and driver, $55 compared to Urbans $16, this primarily has to do with a modest number of 78 drivers in Rural city. 

![PyBer_fare_summary](https://github.com/kossakova/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)

This multiline chart shows the total weekly of the fares for each type of city. We generated this multiple line plot by creating pivot chart, converting to datetime and filtering the data to show weekly summaries.  Jut like in the DataFrame our line chart reveals us that the Urban city’s fares for week are 2-3 times higher than Rural and Suburban cities.

## Summary
The analysis we provided will help PyBer improve access to ride-sharing services and determine affordability for underserved neighborhoods.  Based on analysis we came up with, we can share some recommendations to increase PyBer’s customer utilization among Suburban and Rural cities. 
- Increasing a number of drivers in Rural cities will help PyBer to provide more people ride-sharing services. 
- Relatively, increasing drivers will decrease fare prices in Rural and Suburban cities which will make PyBer more affordable in those areas.  
- Lastly, our analysis shows us that majority of PyBer’s services take place in Urban cities and improving ride-sharing services in those areas should be the major focus. 

Overall PyBer is very popular ride-sharing app in Urban and Suburban cities. 
