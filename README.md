# Prioritizing Potential Aquaculture in West Coast EEZs
## Author: Emma Bea Mitchell

### Purpose of the repository:
The main purpose of the repository is to create a function that can use depth and sea surface temperature data to find suitable locations in EEZs for marine aquaculture. To do this we:

- Reclassify depth and sea surface temperature data into suitable and unsuitable locations
- Find suitable locations based on EEZs
- Map EEZs by amount of suitable locations

Function arguments:
- minimum and maximum sea surface temperature
- minimum and maximum depth
- species name

Function outputs:
- map of EEZ regions colored by amount of suitable area

### Skills utilized in this project:

- map algebra
- function creation
- changing raster extent, resolution, and crs
- map creation using tmap

### Repository Organization
```
Prioritizing_Potential_Aquaculture
│   README.md
│   prioritizing_potential_aquaculture.qmd
|   .gitignore
│
└───data
    │   wc_regions_clean.shp
    │   depth.tif
    │   average_annual_sst_2008.tif
    │   average_annual_sst_2009.tif
    │   average_annual_sst_2010.tif
    │   average_annual_sst_2011.tif
    │   average_annual_sst_2012.tif
```

### Data Access

| Data                 | Source                                                    | Link                                                                  |
|----------------------|-----------------------------------------------------------|-----------------------------------------------------------------------|
| Depth                | GEBCO Gridded Bathymetry Data                             | https://www.gebco.net/data_and_products/gridded_bathymetry_data/#area |
| SST                  | NOAA Global 5km Satellite Sea Surface Temperature Anomaly | https://coralreefwatch.noaa.gov/product/5km/index_5km_ssta.php        |
| West Coast EEZs      | Marine Regions EEZ Boundaries                             | https://www.marineregions.org/eez.php                                 |
| Species Requirements | SeaLifeBase                                               | https://www.sealifebase.ca/search.php                                 |


### Acknowledgements:

Assignment and instructions provided by Ruth Oliver for the EDS 223 Geospatial and Remote Sensing graduate course at UCSB

Public data provided by the GEBCO, NOAA, Marine Regions, and SeaLifeBase were integral in the completion of this project

All data downloaded from [google drive](https://drive.google.com/file/d/1u-iwnPDbe6ZK7wSFVMI-PpCKaRQ3RVmg/view)

Shoutout to my friends and rubber ducks for successfully helping me through this project :)

