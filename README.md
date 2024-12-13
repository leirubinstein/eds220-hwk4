# Visualizing Fire Scars Through False Color
*This repository was produced as a part of the UCSB MEDS program for EDS 220: Working with Environmental Datasets.*

## About
This repository contains a notebook `bii-phoenix.ipynb` analyzing Biodiversity Intactness Index change in Phoenix, AZ. This exercise involves:
- `rioxarray` raster manipulation
- `STAC` specification
- API catalog search
- boolean operations

![Phoenix Urban Sprawl image by ArcGIS](images/phoenix-sprawl.jpg)

## Repository Structure
```
eds220-final-project
│   README.md
|   bii-phoenix.ipynb
|   .gitignore
│
└───data
    └───tl_2022_04_cousub
└───images
    │   phoenix-sprawl.jpg
```
## Data
Biodiversity data was obtained from Microsoft Planetary Computer's STAC collection. The Phoenix shapefile was obtained from the US Census Bureau.

## References
- F. Gassert, J. Mazzarello, and S. Hyde, “Global 100m Projections of Biodiversity Intactness for the years 2017-2020 [Technical Whitepaper].” Aug. 2022. Available: https://ai4edatasetspublicassets.blob.core.windows.net/assets/pdfs/io-biodiversity/Biodiversity_Intactness_whitepaper.pdf

- U.S. Census Bureau. (2022). TIGER/Line Shapefiles: County Subdivisions, Arizona. Retrieved from https://www.census.gov/cgi-bin/geo/shapefiles/index.php?year=2022&layergroup=County+Subdivisions