# High-Resolution Mapping of Travel Time to Emergency Obstetric and Neonatal Care in East Java, Indonesia

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.XXXXXXXX.svg)](https://doi.org/10.5281/zenodo.XXXXXXXX)

## Overview

This repository contains the Python code and analytical workflow for the study: **"High-resolution mapping of closer-to-reality travel time to Emergency Obstetric and Neonatal Care Facility in East Java, Indonesia: a population-based spatial analysis."**

The primary goal of this project is to calculate and map high-resolution, realistic travel times from population centers to the nearest Emergency Obstetric and Neonatal Care (EONC) facilities across the East Java province. The code processes geospatial data to produce the final analysis presented in our research.

### Associated Publication
This code supports our manuscript, currently in preparation

## Data Sources
The analysis relies on several key datasets. All data must be downloaded and placed in the designated `/data` directory before running the analysis.

1.  **Population Data:** High-resolution population density maps from Meta, available via the [Humanitarian Data Exchange (HDX)](https://data.humdata.org/dataset/indonesia-high-resolution-population-density-maps-demographics).
2.  **Road Network:** OpenStreetMap (OSM) data for Indonesia, obtained from [Geofabrik](https://download.geofabrik.de/asia/indonesia.html).
3.  **Health Facilities:** A list of EONC facilities in East Java derived from the East Java Health Profile Year 2023.
4.  **Administrative Boundaries:** Shapefile for East Java's administrative regions, sourced from [GADM](https://gadm.org/download_country.html).

## Requirements

### Software and Libraries

This analysis was performed using Python 3.9+. The specific libraries are listed in the `requirements.txt` file.

* `geopandas`
* `pandas`
* `pyproj`
* `shapely`
* `fiona`
* `scikit-learn`
* `matplotlib`
* `r5py`
* `folium`
* `googlemaps`

### System Dependencies

* **Java Development Kit (JDK) v21 or newer:** Required by the `r5py` library.

## Repository Structure
├── EONC_Travel_Time_Analysis.ipynb   # Main Jupyter Notebook with the analysis
├── data/                               # Folder for storing input data (needs to be populated by user)
├── outputs/                            # Folder for generated maps and result files
├── README.md                           # This file
├── requirements.txt                    # List of Python packages for installation
└── LICENSE                             # Repository license

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## How to Cite

If you use this code in your research, please cite both the repository and our associated paper.

## Contact

For any questions regarding the code or the study, please contact Muhammad Rizky Widodo at rizkywidodo.muhammad@gmail.com
