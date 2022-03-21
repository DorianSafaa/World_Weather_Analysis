# World_Weather_Analysis
## Description of the analysis

In this analysis, we generated a set of 2,000 random latitudes and longitudes and retrieved the nearest city. Then, we perform an API call with the OpenWeatherMap and retrieved the following information:

 •	Latitude and longitude
 
 •	Maximum temperature
 
 •	Percent humidity
 
 •	Percent cloudiness
 
 •	Wind speed
 
 •	Weather description (for example, clouds, fog, light rain, clear sky)

![Picture1](https://user-images.githubusercontent.com/66279829/159218322-adaa52f5-e2e0-45de-af00-5ff37bd43b79.png)

After gathering the data, we used input statements to retrieve customer weather preferences, then used those preferences to identify potential travel destinations and nearby hotels we have supplied the search parameter (search for hotels with 5000 meters) that we needed to use to search for a hotel for each city. Finally, we created a marker layer map that have pop-up markers for each city on the map

![WeatherPy_vacation_map](https://user-images.githubusercontent.com/66279829/159218236-c68bd7ba-3923-401c-8d88-8e05dc580d99.png)
 

Finally, we used the Google Directions API to create a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations. Then, created a marker layer map with a pop-up marker for each city on the itinerary.

![WeatherPy_travel_map](https://user-images.githubusercontent.com/66279829/159218193-fbc5c7db-5a77-4ab3-aea9-e393d2bbccd4.png)

![WeatherPy_travel_map_markers](https://user-images.githubusercontent.com/66279829/159218151-88131f53-e80f-4dda-b5f9-69fe559c9b29.png) 


