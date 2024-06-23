# Dryland-Geospatial-Analysis

## Overview
This repository hosts the **Global Dryland Assessment Data Set** and accompanying resources, offering comprehensive geospatial information on dryland regions worldwide. The dataset includes geographic coordinates, aridity zones, land use categories, and tree cover data, essential for understanding the distribution and characteristics of dryland areas, which constitute a significant portion of the Earth's surface.

Meticulously compiled from multiple sources, the dataset has been pre-processed to ensure topological integrity and consistency. The repository features a Jupyter Notebook that documents the data processing steps, metadata, and code used to convert the dataset into a GeoJSON format, making it suitable for use in the Full Lands Integration Tool (FLINT).

## Contents
- **`dryland_assessment.ipynb`**: Jupyter Notebook with data processing code and thorough documentation.
- **`/data`**: Directory containing the source and processed datasets.

## Dataset Description
The Global Dryland Assessment Data Set provides comprehensive information on dryland regions across the globe, including:
- **Geographic Coordinates**: Longitude and latitude of locations.
- **Aridity Zones**: Classification of aridity zones.
- **Land Use Categories**: Various categories of land use.
- **Tree Cover**: Tree cover percentage for different locations.

## Format
- **Extent**: Global coverage
- **Format**: Vector point GeoJSON (.json)
- **Coordinate System**: EPSG:4326 (WGS84)
- **Year**: 2024
- **Size**: Varies depending on the number of points

## Original Source
Compiled from various global dryland assessment studies and reports. The dataset is available in vector point format (Feature Class, GeoJSON).

## License
Users may use and redistribute these data without explicit written permission, provided they adhere to the relevant restrictions and citation requirements. Please consult the data documentation for further information.

## Citation
Global Dryland Assessment Data Set (2024). From [https://www.science.org/doi/10.1126/science.aam6527]

## Metadata
### Columns:
- `location_x`: Longitude of the location
- `location_y`: Latitude of the location
- `dryland_assessment_region`: Name of the dryland assessment region
- `Aridity_zone`: Aridity zone classification
- `land_use_category`: Land use category of the location
- `tree_cover`: Tree cover percentage

## Notes
- **Known Issues**: Ensure the consistency of tree cover data across different regions and years. Potential discrepancies in land use categories due to different classification systems in source data.
- **Processing**: The dataset was transformed to EPSG:4326 (WGS84) and saved as GeoJSON format. The coordinates and attribute data were checked for consistency and accuracy.


