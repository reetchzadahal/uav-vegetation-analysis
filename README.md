# UAV Vegetation Analysis using NDVI, NDRE, and GNDVI

## Overview

This project demonstrates vegetation health analysis using high-resolution UAV imagery. The drone images were processed into an orthomosaic and analyzed using vegetation indices to assess plant health and variability.


## Data Acquisition

* **Platform:** UAV (Drone)
* **Processing Software:** Agisoft Metashape
* **Output:** Orthomosaic (GeoTIFF)
* **Study Area:** Greenhouse Area in AIT


## Workflow

### 1. Image Processing

* Captured aerial images using UAV
* Processed images in Agisoft Metashape:

  * Image alignment
  * Dense point cloud generation
  * Orthomosaic creation

### 2. GIS Analysis

Performed in ArcGIS:

* Imported orthomosaic
* Calculated vegetation indices using raster calculator


## Vegetation Indices

### NDVI (Normalized Difference Vegetation Index)

Used to measure vegetation health.

### NDRE (Normalized Difference Red Edge)

Sensitive to chlorophyll content and plant stress.

### GNDVI (Green Normalized Difference Vegetation Index)

Useful for detecting variations in crop nitrogen levels.


## Results

### Orthomosaic

![Orthomosaic](outputs/orthomosaic.png)

### NDVI Map

![NDVI](outputs/ndvi.png)

### NDRE Map

![NDRE](outputs/ndre.png)

### GNDVI Map

![GNDVI](outputs/gndvi.png)


## Key Insights

* NDVI highlights general vegetation health across the study area
* NDRE provides early detection of plant stress
* GNDVI shows variation in chlorophyll and nitrogen levels
* High-resolution UAV data improves analysis accuracy compared to satellite imagery


## Tools & Technologies

* ArcGIS (Raster Analysis)
* Agisoft Metashape (Photogrammetry)
* UAV Drone Imagery


## Contact

Richa Dahal
[linkedin.com/in/richa-dahal/](https://www.linkedin.com/in/richa-dahal/)
