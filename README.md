## Final Map Output

![EV Density Map](images/tampa_ev_density_map.png)

# EV Charging Station Density Analysis — Tampa, FL

GIS + Python analysis of EV charging station density in Tampa, Florida using GeoPandas and QGIS.

## Overview
This project analyzes the spatial distribution of EV charging stations in Florida, then focuses on Tampa to identify clustering patterns using kernel density analysis.

## Tools Used
- Python
- Pandas
- GeoPandas
- Jupyter Notebook
- QGIS
- OpenStreetMap

## Workflow
1. Download EV charging station data from AFDC
2. Clean and filter the dataset in Python
3. Convert tabular data into GeoJSON using GeoPandas
4. Visualize the statewide dataset in QGIS
5. Filter Tampa stations
6. Perform kernel density analysis in QGIS
7. Export a final map layout

## Outputs
- Cleaned GeoJSON dataset
- Tampa-focused EV station layer
- Kernel density raster
- Final PDF map

## Key Insight
The analysis shows stronger EV charging station clustering in central Tampa urban corridors, with lower density toward outlying areas.