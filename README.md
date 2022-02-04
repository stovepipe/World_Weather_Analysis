# World_Weather_Analysis
  Using weather and map API's to determine the most ideal vacation destinations

## WeatherPy Project

  This project consisted of generating random latitudes and longitudes, gathering weather data from an api for each coordinate, and associating them with the nearest cities using citipy. From there, using the Google Places and Google Directions API's, gmaps were created to show the cities on the map, along with the associated weather and hotel data. A brief explanation of the files can be found below:
  
### Weather_Database.ipynb

  A Jupyter Notebook script to call the OpenWeatherMap API to associate weather data with cities that are generated using random latitudes and longitudes

### WeatherPy_Database.csv

  A csv file containing the weather data

### Vacation_Search.ipynb

  A Jupyter Notebook script to gather user input and generate a gmap with markers for cities that satisfy the user input

### WeatherPy_vacation.csv

  A csv file containing the hotel data

### WeatherPy_vacation_map.png

  A screenshot of the hotel map generated using gmaps

### Vacation_Itinerary.ipynb

  A Jupyter Notebook script to call the Google Directions API, mapping driving routes between four cities

### WeatherPy_travel_map.png

  A screenshot of the itinerary route using gmaps

### WeatherPy_travel_map_markers.png

  A screenshot of the itinerary route with markers containing hotel and weather data
