# <div align="center">

# 🗺️ Spatial Distribution Analysis of Rural Infrastructure in Sarawak

# A Cartographic Production

# 

# A GIS Portfolio Project by Bayu (Noorfizan Jauraid)

# Demonstrating professional cartographic and spatial data management skills.

# 

# </div>

# <div align="center">

# 

# 

# 

# 

# 

# 

# </div>

# 🧭 1. Overview

# 

# This project presents a research-grade cartographic visualization of rural infrastructure distribution in Sarawak, integrating authoritative GIS datasets from national and global providers. It is designed to demonstrate:

# 

# Competence in GIS data acquisition

# 

# Spatial data preparation

# 

# Professional symbology and map layout design

# 

# Research-oriented documentation and workflow structuring

# 

# This repository forms part of my GIS portfolio and supports my application for a Graduate Research Assistant (GRA) role in geospatial or development-focused research.

# 

# 🎯 2. Objectives

# 

# The aim of this project is to:

# 

# Map and visualize the spatial distribution of key rural infrastructure features.

# 

# Integrate multi-source spatial datasets into a coherent cartographic workflow.

# 

# Produce publication-quality maps aligned with research standards.

# 

# Demonstrate end-to-end GIS project management and documentation.

# 

# 🗺️ 3. Study Area

# 

# Sarawak, Malaysia — the largest state in East Malaysia — characterized by dispersed rural settlements, mountainous terrain, and extensive hydrological networks.

# The mapping extent is defined using the GADM Level 1 administrative boundary.

# 

# 📦 4. Data Sources

# 4.1 Administrative Boundaries 🗂️

# 

# Provider: GADM v4.1

# 

# URL: https://gadm.org

# 

# Levels: L1 (state), L2 (district)

# 

# Format: Shapefile / GeoPackage

# 

# 4.2 Elevation Data — SRTM 1 Arc-Second DEM ⛰️

# 

# Provider: NASA Earthdata

# 

# URL: https://search.earthdata.nasa.gov

# 

# Type: DEM tiles (GeoTIFF)

# 

# Use: Hillshade, elevation visualization

# 

# 4.3 OpenStreetMap (OSM) Infrastructure 🚧

# 

# Provider: Geofabrik (Borneo Extract)

# 

# URL: https://download.geofabrik.de/asia/malaysia.html

# 

# Layers Extracted: Roads, rivers, buildings, landuse, amenities

# 

# 4.4 Land Cover — ESA WorldCover (2021) 🌲

# 

# Provider: ESA

# 

# URL: https://esa-worldcover.org

# 

# Resolution: 10m

# 

# Use: Background land cover context

# 

# 4.5 Population Data (Optional) 👥

# 

# Provider: WorldPop

# 

# URL: https://www.worldpop.org

# 

# Use: Rural population distribution context

# 

# 📁 5. Project Folder Structure

# sarawak-rural-infrastructure-cartography/

# │

# ├── docs/

# │   ├── images/               # Screenshots \& exported figures

# │

# ├── src/

# │   ├── qgis/                 # QGIS project (.qgz) \& style files (.qml)

# │

# ├── data/                     # Local datasets (gitignored)

# │   ├── boundaries/

# │   ├── DEM/

# │   ├── OSM/

# │   ├── landcover/

# │   ├── population/

# │

# ├── .gitignore

# ├── README.md

# └── LICENSE (optional)

# 

# 🔧 6. Workflow Summary

# ✅ Step 1 — Define Area of Interest (AOI)

# 

# Use GADM L1 boundary for the Sarawak extent

# 

# Save screenshot → docs/images/aoi.png

# 

# ✅ Step 2 — Acquire Datasets

# 

# SRTM DEM tiles

# 

# OSM infrastructure

# 

# WorldCover (optional)

# 

# WorldPop (optional)

# 

# ✅ Step 3 — Data Preparation

# 

# Merge DEM tiles

# 

# Clip layers to AOI

# 

# Standardize CRS (EPSG:3857 or EPSG:3375)

# 

# ✅ Step 4 — Cartographic Design in QGIS

# 

# Hillshade generation

# 

# Road hierarchy symbology

# 

# Water and settlement layers

# 

# Label placement

# 

# Layout composition

# 

# ✅ Step 5 — Final Outputs

# 

# Export maps → PNG + PDF

# 

# Store PNG in docs/images/

# 

# 🖼️ 7. Expected Outputs

# 

# 🌄 Hillshade Elevation Map

# 

# 🛣️ Rural Road Network Map

# 

# 🌊 River \& Settlement Map

# 

# 🗺️ Composite Rural Infrastructure Map

# 

# Maps will be added as development progresses.

# 

# 🛠️ 8. Tools

# 

# QGIS 3.x

# 

# GDAL

# 

# NASA Earthdata

# 

# ESA WorldCover

# 

# OpenStreetMap / Geofabrik

# 

# 🙏 9. Acknowledgements

# 

# This project uses open-access datasets provided by NASA, ESA, GADM, OSM contributors, and WorldPop.

# All rights belong to their respective providers.

# 

# <div align="center">

# 

# 📌 Project maintained by Bayu

# For academic and research demonstration purposes.

# 

# </div>

