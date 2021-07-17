# WeatherPy Analysis

# Overview

Creating a PlanMyTrip app by retrieving weather data, creating a customer travel desinations map, and creating a travel itenerary map. Travelers will be able to input statments to filter data for their weather preferences, which will be used to identify potential travel destinations and nearby hotels. From the list of potential travel destinations, travelers can choose four cities to create a travel itenerary. Finally, using the Google Maps Directions API, we will create a travel route between the four cities along with a marker layer map.


## Process:
### Deliverable 1: Retrieve Weather Data

Step 1 - Generate a set of 2,000 random latitudes and longitudes

Step 2 - Retrieve the nearest city

Step 3 - Perform an API call with the OpenWeatherMap

Step 4 - Retrieve the current weather description for each city

Step 5 - Create a new DataFrame containing the updated weather data

### Deliverable 2: Create a Customer Travel Destinations Map

Step 1 - Create input statements to retrieve customer weather preferences

Step 2 - Use those preferences to identify potential travel destinations and nearby hotels

Step 3 - Show those destinations on a marker layer map with pop-up markers

### Deliverable 3: Create a Travel Itinerary Map

Step 1 - Use the Google Directions API to create a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations

Step 2- Create a marker layer map with a pop-up marker for each city on the itinerary

## Resources:
Sources: OpenWeatherMap, GoogleMaps

Software: Python 3.7.6, Conda 4.10.1

Environment: Jupyter Notebook

Dependencies: Pandas, Matplotlib, Numpy, Citipy


# Results:
### Deliverable 1: Retrieve Weather Data: 
* Generated a [DataFrame](https://github.com/corispade/World_Weather_Analysis/blob/main/Weather_Database/WeatherPy_DataFrame.png) with random cities, including all necessary information such as location, maximum temperature, percent humidity, percent cloudiness, wind speed and weather description. 
* Travelers can use this data to identify potential travel destinations based on weather preferences.

### Deliverable 2: Create a Customer Travel Destinations Map
* Identified travelers weather preferences
* Within preferences, we found the nearest hotel and added to DataFrame
* Generated a [map](https://github.com/corispade/World_Weather_Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.png) with pop-up markers to show hotel name, city, country and current weather description.

### Deliverable 3: Create a Travel Itinerary Map
* Generated a [map](https://github.com/corispade/World_Weather_Analysis/blob/main/Vacation_Itenerary/WeatherPy_travel_map.png) to show the driving route between 4 selected cities in Japan.
* Generated a [map](https://github.com/corispade/World_Weather_Analysis/blob/main/Vacation_Itenerary/WeatherPy_travel_map_markers.png) with pop-up markers to show hotel name, city, country and current weather description for those 4 selected cities in Japan.


# Summary:
Travelers can use this app to identify travel destinations based on their desired weather conditions, find the nearest hotels, current weather information and directions to other nearby cities. 