# Leaflet Homework - Visualising Data with Leaflet

## Background

Background 

The United States Geological Survey, or USGS for short is responsible for providing scientific data about natural hazards, the health of our ecosystems and environment; and the impacts of climate and land-use change. Their scientists develop new methods and tools to supply timely, relevant, and useful information about the Earth and its processes.

The USGS is interested in building a new set of tools that will allow them visualise their earthquake data. They collect a massive amount of data from all over the world each day, but they lack a meaningful way of displaying it. Their hope is that being able to visualise their data will allow them to better educate the public and other government organisations (and hopefully secure more funding..) on issues facing our planet.

The USGS provides earthquake data in a number of different formats, updated every 5 minutes. Visit the [USGS GeoJSON Feed](http://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php) page and pick a data set to visualise. When you click on a data set, for example 'All Earthquakes from the Past 7 Days', you will be given a JSON representation of that data. You will be using the URL of this JSON to pull in the data for our visualisation.

The repository "Leaflet-Challenge" comprises 2 sections:

1.**Leaflet-Step-1** 
Basic Visualisation: Display basemaps Dark and light basemaps from mapbox. Contains 1 overlay to show where earthquakes have been recorded color and circle size coded to the earthquakes magniture. Overlay can be turned on and off

The folder structure :
Leaflet-1
     Images
       --various images provided for the homework to compare results to
     static
       --css
          style.css
     Index.html
       --js
          config.js : contains api_key for mapbox (removed when loaded into repository)
          logic.js  : the main logic create and display the map and its features 

2 **Leaflet-Step-2**.
Advanced Visualisation: The USGS wants you to plot a second data set on your map to illustrate the relationship between tectonic plates and seismic activity. You will need to pull in a second data set and visualise it along side your original set of data. Data on tectonic plates can be found at <https://github.com/fraxen/tectonicplates>.

Display basemaps Dark and light basemaps from mapbox. Contains 2 overlays to show where earthquakes have been recorded color and circle size coded to the earthquakes magniture and where the boundaries of the earth's tectonic plates are. Overlay can be turned on and off

The folder structure :
Leaflet-1
     Images
       --various images provided for the homework to compare results to
     static
       --css
          style.css
     Index.html
       --js
          config.js : contains api_key for mapbox (removed when loaded into repository)
          logic.js  : the main logic create and display the map and its features 



