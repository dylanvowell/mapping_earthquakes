# OVERVIEW
In this project, I used the Leaflet.js Application Programming Interface (API) to populate a geographical map with GeoJSON earthquake data from a URL. Each earthquake is visually represented by a circle and color, where a higher magnitude will have a larger diameter and will be darker in color. In addition, each earthquake has a popup marker that, when clicked, shows the magnitude of the earthquake and the location of the earthquake. There are also several map layers to choose from, as well as the option to filter between all earthquakes, tectonic plates, and major earthquakes. 

## Process 

Using JavaScript, Leaflet.js, and geoJSON data, I added tectonic plate data with d3.json() and geoJSON(), and set tectonic plate data with LineStrings to display on the map. I then added additional information to the map data by including popups for each earthquake marker that displayed the magnitude and location using the geoJSON layer.

## Map Preview
![map screenshot](https://github.com/dylanvowell/mapping_earthquakes/blob/main/map_screenshot.png?raw=true)
