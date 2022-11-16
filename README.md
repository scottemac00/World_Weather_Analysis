# World_Weather_Analysis
## Purpose 
- The purpose of this project was to collect and present data for customers via a notional search page, which they would be able to filter based on specific (preferred) travel criteria in order to find their ideal hotel, anywhere in the world.
## Analysis
- Part of this analysis entailed performing statistical calculations on real-time weather data using linear regression on parameters in the Northern and Southern hemispheres. This data can help teams predict the best time of year for people to plan their vacation (if a major factor in their planning is weather).
- Analysis of locations in [WeatherPy.ipynb](https://github.com/scottemac00/World_Weather_Analysis/blob/6a6c5e5d51a2df779ca48af239a6edfa7dbc4a60/WeatherPy.ipynb)
- Weather data generated from API call to openweathermap.org in [Weather_Database](https://github.com/scottemac00/World_Weather_Analysis/tree/main/Weather_Database)
- Customer Travel Destinations Information and supporting code in [Vacation_Search](https://github.com/scottemac00/World_Weather_Analysis/tree/main/Vacation_Search)
- Sample Travel Itinerary Information  and supporting code in [Vacation_Itinerary](https://github.com/scottemac00/World_Weather_Analysis/tree/main/Vacation_Itinerary)
## Summary Results
- The data was exported, assessed, cleaned, and used to identify the best cities for vacation based on specific temperature criteria, and then mapping these cities using Jupyter and the Google Places API. Correlations between latitude and temperature and humidity were noted, with cloud cover and wind speed proving not to have correlational signficance based on a city's geographic location. Of course weather is but one factor customers consider when planning a vacation. Additional uses for code similar to this, perhaps with added functionalities that allow for additional variable inputs would certainly assist users when planning travel.
