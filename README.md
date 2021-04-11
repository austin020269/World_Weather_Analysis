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

## Analysis/Workflow/Output

Deliverable 1 (code : https://github.com/austin020269/World_Weather_Analysis/blob/main/Weather_Database/WeatherPy_Database.ipynb)
Our code was used to create a spreadsheet containing cities and their current weather information including: 
- Latitude and longitude
- Maximum temperature
- Percent humidity
- Percent cloudiness
- Wind speed
- Weather description (for example, clouds, fog, light rain, clear sky)

![alt text](https://github.com/austin020269/World_Weather_Analysis/blob/main/Weather_Database/Weather_Database_csv.PNG)

Deliverable 2 (code : https://github.com/austin020269/World_Weather_Analysis/blob/main/Vacation_Search/Vacation_Search.ipynb)
We used input statements to retrieve customer weather preferences to identify potential travel destinations and nearby hotels.  The search was run according to the answers of the two questions below.

1. What is the minimum temperature you would like for your trip? 0
2. What is the maximum temperature you would like for your trip? 100

Then:
- Filter the dataframe according to the answers from 1 and 2 to create a new dataframe.
- Check for empty rows and drop any to create a clean dataframe.
- Create a hotel dataframe with the desired information to include the Hotel Name column.
- Set parameters to search for hotels with 5000 meters.
- Iterate the hotel dataframe and set up the base URL to retrieve JSON data
- Get the first hotel from the results and store the name, if a hotel isn't found skip the city.
- Drop rows with no hotel and create output file to poulate the figure as shown below.

![alt text](https://github.com/austin020269/World_Weather_Analysis/blob/main/Vacation_Search/Deliverable%202%20out.PNG)

![alt text](https://github.com/austin020269/World_Weather_Analysis/blob/main/Vacation_Search/Hotel_listings.png)

Deliverable 3 (code: https://github.com/austin020269/World_Weather_Analysis/blob/main/Vacation_Itinerary/Vacation_Itinerary%2Cipynb.ipynb)




