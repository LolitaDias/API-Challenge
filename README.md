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




















* In building your script, pay attention to the cities you are using in your query pool. Are you getting coverage of the full gamut of latitudes and longitudes? Or are you simply choosing 500 cities concentrated in one region of the world? Even if you were a geographic genius, simply rattling 500 cities based on your human selection would create a biased dataset. Be thinking of how you should counter this. (Hint: Consider the full range of latitudes).

* Lastly, remember -- this is a challenging activity. Push yourself! If you complete this task, then you can safely say that you've gained a strong mastery of the core foundations of data analytics and it will only go better from here. Good luck!

### Copyright

Trilogy Education Services © 2019. All Rights Reserved.
