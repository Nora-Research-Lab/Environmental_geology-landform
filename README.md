# Landform classification (Weiss 2001 TPI scheme) - Environmental Geology Suite

[![GitHub](https://img.shields.io/badge/GitHub-NORA_Research_Lab-black?logo=github)](https://github.com/Nora-Research-Lab)
[![Hugging Face](https://img.shields.io/badge/HuggingFace-NORA-yellow?logo=huggingface)](https://huggingface.co/NoraResearchLab)

## Overview
This repository hosts the standardized **Landform classification (Weiss 2001 TPI scheme)** dataset, a key component of the Environmental Geology data framework maintained by **NORA Research Lab**. The data is provided as Cloud-Optimized GeoTIFFs (COG) to support high-performance spatial analysis and GeoAI workflows.

## Technical Specifications
- **Parameter:** Landform classification (Weiss 2001 TPI scheme)
- **Units:** 1 summit, 2 upper slope, 3 flat/mid-slope, 4 lower slope, 5 valley
- **Spatial Resolution:** 30m (1 arc-second)
- **CRS:** EPSG:4326 (WGS84)
- **Format:** Cloud-Optimized GeoTIFF (COG)
- **Compression:** ZSTD

## Repository Structure
- `*.tif`: Tiled GeoTIFF files named by their geographic coordinates.
- `README.md`: Dataset documentation and metadata.

## Intended Applications
This dataset is optimized for:
- **GeoAI & Machine Learning:** Feature engineering for terrain-based models.
- **Hydrogeology:** Watershed and drainage analysis.
- **Environmental Modeling:** Hazard assessment and land-use planning.

## Data Pipeline
The data is fetched from the Copernicus GLO-30 source, repaired for geometry artifacts, reprojected if necessary, and converted into cloud-native formats using NORA's automated pipeline.

## Attribution
Derived from Copernicus DEM GLO-30 (c) DLR e.V. 2010-2014 and (c) Airbus Defence and Space GmbH 2014-2018.

## About NORA Research Lab
NORA Research Lab is dedicated to open-science geospatial data standardization.

- **GitHub:** [Nora-Research-Lab](https://github.com/Nora-Research-Lab)
- **Hugging Face:** [NoraResearchLab](https://huggingface.co/NoraResearchLab)
- **Contact:** [LinkedIn](https://www.linkedin.com/company/nora-research-lab)
