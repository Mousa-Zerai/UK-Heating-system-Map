# Interactive Map of Electric Heating Systems

This repository contains an interactive map of properties with various electric heating systems, including **Community Scheme** types, based on the provided dataset.
The map has been generated using Python and the **Folium** library, with marker clustering and category-based color coding for easy visualization.

## Features

- **Marker Clustering**: Properties with electric heating systems are clustered to improve map navigation and performance.
- **Color-Coded Markers**: Each type of electric heating system is represented by a specific color, making it easy to identify different categories on the map.
- **Interactive Map**: The map can be zoomed and panned, and clicking on a marker reveals more information about the property and its heating system.

## How to View the Map

### GitHub Pages (View-Only)
The interactive map is hosted on GitHub Pages and can be viewed at the following URL:
- [View the Map Here](heating_systems_electric_map_with_clusters_all_rows.html)


#### How the Map was Created

The interactive map was generated using the Folium library, which allows for the rendering of interactive maps in Python. Here’s a summary of the steps used to create the map:

####Data Preparation: A dataset containing information on properties with electric heating systems is loaded.
####Geocoding: The geopy library is used to convert property postcodes into latitude and longitude coordinates.
####Marker Clustering: Folium's MarkerCluster plugin is used to group nearby markers to avoid overcrowding on the map.
####Color-Coded Markers: Each type of electric heating system is color-coded using a predefined color scheme for better visualization.
####Custom Legend: A legend was added to explain the meaning of different marker colors on the map.

#### Map Legend

Blue: Room heaters, electric
Green: Air source heat pump, radiators
Red: Boiler and radiators, electric
Orange: Electric storage heaters
Purple: Room heaters, electricity
Pink: Portable electric heaters
Gray: No system present (electric heaters assumed)
Yellow: Electric underfloor heating
Black: Community Scheme

#### Contributions

Feel free to contribute! If you would like to add improvements or new features, please fork the repository and create a pull request with a detailed description of your changes.



![download](https://github.com/user-attachments/assets/2cbc57b0-29b2-4646-9515-4e6d0403dc24)
