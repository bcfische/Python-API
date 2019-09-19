WeatherPy

In this example, we create a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator.
To accomplish this, we utilize a simple Python library, the OpenWeatherMap API, and a little common sense to create a representative
model of weather across world cities. The objective is to build a series of scatter plots to showcase the following relationships:
~Temperature (F) vs. Latitude
~Humidity (%) vs. Latitude
~Cloudiness (%) vs. Latitude
~Wind Speed (mph) vs. Latitude

The final notebook randomly selects at least 500 unique (non-repeated) cities based on latitude and longitude. It then performs a
weather check on each of the cities using a series of successive API calls. A print log is included for each city as it's being processed
with the city number and city name. Contained in this directory is a CSV of all data retrieved and as well as png images for each scatter
plot.
