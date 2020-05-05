# <p align="center">Visualizing USGS Earthquake Data with Leaflet</p>

![MainScreenShot](Images/MRD_MainMapScreenShot.png)

## Background

<p align="center">
  <img width="600" height="200" src="Images/1-Logo.png?raw=true)">
</p>

The United States Geological Survey (USGS) is responsible for providing scientific data about natural hazards, the health of our ecosystems and environment; and the impacts of climate and land-use change. The have some of the top scientists in the world who develop new methods and tools to supply timely, relevant, and useful information about the Earth and its processes.

In this project, I want to build a new set of tools that will visualize USGS earthquake data. They collect a massive amount of data from all over the world each day and a robust set of vizzes help tell important stories from their data collected. Important policy and funding decisions that impact the public's health and safety use this data.


### Setup up Github repo to oraganize plots, code, and date collected from the USGS data

1. I created a new GitHub repository for this project called `leaflet-challenge`.
2. I cloned this new repository to my computer.
3. Inside your local git repository, create a directory for the Leaflet challenge. Use the folder names to correspond to the challenges: **Leaflet-Step-1** and **Leaflet-Step-2**.
4. This project utilizes both **html** and **Javascript**.
5. Pushed the above changes to GitHub.


## Projec Documentation

### 1. **Collect the USGS data set**

<p align="center">
  <img src="Images/MRD_USGSsite.png?raw=true)">
</p>
<p align="center">
  <img width="181" height="754" src="Images/MRD_USGSfeeds.png?raw=true)">
</p>   
   The USGS provides earthquake data in a number of different formats, updated every 5 minutes at [USGS GeoJSON Feed](http://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php). When you click on a data set, for example 'All Earthquakes from the Past 7 Days', you will be given a JSON representation of that data. You will be using the URL of this JSON to pull in the data for our visualization.

   ![4-JSON](Images/4-JSON.png)

2. **Import & Visualize the Data**

   Create a map using Leaflet that plots all of the earthquakes from your data set based on their longitude and latitude.

   * Your data markers should reflect the magnitude of the earthquake in their size and color. Earthquakes with higher magnitudes should appear larger and darker in color.

   * Include popups that provide additional information about the earthquake when a marker is clicked.

   * Create a legend that will provide context for your map data.

   * Your visualization should look something like the map above.

- - -

### Level 2: More Data (Optional)

![5-Advanced](Images/5-Advanced.png)

The USGS wants you to plot a second data set on your map to illustrate the relationship between tectonic plates and seismic activity. You will need to pull in a second data set and visualize it along side your original set of data. Data on tectonic plates can be found at <https://github.com/fraxen/tectonicplates>.

In this step we are going to..

* Plot a second data set on our map.
* Add a number of base maps to choose from as well as separate out our two different data sets into overlays that can be turned on and off independently.
* Add layer controls to our map.

- - -
## Author

* **Michael Davis** - [Davis1776](https://github.com/Davis1776)

## Acknowledgments

* Data Source: 

## Copyright
Michael Davis © 2020. All Rights Reserved.