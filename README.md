# Blue Carbon Tidal Restrictions Dataset

This repository contains data on tidal restrictions identified along the Victorian coastline, Australia, as part of a study on blue carbon restoration potential.

## Abstract

Blue carbon ecosystems (BCEs), encompassing mangroves, saltmarshes, and seagrasses, are vital ecosystems that deliver valuable services such as carbon sequestration, biodiversity support, and coastal protection. However, these ecosystems are threatened by various anthropogenic factors, including tidal restrictions like levees, barriers, and embankments. These structures alter the natural seawater flow, often converting coastal ecosystems into freshwater environments. Identifying tidal restrictions and assessing their suitability for tidal restoration in areas amenable for coastal management is a crucial first step to successfully restore BCEs and the associated ecosystem services they provide, i.e., managed realignment. This study presents a novel approach for detecting tidal restrictions in the state of Victoria, Australia, using high-resolution LiDAR data, geospatial analysis techniques, and a multi-criteria scoring system. Our model successfully identified 90% of known tidal restrictions from an existing dataset, while also detecting an additional 118 potential tidal restrictions, representing a 35% increase. The model performance analysis revealed trade-offs between precision, recall, and noise ratio when using different noise reduction thresholds, highlighting the importance of selecting an appropriate threshold based on project objectives. The multi-criteria scoring system, which considered factors such as proximity to BCEs and current land use, enabled the selection of tidal restrictions based on their hydrological suitability for restoration. The results of this study have significant implications for BCE restoration efforts not only in Victoria, but more broadly across Australia and globally, providing a systematic approach to identifying and targeting areas with the greatest potential for successful restoration projects.

## Dataset Description

The dataset includes both known and newly detected tidal restrictions along the Victorian coastline, along with their assessed suitability for restoration. It provides a comprehensive mapping of potential sites for blue carbon ecosystem restoration through tidal reconnection.

## File Format

The data is provided in ESRI Shapefile format, including the following files:
- BlueCarbon_TidalRestrictions.shp
- BlueCarbon_TidalRestrictions.shx
- BlueCarbon_TidalRestrictions.dbf
- BlueCarbon_TidalRestrictions.prj

## Attributes

The shapefile includes the following attributes:

1. ID: Unique identifier for each tidal restriction
2. Type: Classification as 'Known' or 'Newly Detected'
3. Length_m: Length of the tidal restriction in meters
4. Score: Hydrological suitability score (0-5) based on multi-criteria assessment
5. Prox_BCE: Proximity to existing blue carbon ecosystems (1 if within 250m, 0 if not)
6. Prox_Urban: Proximity to urban developments (1 if further than 250m, 0 if not)
7. Elev_Prof: Presence of typical elevation profile (1 if present, 0 if not)
8. Prox_Hydro: Proximity to hydrological features (1 if within 250m, 0 if not)
9. Current_Use: Current functional purpose of the restriction (e.g., 'None', 'Salt Pond', 'Sewage Treatment')
10. Region: Coastal region (e.g., 'Port Phillip', 'Western Port', 'Corner Inlet', 'Gippsland Lakes')

## Usage

This dataset can be used to identify potential sites for blue carbon restoration through tidal reconnection. The suitability scores can help prioritize sites for further investigation and potential restoration projects.

## Citation

If you use this dataset, please cite:
Nuyts, S., Wartman, M., Macreadie, P.I., Costa, M.D.P. (2024). Mapping tidal restrictions to support blue carbon restoration. Science of The Total Environment

## License

This dataset is licensed under a Creative Commons Attribution 4.0 International License (CC-BY 4.0). You are free to share and adapt the material for any purpose, even commercially, as long as you give appropriate credit, provide a link to the license, and indicate if changes were made.

