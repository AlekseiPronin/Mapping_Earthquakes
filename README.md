# Mapping_Earthquakes

## Purpose 

The purpose of this project was to create the interactive map of the world using JavaScript D3 library, GeoJSON data, Leaflet library and Mapbox API.

The project was broken down into several steps:

* the data was retrieved in GeoJSON format
* the API request was made to server to host geographical maps
* maps were populated with GeoJSON data using JavaScript and D3 library
* multipple layers were added to a map using Leaflet control plugins to add user interface controls
* ES6 functions were used to add GeoJson data, features and interactivity to maps


In the end user has an option to switch between 3 different types of maps and 3 overlays that can be toggled on and off according to user's preferrence. The map also contains the legend for convenience. Each earthquake is visually represented by a circle and color, where a higher magnitude has a larger diameter and darker in color. In addition, each earthquake has a popup marker that, when clicked, shows the magnitude of the earthquake and the location of the earthquake.

The screenshot of the map as follows

![map](https://github.com/AlekseiPronin/Mapping_Earthquakes/blob/main/Resources/map.png)
