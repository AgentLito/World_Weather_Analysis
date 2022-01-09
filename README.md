# World_Weather_Analysis
Jupyter Notebook
Overview

We are working on the PlanMyTrip app. Within this app we are using open weather api to find out specific city details (city, country, date, latitude and longitude, maximum temperature, humidity, cloudiness, wind speed). With these specific details, we can create vacation search. We can make it as a traveling itinerary for the customer to find out their travelling destination. With some modifications on criteria such as "weather descriptions" for specific places that the customer wants to visit. Off this list of potential travel destinations, we will choose four cities to create a travel itinerary.
This project involved accessing a site via API to pull data involving current weather conditions for numerous locations across the world. Then taking this data we utilized Google API to map this data, search for hotels near vicinity, and route trip information.

Purpose

Here we are going use the Google Maps Directions API, to create a travel route between the four cities as well as a marker layer map which will give descriptions respectively.

Resources

Python 3.7.6
Jupyter Notebook



1. Weather DataBase:

Retrieve the following information from the API call:
Latitude and longitude
Maximum temperature
Percent humidity
Percent cloudiness
Wind speed
Weather description (for example, clouds, fog, light rain, clear sky)
Create a csv file and save it

2. Vacation Search:

Take user input for temperatures and find out the travel itinerary and retrieve the hotel info.
Set markers with following description:
Hotel name
City
Country
Current weather description with the maximum temperature
3. Vacation Itinerary:

Use the Google Directions API
Create a travel itinerary
Show the route between four cities chosen from the customer
Results

1. Weather DataBase which we created with the help of open weather api:
![Screen Shot 2021-12-26 at 10 32 53 PM](https://user-images.githubusercontent.com/91812090/147434761-9d9fa1ef-9101-41ec-bb20-19a0a0c9c198.png)
2. Vacation Search for specific temprature criteria with the help of google maps api:
![Screen Shot 2021-12-26 at 10 35 45 PM](https://user-images.githubusercontent.com/91812090/147434847-b2e2b320-866f-45f4-8ba8-4773b73e2a33.png)
3. Vacation Itinerary with travel rout and description with the help of google maps direction api:
![Screen Shot 2022-01-08 at 6 42 40 PM](https://user-images.githubusercontent.com/91812090/148664740-2d7d2777-2185-4a9b-8caa-2c5ef35648d3.png)

