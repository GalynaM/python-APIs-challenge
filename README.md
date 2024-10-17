## python-APIs-challenge

## Project description:
### The project analyses the weather of 500+ cities across the world of varying distance from the equator.

### Data retrieved from:
* OpenWeather API to retrieve weather data https://openweathermap.org/api.
* Google Places API is used to find locations of Hotels in cities with the best weather https://developers.google.com/maps/documentation/places/web-service/overview.

#### WeatherPy.ipynb
#### The weather of 500+ cities across the world of varying distance from the equator is vizualized.
* Citypy module is used. https://pypi.org/project/citipy/; https://github.com/wingchen/citipy.
* 500 unique (non-repeat) cities were randomly selected based on latitude and longitude.
* A weather check on each of the cities performed using a series of successive API calls.
* A print log of each city as it's being processed with the city number and city name included.
* Weather data for retrieved cities cleaned to exclude cities with >100% humidity.
* The following relationships vizualized and analyzed:
  Max Temperature (F) vs. Latitude, Humidity (%) vs. Latitude, Cloudiness (%) vs. Latitude, Wind Speed (mph) vs. Latitude.
* MatPlotLib package used to build Charts. 
* SciPy package used to calculate linear regression and Pearson correlation.
* Analysis was done separetely for North and South Hemispheres.


#### VacationPy.ipynb
#### Using weather data plan future vacations.
* Weather data for cities from Part I used to plan vacations.
* Gmaps library used to visualize the map.
* The Humidity Heatmap created for the cities in data set.
* DataFrame to find an ideal weather condition was narrowed.
* Google Places API used to find the first hotel for each city located within 5000 meters of ideal coordinates.
* Marker Layers for Hotels in the ideal weather conditions added.
