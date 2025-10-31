# 📍Spatial Distribution Analysis of Rural Infrastructure in Sarawak



### A GIS Portfolio Project by Bayu (Noorfizan Jauraid)

###### 

###### 

### 🧭 1. Overview

#### 

#### This project presents a professional cartographic visualization of rural infrastructure distribution in Sarawak, integrating authoritative datasets from national and global providers. The objective is to demonstrate technical competency in:

#### 

* #### GIS data acquisition

#### 

* #### Spatial data preparation

#### 

* #### Cartographic design

#### 

* #### Research-oriented documentation

#### 

#### This repository is part of a broader GIS portfolio developed to showcase academic-grade spatial analysis skills, aligning with expectations for Graduate Research Assistant (GRA) positions.

#### 

### 🎯 2. Objectives

#### 

#### This project aims to:

#### 

* #### Map and visualize the spatial distribution of key rural infrastructure features in Sarawak.

#### 

* #### Integrate multiple datasets (boundaries, elevation, transportation, settlements, land cover).

#### 

* #### Produce publication-ready cartographic outputs using professional mapping standards.

#### 

* #### Demonstrate data management, layer styling, and compositing in QGIS.

#### 

### 🗺️ 3. Study Area

#### 

#### Sarawak, Malaysia — the largest state in East Malaysia — characterized by dispersed rural settlements, mountainous terrain, and complex river networks.

#### The map extent follows Sarawak’s Level 1 GADM boundary.

#### 

### 📦 4. Data Sources

#### 

#### All datasets used in this project are openly available and licensed for academic use.

#### 

#### 4.1 Administrative Boundaries 🗂️

#### 

#### Provider: GADM v4.1

#### 

#### URL: https://gadm.org

#### 

#### Levels Used: L1 (state), L2 (district)

#### 

#### Format: Shapefile / GeoPackage

#### 

#### 4.2 Elevation (SRTM 1 Arc-Second DEM) ⛰️

#### 

#### Provider: NASA Earthdata

#### 

#### URL: https://search.earthdata.nasa.gov

#### 

#### Format: GeoTIFF tiles

#### 

#### Purpose: Hillshade generation, terrain context

#### 

#### 4.3 OpenStreetMap (OSM) Infrastructure 🚧

#### 

#### Provider: Geofabrik (Borneo extract)

#### 

#### URL: https://download.geofabrik.de/asia/malaysia.html

#### 

#### Layers Used:

#### 

* #### Roads

#### 

* #### Rivers

#### 

* #### Buildings

#### 

* #### Landuse

#### 

* #### Schools

#### 

* #### Clinics

#### 

* #### Amenities

#### 

#### 4.4 Land Cover (ESA WorldCover 2021) 🌲

#### 

#### Provider: ESA

#### 

#### URL: https://esa-worldcover.org

#### 

#### Format: 10m GeoTIFF

#### 

#### 4.5 Population (Optional) 👥

#### 

#### Provider: WorldPop

#### 

#### URL: https://www.worldpop.org

#### 

#### Format: 100m GeoTIFF

#### 

### 📁 5. Project Folder Structure

#### sarawak-rural-infrastructure-cartography/

#### │

#### ├── docs/

#### │   ├── images/               # ✅ Project screenshots \& figure outputs

#### │

#### ├── src/

#### │   ├── qgis/                 # ✅ QGIS project (.qgz) \& styles (.qml)

#### │

#### ├── data/                     # ✅ Local datasets (ignored by GitHub)

#### │   ├── boundaries/

#### │   ├── DEM/

#### │   ├── OSM/

#### │   ├── landcover/

#### │   ├── population/

#### │

#### ├── .gitignore               

#### ├── README.md                

#### └── LICENSE (optional)

#### 

### 🔧 6. Workflow Summary

#### ✅ Step 1 — Define Area of Interest (AOI)

#### 

#### Using GADM L1 boundary

#### 

#### AOI screenshot stored in docs/images/

#### 

#### ✅ Step 2 — Download datasets

#### 

#### SRTM DEM tiles from NASA Earthdata

#### 

#### OSM infrastructure layers from Geofabrik

#### 

#### Optional: Land cover + population

#### 

#### ✅ Step 3 — Prepare GIS data

#### 

#### Merge + clip DEM

#### 

#### Reproject all layers to consistent CRS (EPSG:3857/3375)

#### 

#### Clean and standardize attribute fields

#### 

#### ✅ Step 4 — Cartographic Design in QGIS

#### 

#### Hillshade + DEM blending

#### 

#### Road and river hierarchy styling

#### 

#### District label placement

#### 

#### Legend, scale bar, north arrow

#### 

#### ✅ Step 5 — Export Maps

#### 

#### Save as PNG and PDF

#### 

#### Upload PNG into docs/images/

#### 

### 🖼️ 7. Outputs

#### 

#### Final visual products will include:

#### 

* #### 🌄 Hillshade Elevation Map

#### 

* #### 🛣️ Rural Road Network Map

#### 

* #### 🌊 River Network \& Settlement Map

#### 

* #### 🗺️ Final Composite Infrastructure Map

#### 

#### (All outputs added progressively as project develops.)

#### 

#### 🛠️ 8. Tools Used

#### 

* #### ArcGIS Pro



* #### QGIS 3.x



* #### GDAL



* #### NASA Earthdata



* #### ESA WorldCover



* #### OpenStreetMap / Geofabrik

#### 

### 🙏 9. Acknowledgements

#### 

#### Datasets provided by ESA, NASA, WorldPop, GADM, and OpenStreetMap contributors.

All rights belong to their respective providers.

📌 Project maintained by Noorfizan Jauraid
---

#### For academic and research demonstration purposes.

