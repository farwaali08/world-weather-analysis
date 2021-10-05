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

## QUICK LINKS

**CSV Files:**

* [WeatherPy_Database](https://github.com/farwaali08/world-weather-analysis/blob/65393b84d8485027fa9086d7adec54db1ac5395b/weather-database/WeatherPy_Database.csv)

* [WeatherPy_Vacation](https://github.com/farwaali08/world-weather-analysis/blob/65393b84d8485027fa9086d7adec54db1ac5395b/vacation-search/WeatherPy_Vacation.csv)


**Code:**

* [Weather_Database](https://github.com/farwaali08/world-weather-analysis/blob/65393b84d8485027fa9086d7adec54db1ac5395b/weather-database/Weather_Database.ipynb)

* [Vacation_Search](https://github.com/farwaali08/world-weather-analysis/blob/65393b84d8485027fa9086d7adec54db1ac5395b/vacation-search/Vacation_Search_starter_code.ipynb) 

* [Vacation_Itinerary](https://github.com/farwaali08/world-weather-analysis/blob/65393b84d8485027fa9086d7adec54db1ac5395b/Vacation_Itinerary/Vacation_Itinerary_starter_code.ipynb)


## VACATION SEARCH

The map below displays potential travel destinations and nearby hotels based on the user's weather preferences.

![alt_text](https://github.com/farwaali08/world-weather-analysis/blob/65393b84d8485027fa9086d7adec54db1ac5395b/vacation-search/WeatherPy_vacation_map.png)



## VACATION ITINERARY

In this example, a travel route and itinerary was created for 4 cities in Japan.

![alt_text](https://github.com/farwaali08/world-weather-analysis/blob/65393b84d8485027fa9086d7adec54db1ac5395b/Vacation_Itinerary/WeatherPy_travel_map.png)




![alt_text](https://github.com/farwaali08/world-weather-analysis/blob/65393b84d8485027fa9086d7adec54db1ac5395b/Vacation_Itinerary/WeatherPy_travel_map_markers.png)
