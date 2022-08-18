## PyBer_Analysis

---

# Overview of the analysis: Explain the purpose of the new analysis.

The goal of this challenge is to provide ridesharing data visualizations for PyBer a ridesharing comapny, in order to promote access to ride-sharing services and determine affordability for underprivileged neighborhoods. In this project analyze all the rideshare data from January to early May of 2019 and create a compelling visualization for Pyber CEO.
The study is based on data obtained in the form of a CSV file from PyBer. This data has been processed using Python's Pandas to produce a summary dataframe as well as a chart generated using the information in the dataframe to visualize the data.

---

# Results: Using images from the summary DataFrame and multiple-line chart, describe the differences in ride-sharing data among the different city types.


![alt text](https://github.com/salvamike/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)
The multiple-line chart "Total Fare by City Type" further supports the PyBer Summary DataFrame by providing trends of total fares in rural, suburban, and urban cities between January 2019 and April 2019. The yellow trend shows how fares in urban cities totaled from around $1,600 to $2,300 from beginning to end during this five-month period. In contrast, the blue trend shows how fares in rural cities totaled around $300 from beginning to end during the same time period. The orange trend shows how the total fares in suruban cities fall in between urban and rural cities: around $700 to $1,300 from beginning to end during this time. The chart further demonstrates similar peak times in all these types of cities. One noteworthy peak in total fares among urban, suburban, and rural cities occurred sometime at the end of February 2019.

The above chart illustrates that the quantity of money made by the service is fairly steady over the time period studied (January to May). Urban cities generate the most total revenue, followed by suburban and rural locations. 

Based on all the data reviewed and for some obvious reasons most of the outcome is not surprising, given that cities are expected to generate more revenue because they have more inhabitants than suburban or rural locations.


![alt text](https://github.com/salvamike/PyBer_Analysis/blob/main/analysis/PyBerSummaryDF.png)
It appears that riders in rural cities pay on average almost $10 more for PyBer than riders in urban cities. The average fare per ride is about $35 in rural cities whereas the average fare per ride is about $25 in urban cities. Suburban cities' average fare per ride falls just in between - at about $31. While it may not be good news for riders in rural cities, it is a better market for drivers in this type of city. The average fare per driver is about $55 in rural cities, whereas the average fare per driver is about $17 in urban cities. Suburban cities' average fare per driver is about $40.

---

# Summary: Based on the results, provide three business recommendations to the CEO for addressing any disparities among the city types.

In order to reduce the disparity between Urban, Suburban and Rural cities, we recomend the following:

1. based on this initial approach, The Rural cities seem to be underserved, but it would be neccesary to perform a market study to confirm if there is enough demand in this market segment to justify investing in hiring more drivers. In addition to this subject, The Data for rural cities shows that the average fare per ride and average fare per driver is much higher than Suburban and urban cities.This can indicate that rural area based riders are taking trips over a longer distance. This can result in a majority of drivers being occupied with current trips and loss in potential revenue when there are peaks in business.

2. An analisys focusing on just the first third of the year might not be the best way to see a more clear picture, the study may gain from having extra data points that span the entire year and provide insights into yearly trends.

3. In addition to the above analysis, I would recommend obtaining more information about the demographics of those living the the three city types and additional two to five previous year city and ride data. This more likely will help to have a more clear path where the company is heading.
