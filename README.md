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
- [Comparison of the libraries](https://medium.com/@yash.sanghvi/map-based-visualization-libraries-for-python-comparison-and-tutorials-85cf53cf5503?source=friends_link&sk=5b87634eb972862947d0e69049245c41)
- [Auxiliary Concepts Covered](#auxiliary-concepts-covered)
- [Contributing to this repo](#contributing-to-this-repo)


## About
Map-based visualizations are an essential aspect of any data-presentation/ inference. Geo-spatial visualizations become all the more important for IoT companies like Carnot which have their devices scattered across different geographies. We at Carnot realized the need for having a robust map-based visualization infrastructure for all our present and future requirements. When we started building this infrastructure, we realized that there are way too many libraries available for map visualizations and several detailed tutorials for each library. However, what wasn't readily available was a comparison of the different libraries and a guide on which library is best suited for a particular application. 

Hence, we started off with one library at a time, determined what it was best suited for, and then moved on to the next. We kept doing this exercise till we generated nearly all the types of visualizations we could envision. This repo is a helper repo for the series of Medium blog posts on map-based visualizations, where we share a summary of our learning during this entire exercise. It will hopefully serve as a guide to people who find themselves as overwhelmed with choices as we were at the start of our infra-building exercise.

In order to get an overview and comparison of different libraries, [Click Here](https://medium.com/@yash.sanghvi/map-based-visualization-libraries-for-python-comparison-and-tutorials-85cf53cf5503?source=friends_link&sk=5b87634eb972862947d0e69049245c41).

## Types of Visualizations
- Scatter
- Choropleth

## Libraries Covered
| Library  | Visualization Covered | Visualization Preview | Tutorial |
| :---:  | :---:  | :---:  | :---:  |
| Cartopy | Scatter with custom map background | ![](https://github.com/carnot-technologies/MapVisualizations/blob/master/images/GitHub%20Readme%20Images/cartopy.png)| [Click Here](https://medium.com/@yash.sanghvi/time-lapse-scatter-map-visualization-using-cartopy-c12400494afd?source=friends_link&sk=f2e6023a68dd5986af45e73af12bc55b) |
| GeoPandas | Choropleth with shapefile | ![](https://github.com/carnot-technologies/MapVisualizations/blob/master/images/GitHub%20Readme%20Images/geopandas.png) | [Click Here](https://medium.com/@yash.sanghvi/2d9427530589?source=friends_link&sk=28635565cb5b991591b140d417c1df00)
| Plotly | Interactive Choropleth with GeoJSON | ![](https://github.com/carnot-technologies/MapVisualizations/blob/master/images/GitHub%20Readme%20Images/plotly.png)| [Click Here](https://medium.com/@yash.sanghvi/8a7adc417a2?source=friends_link&sk=ca185544ba874209a3b58abcc4292fb6) |
| Plotly + Mapbox | Interactive Choropleth with GeoJSON and base-map | ![](https://github.com/carnot-technologies/MapVisualizations/blob/master/images/GitHub%20Readme%20Images/mapbox2.PNG) | [Click Here](https://medium.com/@yash.sanghvi/24be9a586b28?source=friends_link&sk=3aed429c6044a580c6de0847f40787cc) |
| Plotly + Mapbox | Interactive Scatter with base-map | ![](https://github.com/carnot-technologies/MapVisualizations/blob/master/images/GitHub%20Readme%20Images/mapbox1.PNG) | [Click Here](https://medium.com/@yash.sanghvi/a6afec285351?source=friends_link&sk=9e6413838dd34cb051abc63f61829eb0) |
| Plotly + Datashader | Partly Interactive Large-data Scatter with base-map | ![](https://github.com/carnot-technologies/MapVisualizations/blob/master/images/GitHub%20Readme%20Images/datashader.PNG) | [Click Here](https://medium.com/@yash.sanghvi/a50b5fbd851b?source=friends_link&sk=b6a16a548c38ec12f9255a5571a0322c)|
| Folium | Partly Interactive Choropleth with TopoJSON | ![](https://github.com/carnot-technologies/MapVisualizations/blob/master/images/GitHub%20Readme%20Images/folium.png) | [Click Here](https://medium.com/@yash.sanghvi/b65278619c65?source=friends_link&sk=fbabdc341eec78dfd5aac2b539b239e6)|


## Auxiliary Concepts Covered
Along with the tutorial of each library, several auxiliary concepts and processes are covered in the tutorials. They are listed below, linking to the tutorial in which they are covered.
- [All about Shapefiles](https://medium.com/@yash.sanghvi/2d9427530589?source=friends_link&sk=28635565cb5b991591b140d417c1df00)
- [Methods of converting Shapefile to GeoJSON](https://medium.com/@yash.sanghvi/8a7adc417a2?source=friends_link&sk=ca185544ba874209a3b58abcc4292fb6)
- [Difference between GeoJSON and TopoJSON](https://medium.com/@yash.sanghvi/b65278619c65?source=friends_link&sk=fbabdc341eec78dfd5aac2b539b239e6)
- [Uploading Plotly Visualizations to Chart Studio](https://medium.com/@yash.sanghvi/a6afec285351?source=friends_link&sk=9e6413838dd34cb051abc63f61829eb0)
- [Stitching Images to form a video](https://medium.com/@yash.sanghvi/time-lapse-scatter-map-visualization-using-cartopy-c12400494afd?source=friends_link&sk=f2e6023a68dd5986af45e73af12bc55b)
- [Different free base-maps from mapbox](https://medium.com/@yash.sanghvi/24be9a586b28?source=friends_link&sk=3aed429c6044a580c6de0847f40787cc)

## Contributing to this repo
All suggestions, feedback and pull requests are welcome. However, please remember the context of this repo before submitting any contributions. This repo is intended to be a helper repo for the series of medium tutorial posts on the different map-based visualization libraries. At the same time, this repo and the blog posts intend to help the users identify the correct library for their user-case, out of all the available options. Finally, when introducing the users to a new library, the USP and the application areas of that library need to be explicitly made clear to the users. Your contributions should align with these objectives in kind and in spirit. 
