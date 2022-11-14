# Mapping_Earthquakes

## Project Overview
The purpose of this project is to visually show the differences between the magnitudes of earthquakes all over the world for the last seven days. We wrote a script to pull the `GeoJSON` earthquake data from the [USGS website](https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson) to retrieve the geographical coordinates and magnitudes of earthquakes for the last seven days. The data is then added to a map. Since the information is linked to a real-time source, the map will update whenever the user accesses it. Scripts are built using `JavaScript` and `D3.js` library to retrieve the coordinates and magnitudes of the earthquakes from the GeoJSON data. We then used `Leaflet` library to plot the data on a `Mapbox` style map through an API request and made it interactive by adding visualization for different map styles, creating layers to display Tectonic plates, Earthquake magnitude and location information.

Throughout this project, we learned how to create map layers, visual customizations that included:

 * Toggling between map styles (i.e. dark, streets, satellite)
 * Color changes to lines, marker types, and sizes
 * Adding popup info box
 * Plotting different points, multiple points, lines, polygons
 
 ## Resources
 
  * Data Source: [Earthquakes GeoJSON](https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson), [Earthquakes above 4.5mag GeoJSON](https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/4.5_week.geojson),[Tectonic Plate data](https://raw.githubusercontent.com/fraxen/tectonicplates/master/GeoJSON/PB2002_boundaries.json) 
  * Software: HTML/CSS, JavaScript, Visual Studio Code 1.49.1, Leaflet 1.7.1, D3.js 6.2.0
  
 ## Results
