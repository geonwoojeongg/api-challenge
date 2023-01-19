# API-challenge
Summary: This two-step project contains various data of weathers and climates of various cities by requesting an api from OpenWeatherMap API and Geoapify API, and by analyzing them to see which city is the best vacation destination. 

## WeatherPy
This file works with the api pulled from OpenWeatherMap API to find random cities across the globe to make a dataframe containing each city's coordination, temperature, humidity, cloudiness, wind speed, and measured date. Each information is then visualized through graphs with latitude as the fixed independent variable in order to figure out whether temperature, humiity, cloudiness, and wind speed have any correlation with latitude. In brief, only the temperature of cities in the northern hemisphere has a strong negative correlation with latitude, whereas other variables showed little to no relation.

## VacationPy
Using Geoapify API, it further analyzes the data retrieved by WeatherPy to see which cities are worth going. The visualization of the cities on the world map enables the reader to easily see which cities have been inclued in the data. It then filters out the cities that have inadequate climates for a vacation, only leaving places with temperatures ranging from 20C to 30C, with relatively less wind speed and no clouds. The file also searches nearby hotels within 10,000 meters to choose what lodging options I have if I go.
