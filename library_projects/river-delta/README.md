# Project Data Overview

In the `csv` folder, you will find crop data for the region of interest, including crop type and area (`crop_data.csv`). You will also find the area calculations for each wetland from the 1911 polygon layer (`wetland_area.csv`).

## Data Sources

### i15 2017 Crop Mapping Data
The crop data was downloaded from the California State ArcGIS Online page. 

> “This dataset presents the spatial extent of all agricultural, semi-agricultural, native, and urban lands within the legal Delta Boundary. Delineated from RapidEye Imagery from the year 2017. The dataset is a comprehensive land use for 2017 and also contains information on agricultural classes for spring 2017. Major assumption of this dataset is that the native vegetation is grouped into 5 level 2 categories and are grouped into 3 DWR native categories.”

### 1911 Map
This "Topographic map of the Sacramento Valley, California" was created by the U.S. Geological Survey in 1911. It displays environmental features of particular importance to this project, such as marshes and tidal areas. I cropped the original map to the region of interest to improve georeferencing accuracy.