# Python_weather

This project consists of two parts. The first part contains a notebook that generates random lat-lng coordinates and then uses the citypy library to determine the nearest city
to the lat-lng coordinates generated. After assembling the dataframe of cities, and api call is made to openweathermap.org to pull current weather conditions in each city (api
call was made August 8th, 2020). Once all this data has been pulled into a dataframe, weather conditions were analyzed comparing latitude with maximum temperature, wind speed,
cloudiness, and humidity. Aditional analysis was done breaking up the dataset into northern and southern hemispheres and running the same analysis. 

The second part utilizes the output data from the first part to curate a list of 15-20 ideal vacation destinations based on individual weather preferences. The cities with
these weather preference parameters are then fed into a google places api call to find a hotel in that city and output as a final dataframe and a map with hotel locations
pinned
