# World_Weather_Analysis
Jupyter Notebook
Overview

We are working on the PlanMyTrip app. In this app we are using open weather api to find out city specific details (City, country, date, Latitude and longitude, Maximum temperature, Humidity, Cloudiness, Wind speed). With the help of details, we can create vacation search and make it as traveling itinerary for the customer to find out their travelling destination. There are some modifications on criteria like "weather descriptions" for specific places that customer want to visit. From the list of potential travel destinations, will choose four cities to create a travel itinerary.

Purpose

Here we are going use the Google Maps Directions API, to create a travel route between the four cities as well as a marker layer map which will give descriptions respectively.

Resources

Jupyter Notebook
Python 3.7.6
Dependencies
Python Pandas library
Python Numpy library
Python Request library
Json Library
Google maps API
Requirements

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
4. 
