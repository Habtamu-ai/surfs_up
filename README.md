# Surfs_up
# Climate  Analysis to invest on surf shop
## Overview of the Project
The main purpose of this analysis is is to do a climate analysis before investing in surfing shop in Oahu Island. To do this, we explore a sqlite weather database. The project  also use SQLAlchemy create_engine to connect to sqlite database and automap_base() to reflect tables into classes and save a reference. We specifically want temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round.

## Results
 - June Temprature
    By using SQLAlchemy pandas and python, we manage to extract tempratures for the month of June.The weconvers the retrived temprature data to a list. After creating a data frame we calculated the summary statistics of the temprature for the month of June. Looking at below's summary statistics we have 1700 observtion for month of June, and the average temprature is 74.94 °F. While the minimum is 64 °F and the maximum is 85 °F.
    
    
 

![June_Temp](https://user-images.githubusercontent.com/78656720/114898423-1249e580-9de0-11eb-8d63-bba9e6817031.png)




 - December Temprature

![December_Temp](https://user-images.githubusercontent.com/78656720/114898494-2392f200-9de0-11eb-8582-cd5a7e6a3fee.png)

There is a bulleted list that addresses the three key differences in weather between June and December.
## Summary
There is a high-level summary of the results and there are two additional queries to perform to gather more weather data for June and December. 
