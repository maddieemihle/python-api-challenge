# **Python-API-Challenge**

## Background
In this assignment, I was tasked with looking at two deliverables, WeatherPy and VacationPy, in order to visually analyze how the weather changes as the equator is approached. The results of this analysis were used to predict the most pleasant vacation locations. The skills learned using Python requests, APIs, and JSON were used to help manipulate the data given. 

All results can be found in the API-Callenge folder under WeatherPy. 

### Part 1: WeatherPy
In this section, I created a Python script to visualize the weather of over 500 cities of varying distances from the equator. I used the Citipy Python library, the [OpenWeatherMap API](https://openweathermap.org/api), and the problem-solving skills learned to create a representative model of weather across cities. 

My overall objective was to build a series of scatter plots to showcase the following relationships: 
* Latitude vs. Temperature (F) 
* Latitude vs. Humidity
* Latitude vs. Cloudiness
* Latitude vs. Wind Speed

Next, I computed the linear regression for each relationship between the plots of the Northern Hemisphere and the Southern Hemisphere. The relationship between latitude and other variables is an important aspect of climatology. Latitude is the distance north or south of the equator and significantly influences a city’s climate. The further discussion explored the linear relationship between city latitude and other variables was given using linear regression analysis. The results were broken down and analyzed to discuss the linear relationship and any correlation between the following: latitude and maximum temperature, latitude and humidity, latitude and cloudiness, and latitude and wind speed. 

### Part 2: VacationPy

In this section, I used weather data skills to plan future vacations using Jupyter Notebooks, geoViews Python library, and the [Geoapify API](https://apidocs.geoapify.com/docs/places/). Map visualizations were created to display a point for every city in the DataFrame and the size of the point to represent the humidity in each city. Next, the DataFrame was narrowed to find the ideal weather condition and hotel within a specific range (10,000 meters). Another map visualization was created to show this data and the respective points. 

## Methods Used:
* Python 
* APIs 
* Jupyter Notebook
* Linear Regression
* R-Values
* GeoViews

## Software Used: 
Coding was performed via Visual Studio Code using a Jupyter environment, with the dependencies: 
* import matplotlib.pyplot as plt
* import pandas as pd
* import numpy as np
* import requests
* import time
* from scipy.stats import linregress
* import os
* from pprint import pprint
* import hvplot.pandas
* import json 

## Refrences
Data for this dataset was given by _edX Boot Camps LLC,_ and is intended for educational purposes only. API keys were provided by OpenWeatherMap API (_2012—2025 OpenWeather; All Rights Reserved_) and Geoapify API.
