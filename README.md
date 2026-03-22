# campus-spatial-mapping-bvdu
GIS-based campus mapping and dashboard project using ArcGIS Online, including buildings, roads, and student services data for Bharati Vidyapeeth University.
# University Campus Spatial Dataset – BVDU Dhankawadi Campus

## Overview

This repository contains a structured geospatial dataset representing key infrastructure and facilities within the Bharati Vidyapeeth Deemed University, Dhankawadi (Katraj) campus. The dataset has been prepared as part of a GIS-based campus mapping and dashboard integration project.

The data includes building footprints, road networks, and points of interest such as ATMs, canteens, and guard houses. All datasets are provided in GeoJSON format for easy integration with GIS platforms such as ArcGIS Online, QGIS, ArcGIS and web mapping applications.

---

## Dataset Contents

The repository includes the following files:

* **Buildings.geojson**

  * Geometry: Polygon / Point
  * Attributes:

    * Name (Building Name / College Name)
    * Function (Academic / Medical / Residential / Administrative)
    * Height (Building height in meters)

* **Roads.geojson**

  * Geometry: LineString
  * Attributes:

    * Name (Road Name)
    * Surface (Asphalt / Pavers)
    * Width (Estimated road width)

* **Points_of_Interest.geojson**

  * Geometry: Point
  * Includes:

    * ATMs
    * Canteens
    * Guard Houses
  * Attributes:

    * Name
    * Type (ATM / Canteen / GuardHouse)
    * Additional details (e.g., status, capacity, shift type)

---

## Coordinate Reference System (CRS)

* **WGS 84 (EPSG:4326)**
  All spatial data is stored in geographic coordinates using latitude and longitude.

---

## Data Collection & Processing

* Spatial features were digitized and organized using GIS tools.
* Data structuring, cleaning, and formatting were performed to ensure compatibility with ArcGIS Online and dashboard applications.
* Attributes were standardized across all feature classes for consistency and usability.

---

## Height Information

* Building heights are included as a dedicated attribute (`Height_m`).
* Heights are represented in meters and are intended for visualization, comparison, and dashboard filtering purposes.

---

## Data Quality & Validation

The dataset has undergone the following checks:

* Topology validation (closed building polygons, connected road networks)
* Attribute completeness (no null values in critical fields such as height)
* Geometry validation using GeoJSON standards

---

## Applications

This dataset can be used for:

* Campus infrastructure mapping
* Smart campus planning
* Dashboard visualization (ArcGIS Dashboards)
* Spatial analysis and decision-making

---

## Disclaimer

This dataset is intended for academic and educational use. While care has been taken to ensure logical consistency and usability, minor spatial or attribute-level variations may exist.

---

## Author

Prepared as part of a GIS academic assignment on
**University Campus Spatial Mapping & Dashboard Integration**

---

## Usage

You are free to use this dataset for:

* Academic projects
* Learning GIS workflows
* Visualization and dashboard creation

Proper attribution is appreciated.
