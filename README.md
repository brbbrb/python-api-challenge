## python-api-challenge

# Georgia Tech Python API Homework

This two-part project explores weather data from the OpenWeatherMap API and uses it to plan a hypothetical vacation with ideal weather conditions.

## WeatherPy
A random list of coordinates was created and assigned to the closest city with citipy. Each city in the list was explored using OpenWeatherMap API to determine current weather conditions. Then, the data was further explored to investigate the the following relationship:
* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

A graph for each relationship was created, followed by analysis. The relationship between the variables was then broken down by hemisphere and regression analysis was run on each graph.

## Vacationpy
Using the city data from the WeatherPy part, gmaps was utilized to visualize humidity percentages on the world map. After determining personal ideal weather conditions, and removing cities that do not meet the conditions, I used Google Map's API to search for the closest hotel to each city, and added that layer to the gmaps figure. 

The end result is an interactive world map featuring a humidity heatmap and markers indicating the closest hotel in each city with ideal weather conditions.