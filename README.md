![Map-based Visualizations](https://github.com/carnot-technologies/MapVisualizations/blob/master/images/GitHub%20Readme%20Images/All_Visualizations.png)

# Map-based Visualizations in Python
[![HitCount](http://hits.dwyl.com/carnot-technologies/MapVisualizations.svg)](http://hits.dwyl.com/carnot-technologies/MapVisualizations)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

:star: Star us on GitHub — it helps!  
This is the helper repo for the series of map-based visualization tutorial posts on medium, covering several popular python libraries that are generally used for geo-spatial data visualization.


## Table of contents
- [About](#about)
- [Types of Visualizations](#types-of-visualizations)
- [Libraries Covered](#libraries-covered)
- [Comparison of the libraries](https://medium.com/@sanghviyash7/5eb66d4cad5e?source=friends_link&sk=f2a1fbb76e98db37d292d1e5c21eeaa3)
- [Auxiliary Concepts Covered](#auxiliary-concepts-covered)
- [Contributing to this repo](#contributing-to-this-repo)


## About
Map-based visualizations are an essential aspect of any data-presentation/ inference. Geo-spatial visualizations become all the more important for IoT companies like Carnot which have their devices scattered across different geographies. We at Carnot realized the need for having a robust map-based visualization infrastructure for all our present and future requirements. When we started building this infrastructure, we realized that there are way too many libraries available for map visualizations and several detailed tutorials for each library. However, what wasn't readily available was a comparison of the different libraries and a guide on which library is best suited for a particular application. 

Hence, we started off with one library at a time, determined what it was best suited for, and then moved on to the next. We kept doing this exercise till we generated nearly all the types of visualizations we could envision. This repo is a helper repo for the series of Medium blog posts on map-based visualizations, where we share a summary of our learning during this entire exercise. It will hopefully serve as a guide to people who find themselves as overwhelmed with choices as we were at the start of our infra-building exercise.

In order to get an overview and comparison of different libraries, [Click Here](https://medium.com/@sanghviyash7/5eb66d4cad5e?source=friends_link&sk=f2a1fbb76e98db37d292d1e5c21eeaa3).

## Types of Visualizations
- Scatter
- Choropleth

## Libraries Covered
| Library  | Visualization Covered | Visualization Preview | Tutorial | View Jupyter Notebook |
| :---:  | :---:  | :---:  | :---:  | :---:  |
| Cartopy | Scatter with custom map background | ![](https://github.com/carnot-technologies/MapVisualizations/blob/master/images/GitHub%20Readme%20Images/cartopy.png)| [Click Here](https://medium.com/@sanghviyash7/9b7b88ef8b6b?source=friends_link&sk=5e1685606eeb5fe3b46a5583ce50c380) | [Click Here](https://nbviewer.jupyter.org/github/carnot-technologies/MapVisualizations/blob/master/CartopyDemo.ipynb)|
| GeoPandas | Choropleth with shapefile | ![](https://github.com/carnot-technologies/MapVisualizations/blob/master/images/GitHub%20Readme%20Images/geopandas.png) | [Click Here](https://medium.com/@sanghviyash7/8adb77a7d14?source=friends_link&sk=f9aefc50ef5019d2dcb1674c8c5ff6d4) | [Click Here](https://nbviewer.jupyter.org/github/carnot-technologies/MapVisualizations/blob/master/GeoPandasDemo.ipynb)|
| Plotly | Interactive Choropleth with GeoJSON | ![](https://github.com/carnot-technologies/MapVisualizations/blob/master/images/GitHub%20Readme%20Images/plotly.png)| [Click Here](https://medium.com/@sanghviyash7/44e8ad419b97?source=friends_link&sk=a35de50939c1c97e5dc6620c8862fca8) | [Click Here](https://nbviewer.jupyter.org/github/carnot-technologies/MapVisualizations/blob/master/PlotlyChoroplethDemo.ipynb)|
| Plotly + Mapbox | Interactive Choropleth with GeoJSON and base-map | ![](https://github.com/carnot-technologies/MapVisualizations/blob/master/images/GitHub%20Readme%20Images/mapbox2.PNG) | [Click Here](https://medium.com/@sanghviyash7/957dcdbca90b?source=friends_link&sk=26b82e00130e1c95564e02023df8999d) | [Click Here](https://nbviewer.jupyter.org/github/carnot-technologies/MapVisualizations/blob/master/PlotlyWithMapbox%20%28Choropleth%20Plot%29.ipynb)|
| Plotly + Mapbox | Interactive Scatter with base-map | ![](https://github.com/carnot-technologies/MapVisualizations/blob/master/images/GitHub%20Readme%20Images/mapbox1.PNG) | [Click Here](https://medium.com/@sanghviyash7/22434cd6a283?source=friends_link&sk=9a30e33b96bc37fbca6d4b68278ab016) | [Click Here](https://nbviewer.jupyter.org/github/carnot-technologies/MapVisualizations/blob/master/PlotlyWithMapbox%20%28Scatter%20Plot%29.ipynb)|
| Plotly + Datashader | Partly Interactive Large-data Scatter with base-map | ![](https://github.com/carnot-technologies/MapVisualizations/blob/master/images/GitHub%20Readme%20Images/datashader.PNG) | [Click Here](https://medium.com/@sanghviyash7/bea27b9d7824?source=friends_link&sk=006562403c528643714b5dfb2b7b4f68)| [Click Here](https://nbviewer.jupyter.org/github/carnot-technologies/MapVisualizations/blob/master/DatashaderDemo.ipynb)|
| Folium | Partly Interactive Choropleth with TopoJSON | ![](https://github.com/carnot-technologies/MapVisualizations/blob/master/images/GitHub%20Readme%20Images/folium.png) | [Click Here](https://medium.com/@sanghviyash7/471113fa5964?source=friends_link&sk=43df1ce8441cf7010758052ec14c4134)| [Click Here](https://nbviewer.jupyter.org/github/carnot-technologies/MapVisualizations/blob/master/FoliumChoroplethDemo.ipynb)|


## Auxiliary Concepts Covered
Along with the tutorial of each library, several auxiliary concepts and processes are covered in the tutorials. They are listed below, linking to the tutorial in which they are covered.
- [All about Shapefiles](https://medium.com/@sanghviyash7/8adb77a7d14?source=friends_link&sk=f9aefc50ef5019d2dcb1674c8c5ff6d4)
- [Methods of converting Shapefile to GeoJSON](https://medium.com/@sanghviyash7/44e8ad419b97?source=friends_link&sk=a35de50939c1c97e5dc6620c8862fca8)
- [Difference between GeoJSON and TopoJSON](https://medium.com/@sanghviyash7/471113fa5964?source=friends_link&sk=43df1ce8441cf7010758052ec14c4134)
- [Uploading Plotly Visualizations to Chart Studio](https://medium.com/@sanghviyash7/22434cd6a283?source=friends_link&sk=9a30e33b96bc37fbca6d4b68278ab016)
- [Stitching Images to form a video](https://medium.com/@sanghviyash7/9b7b88ef8b6b?source=friends_link&sk=5e1685606eeb5fe3b46a5583ce50c380)
- [Different free base-maps from mapbox](https://medium.com/@sanghviyash7/957dcdbca90b?source=friends_link&sk=26b82e00130e1c95564e02023df8999d)

## Contributing to this repo
All suggestions, feedback and pull requests are welcome. However, please remember the context of this repo before submitting any contributions. This repo is intended to be a helper repo for the series of medium tutorial posts on the different map-based visualization libraries. At the same time, this repo and the blog posts intend to help the users identify the correct library for their user-case, out of all the available options. Finally, when introducing the users to a new library, the USP and the application areas of that library need to be explicitly made clear to the users. Your contributions should align with these objectives in kind and in spirit. 
