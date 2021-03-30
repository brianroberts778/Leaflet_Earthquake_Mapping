# Leaflet Earthquake Data Visualization

Background:
The USGS is responsible for providing scientific data about natural hazards, the health of our ecosystems and environment; and the impacts of climate and land-use change. Their scientists develop new methods and tools to supply timely, relevant, and useful information about the Earth and its processes.

I was interested in building a new set of tools that will allow them visualize their earthquake data. They collect a massive amount of data from all over the world each day, but they lack a meaningful way of displaying it. Their hope is that being able to visualize their data will allow them to better educate the public and other government organizations (and hopefully secure more funding..) on issues facing our planet.

Visualization:
1. Get the Data 
 - The USGS provides earthquake data in a number of different formats, updated every 5 minutes. Visit the USGS GeoJSON Feed page and pick the 'All Earthquakes from the Past 7 Days' data set to visualize. Clicking the link yields a JSON representation of that data. Use the URL of this JSON to pull in the data for the visualization.

2. Import & Visualize the Data
 - Create a map using Leaflet that plots all of the earthquakes from your data set based on their longitude and latitude.
 - The data markers reflect the magnitude of the earthquake by their size and depth of the earthquake by color. Earthquakes with higher magnitudes should appear larger and earthquakes with greater depth should appear darker in color.
 - Includes popups that provide additional information about the earthquake when a marker is clicked.
 - Creates a legend that will provide context for your map data.
