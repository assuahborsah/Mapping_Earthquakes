# Mapping_Earthquakes

## Project Overview


## Purpose


The purpose of this project is to visually show the differences between the magnitudes of earthquakes all over the world for the last seven days.
The tasks to complete this project is to use a URL for GeoJSON earthquake data from the USGS website by retrieving geographical coordinates and the magnitudes of earthquakes for the last seven days. Then add the data to a map.
To tackle this, JavaScript and the D3.js library would be incorporated to retrieve the coordinates and magnitudes of the earthquakes from the GeoJSON data. After, the Leaflet library will be accessed to plot the data on a Mapbox map through an API request and create interactivity for the earthquake data.


## Resources


Visual Studio Code, Chrome, Git Bash, GitHub
JavaScript, JSON, GeoJSON


## Results


The following steps would be followed for this analysis:

## Deliverable 1: Add Tectonic Plate Data.


Using your knowledge of JavaScript, Leaflet.js, and geoJSON data, you’ll add tectonic plate data using d3.json(), add the data using the geoJSON() layer, set the tectonic plate LineString data to stand out on the map, and add the tectonic plate data to the overlay object with the earthquake data.



![image](https://user-images.githubusercontent.com/96086671/175818709-ad526b9e-0fd2-48ad-8e70-26ecfb1c7fd7.png)


 

## Deliverable 2: Add Major Earthquake Data.


Using your knowledge of JavaScript, Leaflet.js, and geoJSON data, you’ll add major earthquake data to the map using d3.json(). You'll also add color and set the radius of the circle markers based on the magnitude of earthquake, and add a popup marker for each earthquake that displays the magnitude and location of the earthquake using the GeoJSON layer, geoJSON().




![image](https://user-images.githubusercontent.com/96086671/175818856-45d96251-535b-40c7-bbef-2de65b9de0bf.png)

 

## Deliverable 3: Add an Additional Map


Using your knowledge of JavaScript and Leaflet.js add a third map style to your earthquake map.



![image](https://user-images.githubusercontent.com/96086671/175818892-2a0b21c2-6ad2-4804-b564-a3d1d8d87c4e.png)


 
## Summary


Interactive maps were created using JavaScript and the D3 library to traverse and retrieve GeoJSON earthquake and tectonic plate data from the past 7 days, where the the magnitude of the earthquake is displayed on circles that varies in size and color according to its strength where details can be seen on a popup box when clicked. Also, Leaflet library was used to plot the data on a Mapbox map through an API request.

