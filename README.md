# Python API Homework - What's the Weather Like?

## Background

Whether financial, political, or social -- data's true power lies in its ability to answer questions definitively. In this assignment we answer a fundamental question: "What's the weather like as we approach the equator?"

![Equator](Images/equatorsign.png)

In this example, we will be creating a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. To accomplish this, we will be utilizing a [simple Python library](https://pypi.python.org/pypi/citipy), the [OpenWeatherMap API](https://openweathermap.org/api), and a little common sense to create a representative model of weather across world cities.

Our objective is to build a series of scatter plots to showcase the following relationships:

1. Temperature (F) vs. Latitude
2. Humidity (%) vs. Latitude
3. Cloudiness (%) vs. Latitude
4. Wind Speed (mph) vs. Latitude

Our final notebook :

1. Randomly selects **at least** 500 unique (non-repeat) cities based on latitude and longitude.
2. Performs a weather check on each of the cities using a series of successive API calls.
3. Includes a print log of each city as it's being processed with the city number and city name.
4. Saves both a CSV of all data retrieved and png images for each scatter plot.

