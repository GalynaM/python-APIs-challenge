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
* The following relationships vizualized and analyzed:
* Temperature (F), Humidity (%), Cloudiness (%), Wind Speed (mph) vs. Latitude.
* Scatter Plots used to show correlation between latitude and other weather parameters.
* Linear regression run on each relationship, separating North and South Hemispheres to analyze correlation.
* 

#### VacationPy.ipynb
#### Using weather data plan future vacations.
* Jupyter-gmaps were used.
* A heat map that displays the humidity for every city from the part I of the homework created.
* DataFrame to find an ideal weather condition was narrowed.
* Google Places API used to find the first hotel for each city located within 5000 meters of ideal coordinates.
* Marker Layers for Hotels in the ideal weather conditions added.
