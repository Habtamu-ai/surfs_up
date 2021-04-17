# Surfs_up
# Climate  Analysis to invest on surf shop
## Overview of the Project
The main purpose of this project is to analyze the weather before investing in a surfing shop in Oahu Island. To do this, we explore an SQLite weather database. The project also uses SQLAlchemy create_engine to connect to an SQLite database and automap_base() to reflect tables into classes and save a reference. We specifically want temperature data for June and December in Oahu, to determine if the surf and ice cream shop business is sustainable year-round.

## Results
 - June Temprature
 By using SQLAlchemy pandas and python, we manage to extract temperatures for June.The weconvers the retrived temprature data to a list. After creating a data frame we calculated the summary statistics of the temperature for June. Looking at below's summary statistics we have 1700 observations for June, and the average temperature is 74.94 °F. While the minimum is 64 °F and the maximum is 85 °F. The standard deviation is 3.2 while the first, second, and third quartiles are 73,75 and 77 respectively. The summary shows each temperature data are spread around the average mean.    
    
![June_Temp](https://user-images.githubusercontent.com/78656720/114898423-1249e580-9de0-11eb-8d63-bba9e6817031.png)

 - December Temprature
Our second task of the project was to do extract the temperature data from December and do a summary of statistics. Looking at the table below, we have 1517 observations. The average temperature in Oahu Island during December is 71 °F while the minimum is 56 and the maximum is 83 °F. The standard deviation is 3.7 while the first, second, and third quartiles are 71,74 and 74 respectively. The summary shows each average temperature is equal to the second quartile. which tells us the temperature in Oahu throughout the year is predictable and the variance is small.


![December_Temp](https://user-images.githubusercontent.com/78656720/114898494-2392f200-9de0-11eb-8582-cd5a7e6a3fee.png)

## Summary
The main purpose of this analysis is to do a climate analysis before investing in a surfing shop in Oahu Island. This project extracts the temperature data from the SQLite database and analyses the summary statistics in Oahu Island. The result from the two different months in the different seasons shows that the weather is very stable and has very low variation throughout the year. Based on our analysis we strongly recommend our client to invest in the surfing shop in Oahu since the business can run all year long without significant negative weather impact.
To do this, we explore an SQLite weather database. The project also uses SQLAlchemy create_engine to connect to an SQLite database and automap_base() to reflect tables into classes and save a reference. We specifically want temperature data for June and December in Oahu, to determine if th

