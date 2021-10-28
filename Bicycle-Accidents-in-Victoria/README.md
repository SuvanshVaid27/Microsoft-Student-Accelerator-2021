# Road Crash Statistics for Bicycle Accidents in Victoria

* Source of data: https://discover.data.vic.gov.au/dataset/crash-stats-data-extract

* Problem Domain: Health 

## Problem Space

In 2019, 266 people didn’t make it home after losing their lives on Victoria’s roads. Around 8,000 Victorians were hospitalised with serious injuries and a further 12,000 were injured. This is a big number, but I think this is an emotive issue that doesn’t translate into economics for most people.

__Crashes leave lasting impressions on friends and families and have far reaching social and community impacts.__

In addition, Victoria has also seen a growth in cycling numbers but it has come with a heavy cost. In 2020 alone, bicycle accident fatalities grew 27 percent from the preceding year.

This project aims to answer some of the questions related to bicycle accidents, from the detailed road crash data by making use of the powerful data exploration tool - Power BI. 

## Data Preparation

The dataset is first downloaded as a zip file and prepared for visualisation, in Python. After merging the relevant tables and appplying data transformations to select only the bicycle accidents, the final dataset is stored as __crash_master__. 

## Power BI Dashboard Snapshot

<img src="https://github.com/SuvanshVaid27/Power-BI/blob/main/dashboard.jpg" width="1000" height = "1400" title="snapshot">


## Key Insights generated

* Victoria has reported more than __20K__ bicycle accidents since 2006. 
* Highly populated suburbs such as __Melbourne, Richmond, etc__ reported the most number of bike accidents. 
* __Morning__ (08:00 - 09:00) and __Evening__ (16:00 - 18:30) are the most accident-prone hours throughout victoria. 
* Almost __2 males__ were involved in a bike accident for a __single female__. 
* Most (93%) of the accidents were reported in __clear__ weather conditions, however __rain__ (5%) was the second most common weather condition. 
* Most (74%) of the accidents were reported in __day__ light while 10% being during Dusk/Dawn and the other 10% during the night (with street lights on). 
* The __weekdays__ had more reported accidents as compared to the __weekends__. 
* Speed Zones __40,50 and 60__ together reported almost 80% of the bike accidents. 
* __'Collision'__ was the most common type of accident type, with 'fell from vehicle' being the second most common one. 
* There were more reported accidents at __intersections__ as compared to __non-intersections__ and __T, cross__ intersections were the most accident-prone. 

