## Project: Personalized Appalcart Route Web Map

### Description

This project was designed to create a webmap that displays the bus route of my morning commute to App State's campus.

It's primary function is to display a line feature that corresponds to the route the Appalcart bus takes while highlighting personal landmarks along the route.

The route was created by taking GPX data of the route in Google Maps and converting it to geoJSON format. Using the website, geojson.io, I added custom markers for landmarks along my route. From there, I converted it to Javascript in Atom, and added it into the code for my application.

The route travels between the University Highlands apartment complex and ASU Schaefer center, following along the HWY 105 Bypass, then turning onto HWY 321, and finally onto Rivers Street.

Using an interactive tooltip, users can hover over map markers to display the name of the selected landmark.

All the symbology is displayed using the color yellow-green, identified with the hex code #9ACD32.

#### Libraries

- The Javascript library, Leaflet, can be accessed [here](https://leafletjs.com/download.html).
- Normalize.css, which can be downloaded [here](https://cdnjs.com/libraries/normalize).

#### Data

- Basemap acquired from [Leaflet Providers](https://leaflet-extras.github.io/leaflet-providers/preview/).
- Route information from [Google Maps](https://www.google.com/maps).
- Conversion of route attained from [Maps to GPX](https://mapstogpx.com/).
- geoJSON conversion from [geojson.io](https://geojson.io/#map=2/20.0/0.0).
