# python-api-challenge
Python API Weather and Vacation Challenge

Jeremy Hamley

This assignment is designed to practice making API calls and is divided into two sections: 

### Section One:   WeatherPy

 - Select 500+ cities at random across the entire globe using the Python library CityPy
 - Using the list of cities generated, collect geographical coordinates and weather statistics for each city
 - Create scatter plots that plot the following:
      - Temperature (F) vs. Latitude
      - Humidity (%) vs. Latitude
      - Cloudiness (%) vs. Latitude
      - Wind Speed (mph) vs. Latitude
 
 - Then, divide the data into Northern and Southern Hemisphere.  
  - With each hemisphere's data set, create the same scatter plots as above, calculate the linear regression, and add the linear regression to each scatter plot.  
     
    - Northern Hemisphere - Temperature (F) vs. Latitude
    - Southern Hemisphere - Temperature (F) vs. Latitude
    
    - Northern Hemisphere - Humidity (%) vs. Latitude
    - Southern Hemisphere - Humidity (%) vs. Latitude
    
    - Northern Hemisphere - Cloudiness (%) vs. Latitude
    - Southern Hemisphere - Cloudiness (%) vs. Latitude
    
    - Northern Hemisphere - Wind Speed (mph) vs. Latitude
    - Southern Hemisphere - Wind Speed (mph) vs. Latitude
    

### Section Two:   VacationPy

 - Using the dataframe of cities and weather recorded in Section One (WeatherPy), create a Google map with a heat map that display the humidity for each city in the list
 - Narrow the list of cities to vacation destinations based on each city's weather conditions.  I narrowed my search by:  
      - Max temperature between 73 (F) and 95 (F)
      - Humidity - less than 80%
      - Wind speed - less than 20 mph
      - Cloudiness - less than 50%
      - filtered by a list of countries of interest
      
  - Use Google Places API to find a hotel within 5000 meters of each destination city on the refined list.
  - Drop a pin (marker) on top of the heat map created earlier with an Info box that lists the name of the hotel, the city, and the country.
      
      







