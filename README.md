# Python-API-Project

## Background
This is a detailes annalysis of the weather 500 random cities based on latitude and longitude using a series of successive API calls. To accomplish this, we'll be utilizing a simple Python library, the OpenWeatherMap API, and a little common sense to create a representative model of weather across world cities.

## Part 1- WeatherPy

### Obsevable Trends
* From the analysis we can see that the highest temparature is found a 0 latitude and temperature drop is affected by latitude increase or decrease. This affects equatorial regions as they receive direct sunlight

* Southern Hemisphere temparatures tend to be slightly milder in comparison to those at similar latitudes in the Northern Hemisphere. This could be attributed tothe Southern Hemisphere having significantly more ocean and much less land.

* Also, Lattitude has no considerable impact on wind speed. The speed of the wind is controlled by the strength of the air pressure gradient, the stronger the pressure gradient the higher the wind speed.

#### 

## Part 2- VacationPy
This Jupyter notebook will work with weather data to plan future vacations. We will use jupyter-gmaps and the Google Places API to find cities from the WeatherPy notebook results that have the ideal weather for a vacation spot. Then we will plot out markers on a map of the world and find a hotel we can stay at in those cities.

Create a heat map that displays the humidity for every city from the part I of the homework.
![alt text](https://github.com/Claude-Hanfou/Python-API-Analysis/blob/main/Images/heat_map.png "Heat Map")


In the second map we narrowed down  down the DataFrame to find an ideal weather condition with the following properties: max temperature lower than 80 degrees but higher than 75, wind speed less than 10 mph and Zero cloudiness. The cities extracted were later used to pinned hotels on the map within 5000 meters of their coordinates.
![alt_text](https://github.com/Claude-Hanfou/Python-API-Analysis/blob/main/Images/hotel_map.PNG "Hotel Map")


