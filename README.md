# Terra Cluster Explorer

## Overview
This notebook processes Sentinel-2 satellite imagery to generate visualizations, perform land cover clustering, and create timelapse animations using Google Earth Engine (GEE) and geemap.

## Features
- **Timelapse GIF**: Creates a Landsat timelapse (1984–2022) for a user-defined region.
- **Median Composite**: Generates a noise-reduced composite for analysis.
- **Land Cover Clustering**: Uses KMeans to classify land into clusters (e.g., water, vegetation, snow).
- **Vector Export**: Converts clustered data to shapefiles for GIS use.
- **Interactive Maps**: Visualizes clusters and composites with dynamic layers and legends.

## Usage
1. **Setup**: Install Earth Engine and geemap libraries, and configure GEE credentials.
2. **Define ROI**: Set the region of interest (ROI) on the interactive map.
3. **Run Notebook**: Execute cells to process imagery and visualize results.
4. **Export**: Download clustered vectors or generated images for further analysis.

## Outputs
- **Timelapse**: A GIF showcasing temporal changes.
- **Clustered Map**: Interactive map with color-coded land cover clusters.
- **Vectorized Polygons**: Shapefiles for GIS post-processing.

## Tools
- **Google Earth Engine**: Data processing.
- **Geemap**: Mapping and visualization.
- **Python Libraries**: `ee`, `geemap`.
