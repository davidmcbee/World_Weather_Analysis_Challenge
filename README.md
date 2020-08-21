# World_Weather_Analysis_Challenge
## Purpose of Analysis

Based on initial feedback from supervisor and beta testers, they recommended the following changes and modificaitons.
* Add the weather description to the weather data you’ve already retrieved.
* Add input statements to filter the data for their weather preferences, which will be used to identify potential travel destinations and nearby hotels.
* From the list of potential travel destinations, the beta tester will choose four cities to create a travel itinerary.
* Using the Google Maps Directions API to create a travel route between the four cities as well as a marker layer map.

## Analysis Segments
### Get Weather Data
* Generated a set of 2,000 random latitudes and longitudes.
* Retrieved the nearest city, and performed an API call with the OpenWeatherMap to retrieve the current weather description for each city.
* Created a new DataFrame containing the updated weather data.
### Create a Customer Travel Destinations Map
* Used input statements to retrieve customer weather preferences, then used those preferences to identify potential travel destinations and nearby hotels.
* Showed those destinations on a marker layer map with pop-up markers.
### Creat a Travel Itinerary Map
* Used the Google Directions API to create a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations.
* Showed those destinations on a map with a route including start, waypoints and end (same as start) that can be used for driving, bicycling, or walking.
* Created a marker layer map with a pop-up marker for each city on the itinerary.
