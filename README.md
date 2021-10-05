# world-weather-analysis

## OVERVIEW and METHODOLOGY

[**Weather salience**](https://journals.ametsoc.org/view/journals/bams/90/12/2009bams2794_1.xml) is a psychological concept that describes the way that certain individuals may be more oriented towards, or cognizant of the weather/ atmospheric environment. This concept is also examined when studying behaviours in travel and tourism. ["All tourism destinations are considered climate-sensitive to some extent, and the weather/climate is a key influence on travel planning and the travel experience."](https://scholars.wlu.ca/cgi/viewcontent.cgi?article=1034&context=geog_faculty) With that being said, this project was created to test a potential app for weather-salient travellers to compare travel destinations based on weather conditions, and also locate nearby hotels.

NumPy's `random` module was used to generate 2000 geo coordinates, which were then converted to cities using the `citypy` module. An API call was made for OpenWeatherMap to obtain the following weather data for the newly-generated list of cities:

* Latitude and longitude
* Maximum temperature
* Percent humidity
* Percent cloudiness
* Wind speed
* Current Weather description

The code was configured so that users can enter their desired temperature range, which would then filter the dataset to find the cities that matched the criteria. Google Maps API was used to locate nearby hotels. Users also have the option to choose four cities to create a travel itinerary. 


