# Surfs_up
# Climate  Analysis to invest on surf shop
## Overview of the Project
The main purpose of this analysis is is to do a climate analysis before investing in surfing shop in Oahu Island. To do this, we explore a sqlite weather database. The project  also use SQLAlchemy create_engine to connect to sqlite database and automap_base() to reflect tables into classes and save a reference. We specifically want temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round.

## Results
 - June Temprature
    By using SQLAlchemy pandas and python, we manage to extract tempratures for the month of June.The weconvers the retrived temprature data to a list. After creating a data frame we calculated the summary statistics of the temprature for the month of June. Looking at below's summary statistics we have 1700 observtion for month of June, and the average temprature is 74.94 °F. While the minimum is 64 °F and the maximum is 85 °F.The standard deviation is 3.2 while the first, secodn, and third quartiles are 73,75 and 77 respectively.The summary shows each temprature data are sperad around the average mean.    
    
![June_Temp](https://user-images.githubusercontent.com/78656720/114898423-1249e580-9de0-11eb-8d63-bba9e6817031.png)

 - December Temprature
 Our second task of the project was to do extract the temprature data from the month of Decembcer and do a summary statistics. Looking at the table below, we have 1517 obseravtions. The average temprature in Ouahu Island during December is 71 °F while the minimum is 56 and the maximum is 83 °F. The standard deviation is 3.7 while the first, secodn, and third quartiles are 71,74 and 74 respectively.The summary shows each the average temprature is equal with the second quartile. which tells us the the temprature in Oahu through out the year is predictable and the varuaniance is small.


![December_Temp](https://user-images.githubusercontent.com/78656720/114898494-2392f200-9de0-11eb-8582-cd5a7e6a3fee.png)

## Summary
The main purpose of this analysis is is to do a climate analysis before investing in surfing shop in Oahu Island. This project extract the temprature data from the sqlite database and analyse the the summary statistics in Oahu Island. The result from the two different months in different season shows that the weather is very stable and has very low variation through out the year. Based on our analysis we strongly recommend our client to invest in the surfing shop in Oahu since the business can run all year long with out significant negative weather impact.
To do this, we explore a sqlite weather database. The project  also use SQLAlchemy create_engine to connect to sqlite database and automap_base() to reflect tables into classes and save a reference. We specifically want temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round.

