# web_mapping
Creating a map using Folium
This script uses the Folium library in Python to create an interactive map that shows the location and elevation of volcanoes around the world. The map also displays the population of different countries using GeoJSON data.

Requirements
To run this script, you will need:

Python 3.x
pandas
folium
Usage
Download the Volcanoes.txt and world.json files.
Save the script to a Python file (e.g. map.py).
Open a terminal or command prompt and navigate to the directory containing the script and data files.
Run the script using python map.py.
The script will generate an HTML file called Map1.html in the same directory.
Open the HTML file in a web browser to view the interactive map.
Map Features
The map displays the following features:

The location and elevation of volcanoes around the world. The color of each volcano marker indicates its elevation, with pink markers indicating elevations less than 1000 meters, red markers indicating elevations between 1000 and 3000 meters, and light blue markers indicating elevations greater than 3000 meters.

The population of different countries. The color of each country indicates its population, with green indicating populations less than 10 million, orange indicating populations between 10 and 20 million, and red indicating populations greater than 20 million.

Customization
You can customize the map by modifying the following parameters:

location: the starting location of the map (default is [35.58, -80.99])
zoom_start: the starting zoom level of the map (default is 6)
tiles: the type of map tiles to use (default is "Stamen Terrain")
radius: the size of the volcano markers (default is 6)
fill_color: the color of the volcano markers (determined by the color_producer function)
color: the color of the volcano marker borders (default is grey)
fill_opacity: the opacity of the volcano markers (default is 0.7)
style_function: the function used to style the GeoJSON data (determined by the lambda function in fgp.add_child())
name: the name of the feature group (used for the layer control)
References
Folium documentation
GeoJSON data from Natural Earth
