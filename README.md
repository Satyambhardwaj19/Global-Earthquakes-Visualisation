# Global Earthquakes Visualisation

## Overview

This project analyses and visualises global earthquake activity using data from the USGS Earthquake Catalog API. The aim is to explore how earthquake magnitude, location, and depth can be represented through static and interactive geospatial visualisations.

The project uses Python to retrieve and prepare earthquake data, then creates maps to communicate spatial patterns in a clear and accessible way.

## Tools Used

- Python
- pandas
- GeoPandas
- Matplotlib
- Folium
- requests
- USGS Earthquake Catalog API

## Dataset

The data comes from the USGS Earthquake Catalog API. The project focuses on global earthquake events from 2025 with magnitude 4.5 and above.

Key variables used include:

- Magnitude
- Latitude
- Longitude
- Depth
- Place
- Time

## What I Did

- Retrieved earthquake data from the USGS API
- Converted GeoJSON data into a pandas DataFrame
- Prepared spatial data using GeoPandas
- Created static earthquake maps using Matplotlib
- Created an interactive map using Folium
- Used marker size and colour to represent earthquake magnitude
- Added popups to show additional earthquake details

## Key Skills Demonstrated

- API data retrieval
- JSON and GeoJSON handling
- Data cleaning and preparation
- Geospatial data analysis
- Static and interactive data visualisation
- Communicating insights through maps

## Current Status

This repository is being developed as part of my data science and geospatial visualisation portfolio. More code, outputs, and project explanations will be added as the project is cleaned and structured.

## Future Improvements

- Add more detailed map styling
- Add screenshots of the static and interactive maps
- Add a cleaner project notebook
- Add explanation of the main findings
- Add requirements file for reproducibility
