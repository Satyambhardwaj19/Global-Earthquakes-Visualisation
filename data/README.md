# Data

This project retrieves earthquake data directly from the USGS Earthquake Catalog API.

The dataset is not stored permanently in this repository because the notebook can request the data directly from the API. This keeps the repository lightweight and makes the workflow easier to reproduce.

## Dataset Source

- Source: USGS Earthquake Catalog API
- Format: GeoJSON
- Time period: 2025
- Minimum magnitude: 4.5
- Geographic coverage: Global

## Main Variables Used

- `mag` - earthquake magnitude
- `place` - location description
- `time` - earthquake event time
- `longitude` - x-coordinate
- `latitude` - y-coordinate
- `depth_km` - earthquake depth in kilometres

## Note

The notebook contains the full workflow for retrieving, preparing, and analysing the data.
