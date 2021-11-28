# Air quality prediction
ML project

How next day’s air quality index (AQI) that can be predicted from pollutant substances and metrological factors? /n
 
Data collection:

There are three dataset being gathered for the project:

1. Air quality dataset (1) includes daily information about air quality substance as well as the AQI (Air Quality Index) and AQI_Bucket (Air Quality Index Bucket) for 26 cities of India from 2015 to 2020. This dataset is collected from India Center For Environmental Monitoring Portal. aqicn.org. 

2. Temperature dataset of Delhi (2) includes temperature, humidity, wind speed and wind direction from 2015 to 2021 of Delhi city only. This dataset is collected from aqicn.org and www.meteoblue.com.


3. Temperature dataset of 6 other cities (3) includes 6 different datasets of different cities in India in the first 14 days of October from 2018 to 2021. There are 6 cities with 6 different dataset  collected from www.meteoblue.com.


The idea is to merge Air quality dataset (1) and Temperature dataset of Delhi (2) to get the Delhi Air Quality dataset that include pollutant substance variables and metrological factor variables of Delhi from 2015 to 2020. This dataset will later be treated as Training dataset for modelling.

The Temperature dataset of 6 other cities (3) will be merged with Air quality dataset (1) to get a Cities Air Quality dataset that include pollutant substance variables and metrological factor variables of 6 different cities in India first 14 days of October from 2018 to 2021. This dataset will later be treated as Testing dataset for modelling.

Variables found for this challenge are the historical daily measurement of these air pollutant substances in the air:  PM 10, PM 2.5,  NO 2 (nitrogen dioxide) , O 3 (ground-level ozone), CO (carbon monoxide), SO 2 (Sulphur dioxide); and measurement of some metrological factors such as temperature, precipitation, humidity and wind speed. The number shown in the dataset are daily records of above-mentioned measurements
