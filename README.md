# World_Weather_Analysis

TASK: Collect and Analyze weater data across cities worldwide

PURPOSE: PlanMyTrip will use the data to recommend ideal hotels based on clients weather preferences

METHOD: Create Pandas DataFrame with 500 or more of the worlds unique cities and their weather data in real time. This process will entail collecting, analyzing and visualizing data

 1. Collect the data:
  - Use NumPy module to generate more than 1500 random latitudes and longitudes
  - use the citypy module to list the nearest city to the latitiudes and longitudes
  - Use the OpenWeatherMap API to request the current weather data from each unique city in your list
  - Parse the JSON data from the API request
  - Collect the following data from the JSON file and add it to a dataframe 
     - City, Country and Date
     - Latitude and Longitude
     - Maximum temperature
     - Humidity
     - Cloudiness
     - Wind Speed
 
 2. Exploratory Analysis:
  - Create scatter plots of the weater data for the following comparisons:
     - Latitude vs Temperature
     - Latitude vs Humidity
     - Latitude vs Cloudiness
     - Latitude vs Wind Speed
  - Determine the correlations for the following weather data:
     - Latitude and Temperature
     - Lat and Humidity
     - Lat and Cloudiness
     - Lat and Wind Speed
  - Create a series of heat maps using the google maps and places API that showcases the following:
     - Lat and Temp
     - Lat and humidity
     - Lat and cloudiness 
     - Lat and wind speed

 3. Visualize Travel Data: Create a heatmap with pop-up markers that can display information on specific cities based on a customers travel preferences:
  - Filter the Pandas DataFrame based on user inputs for a minimum and maximum temperature
  - Create a heatmap for the new DataFrame
  - Find a hotel from the cities coordinates using Google Maps and Places API, and Search Nearby feature
  - Store the name of the first hotel in the DataFrame
  - Add pop-up markers to the heatmap that display information about the city, current max temp, and a hotel in the city