# Ciclistic Case Study 🚲

This is the Capstone Project for the Google Data Analytics Professional Certificate. 
In this study I'll analyze historical data from a bike-shared company based in Chicago. The main goal is to undertand how different customer groups use Cyclistic differently.

## Summary

* [Data sources](#-data-sources)
* [Insights](#-insights)
* [Files](#-files)
* [Recommendations](#-recommendations)

## 💻 Data Sources

There are two main datasets I'll use for this project. 

1.Cyclistic historical data, that has detailed information about rides done with their service.
2.An auxiliary database with stations names and location based on Divvy Stations.

Bellow you can see a brief diccionary for the Cyclistic data:
- Ride_id: unique ride identifier
- Rideable_type: (varchar) Bike type - Docked, Electrical or Classic
- Started_at: (date time) Ride start date and time
- Ended_at: (date time) Ride end date and time
- Start_station_name: Ride start station name
- Start_station_id: Ride start station identifier
- End_statio_name: Ride end station name
- End_statio_id: ride end station identifier
- Start_lat: ride start station latitude
- Start_long: ride start station latitude longitude 
- End_lat: ride endstation latitude
- End_long: ride end station longitude
- Member_casual (varchar): Membership type - casual or member

You can also access full cyclistic dataset [here](https://divvy-tripdata.s3.amazonaws.com/index.html), and the Divvy stations dataset [here](https://data.cityofchicago.org/Transportation/Divvy-Bicycle-Stations/bbyy-e7gq/data_preview).

## 💡 Insights

Some of the tools I used for this project were Microsoft Excel, R and PowerBI. After checking the data and understading it better I could draw some initial insights:

- Annual members (users that bought the annual membership) have a lot more rides than casual riders (users that bought single-rides or full day passes).
- Summer months has the most number of rides compared to other seasons.

Other insights and my final considerations can be seen on the notebook provided.

## 🗂️ Files 

This repository has  the following files/folders: 
- Data : including both raw .csv files and the final cleaned file used for analysis
- Notebook: the R Notebook done in Google Colab with codes  I've done to clean and analyze
- Visualization: includes the .pbix file with the visuals I've done for the analysis and presentation.
- Presentation: the final presentation file to be delivered to the stakeholders, both marketing and executive team.

## ✅ Recommendations

Based on the analysis done a few recomendations I would give to the team is:
- Set most part of the marketing budget on campaigns from May to September, that has most rides.
- Use the fact that most rides are done on the coast of the city to increase marketing campaigns there, targetting mostly casual riders.

💜 Made by Gabriela Klitzke
