# Visualizing fire scars through false color
*This repository was produced as a part of the UCSB MEDS program for EDS 220: Working with Environmental Datasets.*

## About
This repository contains two notebooks `hwk4-task2-fire-perimeter-RUBINSTEIN.ipynb` `hwk4-task2-false-color-RUBINSTEIN.ipynb` visualizing the fire perimeter and burn scar, using true and false color imagery from the 2017 Thomas Fire. This exercise involves:
- Cleaning data
- Label-based selection
- Geospatial file creation
- `rioxarray` raster file manipulation 
- True color imagery plotting
- False color imagery plotting

![NASA Earth Observatory image by Joshua Stevens, using MODIS data](images/Satellite_image_of_Thomas_Fire.jpg)

## Repository Structure
```
eds220-hwk4
│   README.md
|   hwk4-task2-fire-perimeter-RUBINSTEIN.ipynb
│   hwk4-task2-false-color-RUBINSTEIN.ipynb
|   .gitignore
│
└───data
    │   thomasfire.geojson
```
## Data
Fire perimeter data was obtained from CalFire's Historical Fire Perimeters dataset. Landsat data was provided as a part of this exercise and accessed from UCSB Bren's Taylor server.

## References
