# What's the weather like?

 "What's the weather like as we approach the equator?"

Part I - WeatherPy

I randomly select 500 unique (non-repeat) cities based on latitude and longitude and perform a weather check on each of the cities using a series of API calls with the use of Python library, the OpenWeatherMap API. I created a Python script to visualize the weather of these cities.
A series of scatter plots were created to showcase the following relationships:

Temperature (F) vs. Latitude

Humidity (%) vs. Latitude

Cloudiness (%) vs. Latitude

Wind Speed (mph) vs. Latitude


I also run linear regression on each relationship for cities in Northern Hemisphere and those in Southern Hemisphere. 

Northern Hemisphere - Temperature (F) vs. Latitude

Southern Hemisphere - Temperature (F) vs. Latitude

Northern Hemisphere - Humidity (%) vs. Latitude

Southern Hemisphere - Humidity (%) vs. Latitude

Northern Hemisphere - Cloudiness (%) vs. Latitude

Southern Hemisphere - Cloudiness (%) vs. Latitude

Northern Hemisphere - Wind Speed (mph) vs. Latitude

Southern Hemisphere - Wind Speed (mph) vs. Latitude


Part II - VacationPy
I created a heat map that displays the humidity for every city from Part I and narrowed down the DataFrame to find the cities with ideal weather condition:

A max temperature lower than 80 degrees but higher than 70.


Wind speed less than 10 mph.


Zero cloudiness.
 
Using Google Places API, I found the first hotel for each city located within 5000 meters of the coordinates and plot the hotels on top of the humidity heatmap with each pin containing the Hotel Name, City, and Country.

