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
- Geodatasets

## Repository Structure

```text
global-earthquakes-visualisation/
│
├── README.md
├── requirements.txt
├── .gitignore
│
├── notebooks/
│   └── earthquake_analysis.ipynb
│
├── outputs/
│   ├── static_magnitude_map.png
│   ├── static_depth_map.png
│   └── interactive_map_preview.png
│
└── data/
```

## How to Run This Project

To run this project locally, follow these steps:

1. Clone this repository:

    git clone https://github.com/Satyambhardwaj19/global-earthquakes-visualisation.git

2. Move into the project folder:

    cd global-earthquakes-visualisation

3. Install the required Python packages:

    pip install -r requirements.txt

4. Open the notebook:

    jupyter notebook notebooks/earthquake_analysis.ipynb

The notebook retrieves data directly from the USGS Earthquake Catalog API, so an internet connection is required when running the data retrieval cells.

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

## Project Outputs

### Static Map: Earthquake Magnitude

This map shows the global distribution of earthquakes with marker size and colour used to represent magnitude.

![Static earthquake magnitude map](outputs/static_magnitude_map.png)

### Static Map: Earthquake Depth

This map explores earthquake depth as an additional variable, helping to show where deeper and shallower events occur.

![Static earthquake depth map](outputs/static_depth_map.png)

### Interactive Map Preview

The interactive map allows users to explore individual earthquake events using popups with magnitude, location, depth, and time information.

![Interactive earthquake map preview](outputs/interactive_map_preview.png)

## Key Findings

- Earthquake activity is not evenly distributed across the world.
- Many events are concentrated around tectonically active regions, especially near plate boundaries.
- Larger magnitude earthquakes can be highlighted effectively using marker size and colour.
- Earthquake depth adds useful context because events occur at different depths below the Earth's surface.
- The interactive Folium map makes the project easier to explore because users can inspect individual earthquake events through popups.

These findings show how geospatial data, API retrieval, and interactive visualisation can be combined to communicate spatial patterns clearly.

## Key Skills Demonstrated

- API data retrieval
- JSON and GeoJSON handling
- Data cleaning and preparation
- Geospatial data analysis
- Static and interactive data visualisation
- Communicating insights through maps

## Current Status

This repository currently includes the main project notebook, static map outputs, and an interactive map preview. The project is structured as part of my data science and geospatial visualisation portfolio.

Further improvements will focus on improving the visual design, adding tectonic plate boundary context, and making the project easier to reproduce.

## Project Reflection

This project helped me practise working with real API data, preparing geospatial datasets, and presenting spatial patterns through both static and interactive maps. It also helped me understand how clear documentation and visual outputs can make a data project easier for others to understand.

## Future Improvements

- Add tectonic plate boundary data for stronger geographic context
- Improve the interactive map legend and styling
- Add filters for magnitude, depth, or region
- Compare earthquake activity across multiple years
- Add a small dashboard version using Python dashboard tools
- Include package versions for stronger reproducibility
