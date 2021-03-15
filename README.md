# World_Weather_Analysis

## Overview of Project

### Purpose
Jack loves the PlanMyTrip app. Beta testers love it too. And, as with any new product, they’ve recommended a few changes to take the app to the next level. Specifically, they recommend adding the weather description to the weather data you’ve already retrieved in this module. Then, you'll have the beta testers use input statements to filter the data for their weather preferences, which will be used to identify potential travel destinations and nearby hotels. From the list of potential travel destinations, the beta tester will choose four cities to create a travel itinerary. Finally, using the Google Maps Directions API, you will create a travel route between the four cities as well as a marker layer map.

### Methodology

Generated a set of 2,000 random latitudes and longitudes, retrieved the nearest city, and performed an API call with the OpenWeatherMap. In addition to the city weather data gathered, used my API skills to retrieve the current weather description for each city. Then, created a new DataFrame containing the updated weather data.

Used input statements to retrieve customer weather preferences, then used those preferences to identify potential travel destinations and nearby hotels. Then, displayed those destinations on a marker layer map with pop-up markers.

Used the Google Directions API to create a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations. Then, created a marker layer map with a pop-up marker for each city on the itinerary.

## Results

### Images for Reference

![Vacation_Map](WeatherPy_vacation_map.png)

![Itinerary Travel_Map.png](WeatherPy_travel_map.png)

![Travel_Map_Markers.png](WeatherPy_travel_map_markers.png)
