# Tehran Local Climate Zone Mapping

Remote-sensing-based mapping of Tehran’s Local Climate Zones using Landsat 8 imagery and GIS software.

## Project Overview

This individual project aimed to map the Local Climate Zones (LCZs) of Tehran using Landsat 8 satellite imagery from 2018 with a spatial resolution of 30 meters. The workflow combined ENVI, SAGA GIS, and ArcGIS for image preparation, LCZ classification, accuracy assessment, and final map production.

The final classification identified 15 of the 17 standard LCZ classes across the study area.

## Objectives

- Produce a Local Climate Zone map of Tehran.
- Classify different urban forms and land-cover types.
- Evaluate the reliability of the final classification.
- Export the results in GIS and Google Earth formats.

## Data and Software

| Item | Details |
|---|---|
| Satellite data | Landsat 8 imagery |
| Image year | 2018 |
| Spatial resolution | 30 m |
| ENVI | Satellite image preparation and preprocessing |
| SAGA GIS | Local Climate Zone classification |
| ArcGIS | Accuracy assessment, spatial analysis, and final map preparation |

## Workflow

1. Preparation and preprocessing of Landsat 8 imagery in ENVI.
2. Preparation of 515 training polygons.
3. Local Climate Zone classification in SAGA GIS.
4. Spatial analysis and final map preparation in ArcGIS.
5. Accuracy assessment using 363 reference samples.
6. Export of the final results as GeoTIFF and KMZ files.

## Results

- **Identified LCZ classes:** 15
- **Training polygons:** 515
- **Accuracy-assessment samples:** 363
- **Overall Accuracy:** 84.30%
- **Kappa Coefficient:** 0.83

## Repository Contents

- [`TEHRAN_LCZ_MAP.tif`](./TEHRAN_LCZ_MAP.tif) — Final LCZ map in GeoTIFF format.
- [`tehran_lcz_map.kmz`](./tehran_lcz_map.kmz) — Final map for visualization in Google Earth.
- [`accuracy_assessment.txt`](./accuracy_assessment.txt) — Confusion matrix and detailed accuracy-assessment results.

## Data Availability

This repository contains the principal project outputs. Raw satellite imagery and original training and testing datasets are not included because of file-size and data-sharing considerations.

## Author

**Ali Moeinkhah**

This project was completed independently.
