# NDVI-Urban-Insurance
Parametric insurance using NDVI for green zones in Mumbai, Jakarta, Manila, Nairobi
# NDVI-Based Parametric Insurance for Urban Green Zones

This repository contains code and data to reproduce the analysis for four cities—Mumbai, Jakarta, Manila, and Nairobi—where NDVI stress is used as a parametric insurance trigger.

## Contents
- `scripts/gee/`: Google Earth Engine scripts for NDVI, NDWI, NBR extraction
- `scripts/analysis/`: R scripts for threshold detection and basis risk analysis
- `qgis_project/`: QGIS project and exported map figures
- `results/`: Figures and tables used in the final paper

## Reproduce in GEE
Copy and paste the code in `scripts/gee/ndvi_extraction.js` to [GEE Code Editor](https://code.earthengine.google.com/).

## Map Visualization
Open `qgis_project/project.qgz` to recreate the green zone trigger maps. Requires QGIS 3.22+ and GDAL.
