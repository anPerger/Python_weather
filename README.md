# Python_weather

# Dependancies
Matplotlib.pyplot  
Pandas  
Numpy  
Requests  
Time  
Scipy.stats  
JSON 
TKinter  
Datetime  
Citipy  
Gmaps  
Pygeocoder

And a google API key in a config.py file

# Overview
This project consists of two parts. The first part contains a notebook that generates random lat-lng coordinates with numpy and then uses the citypy library to determine the
nearest city to the lat-lng coordinates generated. After assembling the dataframe of cities, and api call is made to openweathermap.org to pull current weather conditions in
each city. Once all this data has been pulled into a dataframe, weather conditions were analyzed comparing latitude with maximum temperature, wind speed, cloudiness, and
humidity. Aditional analysis was done breaking up the dataset into northern and southern hemispheres and running the same analysis, creating linear visualizations for each.

The second part utilizes the output data from the first part to curate a short list of ideal vacation destinations based on individual weather preferences. The cities with
these weather preference parameters are then fed into a google places api call to find a hotel in that city and output as a final dataframe and map with hotel locations 
and information pinned.


