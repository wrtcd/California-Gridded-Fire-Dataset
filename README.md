# California Gridded Fire Dataset (2012–2024)

This repository contains a shapefile representing gridded wildfire statistics for the state of California, derived from NASA VIIRS fire detections between 2012 and 2024. The data are aggregated to a uniform 0.5-degree spatial grid to support spatial analysis of wildfire frequency, intensity, and distribution.

## Dataset Overview

- **Source:** NASA FIRMS – VIIRS Active Fire Product  
- **Region:** California, USA  
- **Format:** ESRI Shapefile (.shp, .shx, .dbf, etc.)  
- **Years Covered:** 2012 to 2024  
- **Grid Resolution:** 0.5-degree cells (approx. 55 km at equator)

Each grid cell contains yearly attributes summarizing fire activity across a 13-year period.

## Attributes

Each record includes the following fields for each year:

- `YYYY_FC` – Fire Count  
- `YYYY_FRP_S` – Sum of Fire Radiative Power (FRP)  
- `YYYY_FRP_M` – Mean Fire Radiative Power (FRP)  

Where `YYYY` ranges from 2012 to 2024.

Example:

- `2012_FC`, `2012_FRP_S`, `2012_FRP_M`  
- `2013_FC`, `2013_FRP_S`, `2013_FRP_M`  
- ...  
- `2024_FC`, `2024_FRP_S`, `2024_FRP_M`

## Applications

- Identifying high-frequency and high-intensity fire zones
- Long-term spatial trend analysis of wildfire activity
- Supporting fire risk assessments, land management, and policy planning

## Source

- NASA FIRMS VIIRS: https://firms.modaps.eosdis.nasa.gov/

## License

This dataset is derived from publicly available NASA VIIRS fire data. Please cite NASA FIRMS appropriately when using or referencing this dataset.
