# leaflet-challenge

### Objective

Build a new set of tools to visualize USGS earthquake data.

### Summary

The [United States Geological Survey (USGS)](https://www.usgs.gov) is responsible for providing scientific data about natural hazards, the health of our ecosystems and environment; and the impacts of climate and land-use change. Their scientists develop new methods and tools to supply timely, relevant, and useful information about the Earth and its processes.

The USGS collects a massive amount of data from all over the world each day, but they lack a meaningful way of displaying it. The ability to visualize their data will help them to better educate the public and other government organizations (and hopefully secure more funding) on issues facing our planet.

### The Visualization


1. **Get the data set**

The USGS provides earthquake data in a number of different formats, updated every 5 minutes. Visit the [USGS GeoJSON Feed](http://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php) page and pick a data set to visualize. When you click on a data set, for example "All Earthquakes from the Past 7 Days", you will be given a JSON representation of that data. You will use the URL of this JSON to pull in the data for our visualization.

2. **Import and visualize the data**
   Create a map using Leaflet that plots all of the earthquakes from your data set based on their longitude and latitude.
   * Your data markers should reflect the magnitude of the earthquake by their size and and depth of the earthquake by color. Earthquakes with higher magnitudes should appear larger and earthquakes with greater depth should appear darker in color.
   * **HINT:** The depth of the earth can be found as the third coordinate for each earthquake.
   * Include popups that provide additional information about the earthquake when a marker is clicked.
   * Create a legend that will provide context for your map data.
   * Your visualization should look something like the map above.

### Step 2: Advanced (Optional)

Plot a second data set on your map to illustrate the relationship between tectonic plates and seismic activity. You will need to pull in a second data set and visualize it alongside your original set of data. Data on tectonic plates can be found at <https://github.com/fraxen/tectonicplates>.
In this step, you will:
* Plot a second data set on our map.
* Add a number of base maps to choose from as well as separate out our two different data sets into overlays that can be turned on and off independently.
* Add layer controls to our map.
