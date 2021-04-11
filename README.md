# World_Weather_Analysis
Module 6 World Weather Analysis

## Project Overview
Cities data was provided in order to use APIs to chose hotels for clients based on their weather preferences.

## Resources
Data Sources provided to analyze and minipulate included the cities.csv excel spreadsheet.

Software utilized for this study included: 
- Python 3.7.6 
- Conda 4.9.2 
- Jupyter Notebook 6.1.4
- Google Maps APIs
- Open Weather APIs

## Analysis and Workflow
Data for the math and reading scores were removed then we created district and school summary dataframes to manipulte the following:

- Top 5 and bottom 5 performing schools
- Average math score received by students in each grade level at each school
- Average reading score received by students in each grade level at each school
- School performance based on the spending per student
- School performance based on the size of the school
- School performance based on the type of school

The Jupyter notebooks (Python code) for the above analysis was worked through in the following files.

https://github.com/austin020269/School_District_Analysis/blob/main/PyCitySchools.ipynb
https://github.com/austin020269/School_District_Analysis/blob/main/PyCitySchools_Challenge_testing.ipynb

The Challenge at the end of the module which finakized results of the study is here:

https://github.com/austin020269/School_District_Analysis/blob/main/PyCitySchools_Challenge_final.ipynb


## Summary

Collect the Data

Use the NumPy module to generate more than 1,500 random latitudes and longitudes.
Use the citipy module to list the nearest city to the latitudes and longitudes.
Use the OpenWeatherMap API to request the current weather data from each unique city in your list.
Parse the JSON data from the API request.
Collect the following data from the JSON file and add it to a DataFrame:
City, country, and date
Latitude and longitude
Maximum temperature
Humidity
Cloudiness
Wind speed
Exploratory Analysis with Visualization

Create scatter plots of the weather data for the following comparisons:
Latitude versus temperature
Latitude versus humidity
Latitude versus cloudiness
Latitude versus wind speed
Determine the correlations for the following weather data:
Latitude and temperature
Latitude and humidity
Latitude and cloudiness
Latitude and wind speed
Create a series of heatmaps using the Google Maps and Places API that showcases the following:
Latitude and temperature
Latitude and humidity
Latitude and cloudiness
Latitude and wind speed
Visualize Travel Data

Create a heatmap with pop-up markers that can display information on specific cities based on a customer's travel preferences. Complete these steps:

Filter the Pandas DataFrame based on user inputs for a minimum and maximum temperature.
Create a heatmap for the new DataFrame.
Find a hotel from the cities' coordinates using Google's Maps and Places API, and Search Nearby feature.
Store the name of the first hotel in the DataFrame.
Add pop-up markers to the heatmap that display information about the city, current maximum temperature, and a hotel in the city.
