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
The deployed webpage is accessible [here](https://mitchellfagert.github.io/).

**Interactive Map Views**


*Streets view*
<img width="668" alt="Street_view" src="https://user-images.githubusercontent.com/107579508/201744336-ab04e3b5-399d-4eac-a0fa-fc839e17f538.png">

*Satellite view*
<img width="665" alt="Satellite_view" src="https://user-images.githubusercontent.com/107579508/201744354-aeb8110c-7c26-4f1f-997d-0920f76eafeb.png">

*Dark view*
<img width="661" alt="Dark_view" src="https://user-images.githubusercontent.com/107579508/201744370-a593a4f8-4ed9-4c69-adf9-3585855c2bb9.png">
