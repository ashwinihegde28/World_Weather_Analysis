# World_Weather_Analysis
Weather Analysis with Python APIs

# Project Overview
In this project, we intend to collect, analyze, and visualize weather data across cities worldwide, in addition to providing travelers with a tool that will allow them to select a destination based on the weather. Using Google Maps Directions API, create a route between the four cities as well as a marker layer map.

## Main Objective
1. Perform tasks using new Python libraries and modules.     
    Pandas, gmaps, requests, numpy, random, matplotlib, timeit, scipy, citipy, datetime, time
2. Retrieve and use data from an API "get" request to a server.
3. Retrieve and store values from a JSON array.
4. Use try and except blocks to resolve errors.
5. Write Python functions.
6. Create scatter plots using the Matplotlib library, and apply styles and features to a plot.
7. Perform linear regression, and add regression lines to scatter plots.
8. Create heatmaps, and add markers using the Google Maps API.

## Tools Used
Python, citipy, Pandas, Matplotlib, SciPy, Google Maps API, Google Places API, OpenWeatherMap API, Jupyter Notebook.

## Summary

### Retrieve the Weather Data
An API was established with OpenWeatherMap and a DataFrame was created to get the initial list of potential cities. 
![Weather Data](https://github.com/ashwinihegde28/World_Weather_Analysis/blob/main/Weather_Database/resources/cityDataframe.PNG)

### Create a Customer Travel Destinations Map
After prompting the beta testers for their minimum and maximum temperature preferences, the data frame was cleaned for null hotel entries and empty rows.  Markers and pins were created for the remainder of the hotels. 
![Destinations Map](https://github.com/ashwinihegde28/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.PNG)

### Create an Itinerary Map
The list was narrowed down to 4 cities in the same country and a travel map was created. 
![Itinerary Map 1](https://github.com/ashwinihegde28/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.PNG)

Makers were added to the map of four cities. 
![Itinerary Map 2](https://github.com/ashwinihegde28/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.PNG)
