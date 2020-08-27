# Taxi Demand Predictor per City Zone
* [1_Introduction](#1_Introduction)
  * [1_1_What is this?](#1_1_What-is-this)
  * [1_2_Why?](#1_2_Why)
  * [1_3_Why is relevant?](#1_3_Why-is-relevant)
* [2_What Data have I used?](#2_What-Data-have-I-used)

* [About me]

# 1_Introduction
The purpose of this README file is to give you a quick overview of the project and go through the necessary steps to run the app in your computer.<br>
**If you are a KSCHOOL teacher or just want to read the whole Project´s documentation in much more detail, go straight to the wiki page.**

## 1_1_What is this?
**Taxi Demand Predictor** is the Final Project I have developed as part of my Master in Data Science - KSCHOOL (2019-2020).

It is a machine learning app that predicts for the next three days how many passengers will request a taxi in Manhattan (New York). Predictions are made by city zone and in hourly periods.

## 1_2_Why?
If a taxi driver could know in advance (and with precission) which boroughs or areas are going to have the biggest demand, he could optimize his workday by driving only around those areas. He could choose whether to earn more money in the same time or save that time for his family/personal life. Either way, it will improve his life.

## 1_3_Why is relevant?
There has been a lot of debate and riots in the past year regarding how Uber is literally eating the traditional street hail taxi market. Taxi drivers are afraid that they cannot compete with the kind of on-demand fare-adjusted service Uber provide, based in cutting-edge technology.

I think that traditional taxi drivers should also make use of advance technology like this machine learning app in order to improve their service and profitability.

# 2_What Data have I used?
Yellow taxis are the only vehicles permitted to respond to a street hail from a passenger in all five NY boroughs. Thus, they are the target users of my app.<br>

I have downloaded the data from [NYC Open Data](https://opendata.cityofnewyork.us/), a free public data source of New York City.
Specifically **2019 data of Yellow Taxis**. You can download it from [here](https://data.cityofnewyork.us/Transportation/2019-Yellow-Taxi-Trip-Data/2upf-qytp), although you don´t need it to run this app.<br>

The dataset includes 17 fields (you can have a look at the [data dictionary here](https://data.cityofnewyork.us/api/views/2upf-qytp/files/4a7a18af-bfc8-43d1-8a2e-faa503f75eb5?download=true&filename=data_dictionary_trip_records_yellow.pdf)). I was only interested in:

* ``tpep_pickup_datetime``: The date and time when the meter was engaged.
* ``PULocationID``: TLC Taxi Zone in which the taximeter was engaged. These id's correspond with one of these city zones:

<img src="https://github.com/angelrps/MasterDataScience_FinalProject/blob/master/img/taxi_zone_map_manhattan.jpg" width="400">

Other data sources:
- [Polygon shapefile](https://archive.nyu.edu/handle/2451/36743): Represents the boundaries zones for taxi pickups as delimited by the New York City Taxi and Limousine Commission (TLC).
- Weather (precipitation forecast): scraped from [www.wunderground.com](https://www.wunderground.com/hourly/us/ny/new-york-city)

## 3. Methodology and Tools
* Jupyter Notebook as a workframe.
* Python for data cleaning, engineering and modelling.
* Matplotlib, Seaborn, Bokeh and Altair for data analysis and graphic representation.
* Selenium Webdriver for web scraping.
* Streamlit for webapp front-end.

machine learning techniques used, statistical methodologies
## 4. Summary of main results
## 5. Conclusions
After all the work is done, what can you say about how the problem was resolved
## 6. User manual for frontend
## 7. What do you need to run the project?
### Notebooks
### About me, credits, thanks.
[<img src="https://github.com/angelrps/MasterDataScience_FinalProject/blob/master/img/linkedin-icon.jpg" width="25" height="25" title="Github Logo">](https://www.linkedin.com/in/angelruizpeinado/) [Angel Ruiz-Peinado](https://www.linkedin.com/in/angelruizpeinado/)
