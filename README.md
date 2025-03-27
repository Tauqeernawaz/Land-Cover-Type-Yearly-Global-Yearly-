# MODIS Land Cover Type Yearly Dataset (2001-2021)

This repository contains the **MODIS MCD12Q1 Version 6.1 Land Cover Type Yearly** dataset, accessed from **NASA's Land Processes Distributed Active Archive Center (LP DAAC)**. The dataset provides global land cover types for the years 2001 to 2021, derived from **MODIS Terra** and **Aqua** reflectance data, with yearly intervals. 

The **MCD12Q1 Version 6.1** data product is derived using supervised classifications from **MODIS** reflectance data and is based on multiple classification schemes, including:
- **International Geosphere-Biosphere Programme (IGBP)**
- **University of Maryland (UMD)**
- **Leaf Area Index (LAI)**
- **BIOME-Biogeochemical Cycles (BGC)**
- **Plant Functional Types (PFT)**

## Data Description:
The dataset provides **land cover types** derived from the above classification schemes, with **post-processing** that incorporates additional knowledge and ancillary information. The product includes additional land cover property assessment layers for land cover, land use, and surface hydrology, provided by the **Food and Agriculture Organization (FAO) Land Cover Classification System (LCCS)**.

The dataset contains the following layers:
- **Land Cover Type 1-5**
- **Land Cover Property 1-3**
- **Land Cover Property Assessment 1-3**
- **Land Cover Quality Control (QC)**
- **Land Water Mask**

## Land Cover Types:
The dataset classifies land cover into 10 categories:
1. **Evergreen Needleleaf Forest**
2. **Evergreen Broadleaf Forest**
3. **Deciduous Needleleaf Forest**
4. **Mixed Forest**
5. **Grassland**
6. **Shrubland**
7. **Cropland**
8. **Urban and Built-up Land**
9. **Barren Land**
10. **Water Bodies**

### Data Access:
- **Source**: [NASA LP DAAC - MCD12Q1 Version 6.1](https://lpdaac.usgs.gov/products/mcd12q1v061/)
- **Data Format**: Hierarchical Data Format 4 (HDF4)

### How to Use:
1. **Download the Data**: You can access the dataset from NASA LP DAAC.
2. **Extract and Process the Data**: The dataset is provided in **HDF4 format**, and you can use software like **GDAL** or **HDFView** to open and extract the data. You may also use tools like **QGIS** or **ArcGIS** to visualize the land cover types.
3. **Run the Code**: Use the provided Python or GIS scripts to further process the data (e.g., to compute land cover change or create land cover maps).

### License:
This repository is made available under the **CC BY 4.0** (Creative Commons Attribution 4.0 International License), allowing reuse with proper attribution.
