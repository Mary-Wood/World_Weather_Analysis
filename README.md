# World_Weather_Analysis

## Purpose 
The purpose of this challenge was to be able to enable users to be to input minimum and maximum weather data and have the code give them a series of locations that would match that criteria and also give them a description of the weather at that location. The data will also give the users a hotel that is closest to that location. Finally, the last code was to select four nearby cities and map the directions between those locations. This was done using gmaps and openweathermap API calls as well as libraries: pandas, matplotlib, and numpy. 

## Results 
* world_data shows a series of scatterplots showing the relationship between latitude and maximum temperature, humidity, cloudiness, and windspeed. 
* Weather_Database used libraries matplotlib, pandas, numpy, requests, citipy and datetime, and input openweathermap current weather data via API call to make a CSV file compiling the city, county, maximum temperature, humidity, cloudiness, wind speed, and current description based on latitude and longitude coordinates. 
* Vacation_Search allows users to input a minimum and maximum desired temperature and be matched with a variety of locations that match that criteria. Using pandas, requests, and an API call to gmaps, this code takes the CSV file made in Weather_Database and outputs CSV files and a map of locations that could be desirable to users based on the input critera. ![Vacation Map](https://github.com/Mary-Wood/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.png)
* Vacation_Itinerary uses libraries pandas, requests, numpy, gmaps, and gmaps.datasets. It selects four cities, shows markers with details on the four locations and then maps a trip between those points, starting and ending at the same city. 
![Map Markers](https://github.com/Mary-Wood/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.png)
![Map Trip](https://github.com/Mary-Wood/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.png)