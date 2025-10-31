# Spatial-Distribution-of-Rural-Infrastructure-in-Sarawak



A cartographic visualization of rural infrastructure distribution in Sarawak.

Spatial Distribution Analysis of Rural Infrastructure in Sarawak: A Cartographic Production



1\. Overview

This project presents a professional cartographic visualization of rural infrastructure distribution in Sarawak, integrating authoritative datasets from global and national sources. The objective is to demonstrate technical competency in GIS data acquisition, spatial data preparation, symbology design, and map layout production, aligned with research-grade standards expected for graduate-level work.



This repository forms part of a broader GIS portfolio showcasing analytical and cartographic capabilities relevant to development planning, rural studies, and spatial policy research.



2\. Objectives



This project aims to:



Map and visualize the spatial distribution of key rural infrastructure features in Sarawak.



Integrate multiple datasets (boundaries, elevation, transportation networks, settlements, land cover) into a coherent cartographic workflow.



Produce publication-ready map layouts following recognized cartographic principles.



Demonstrate the ability to manage, clean, and prepare GIS datasets for spatial analysis.



3\. Study Area



Sarawak, Malaysia — the largest state in East Malaysia — characterized by dispersed rural settlements, mountainous terrain, complex river networks, and wide variations in accessibility.

The cartographic extent follows the full administrative boundary of Sarawak (GADM Level 1).



4\. Data Sources



All datasets used in this project are openly licensed for academic and non-commercial use.

Below is the complete data inventory.



4.1 Administrative Boundaries



Source: GADM v4.1



URL: https://gadm.org



Data Used: Level 1 (states), Level 2 (districts)



Format: Shapefile / GeoPackage



Purpose: Define the project boundary and AOI mask.



4.2 Elevation (DEM – SRTM 1 Arc-Second)



Source: NASA Earthdata



URL: https://search.earthdata.nasa.gov



Tiles Required: All SRTM tiles covering Sarawak



Format: GeoTIFF



Purpose: Hillshade, elevation backdrop, terrain context.



4.3 OpenStreetMap (OSM) Infrastructure



Source: Geofabrik – Borneo Extract



URL: https://download.geofabrik.de/asia/malaysia.html



Layers Extracted:



Roads (primary, secondary, tertiary, residential)



Rivers



Buildings (optional for density mapping)



Landuse



Points of interest (schools, clinics, etc.)



Format: Shapefile / PBF



Purpose: Feature-level infrastructure visualization.



4.4 Land Cover



Dataset: ESA WorldCover 2021 (10m)



Source: ESA



URL: https://esa-worldcover.org



Format: GeoTIFF



Purpose: Contextual base for terrain and land-use patterns.



4.5 Population (Optional for Future Analysis)



Dataset: WorldPop Malaysia 2020



Source: WorldPop



URL: https://www.worldpop.org



Format: GeoTIFF



Purpose: Settlement patterns and rural population context.



5\. Project Folder Structure

sarawak-rural-infrastructure-cartography/

│

├── docs/

│   ├── images/               # Screenshots of AOI, DEM tiles, map layouts

│

├── src/

│   ├── qgis/                 # QGIS project files (.qgz), styles (.qml)

│

├── data/                     # Local data storage (excluded from GitHub)

│   ├── boundaries/

│   ├── DEM/

│   ├── OSM/

│   ├── landcover/

│   ├── population/

│

├── .gitignore                # Prevents large datasets from being uploaded

├── README.md                 # Project documentation

└── LICENSE (optional)



6\. Workflow Summary



Define Area of Interest (AOI)



Using GADM Sarawak boundary



Save screenshot for documentation



Acquire datasets



SRTM tiles downloaded using bounding boxes



OSM layers using Geofabrik Borneo region



Land cover and population rasters (optional)



Data preparation (not in GitHub due to size)



Merge DEM tiles



Clip DEM to AOI



Reproject all data to a consistent CRS (EPSG:3857 or EPSG:3375)



Cartographic design



Apply symbology to roads, rivers, DEM hillshade



Use layer blending and transparency



Incorporate labels (districts, major towns)



Design legend, scale bar, and north arrow



Export final maps



Save as PNG and PDF



Upload PNG versions to docs/images/



7\. Outputs



Final cartographic deliverables include:



Hillshade Elevation Map of Sarawak



Rural Road Network Map



Rivers and Settlements Distribution Map



Composite Rural Infrastructure Map (Final)



Each output will be added as development progresses.



8\. Tools Used



ArcGIS Pro



QGIS 3.x (primary)



GDAL



ESA WorldCover



NASA Earthdata SRTM Server



OpenStreetMap / Geofabrik



9\. Acknowledgements



Datasets are sourced from ESA, NASA, WorldPop, and OSM contributors.

All rights and licenses belong to their respective providers.

