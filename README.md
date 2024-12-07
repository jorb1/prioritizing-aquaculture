# Prioritizing Potential Aquaculture Zones on the West Coast of the United States:
## An Exercise in R Analysis
## Author: Bailey Jørgensen
** https://github.com/jorb1

For this analysis, I will determine which Exclusive Economic Zones (EEZ) on the West Coast of the United States are best suited to developing marine aquaculture for several species of Oysters and White Shrimp. Suitable locations will be determined based on a range of suitable sea surface temperatures (SST) and depth values for the species. 

![aquaculture image](https://cdn-amiji.nitrocdn.com/IEZIUgrNRbYQggDlmHBLkLYuABZyJyOL/assets/images/optimized/rev-9ab0d0b/commodity.com/wp-content/uploads/2021/12/00_Sea_fish_farm.jpg)

## Data

All data for this analysis was accessed on 11/20/2024. Direct links to data sites are provided in the citations.

- Data on species depth and temperature requirements came from SeaLifeBase.

- Data on sea surface temperatures came from NOAA's 5km Daily Global Satellite Sea Surface Temperature Anomaly v3.1. 

- Bathymetry data came from the General Bathymetric Chart of the Oceans (GEBCO). 

- Data on Exclusive Economic Zones came from Marineregions.org.

## Repository Structure

```bash
├── prioritizing-aquaculture
│   ├── prioritizing-aquaculture.Rproj
│   ├── aquaculture.html
│   ├── aquaculture.qmd
│   ├── README.md
│   └── .gitignore
├── data
│   ├── average_annual_sst_2008.tif
│   ├── average_annual_sst_2009.tif
│   ├── average_annual_sst_2010.tif
│   ├── average_annual_sst_2011.tif
│   ├── average_annual_sst_2012.tif
│   ├── depth.tif
│   ├── IMG_20241203_193746.jpg
│   ├── wc_regions_clean.dbf
│   ├── wc_regions_clean.prj
│   ├── wc_regions_clean.shp
│   └── wc_regions_clean.shx
```

## Citations: 

Boyd, Claude E., and Jason W. Clay. “Shrimp Aquaculture and the Environment.” Scientific American 278, no. 6 (1998): 58–65. http://www.jstor.org/stable/26057855.

Hall, S. J., Delaporte, A., Phillips, M. J., Beveridge, M. & O’Keefe, M. Blue Frontiers: Managing the Environmental Costs of Aquaculture (The WorldFish Center, Penang, Malaysia, 2011).

Gentry, R. R., Froehlich, H. E., Grimm, D., Kareiva, P., Parke, M., Rust, M., Gaines, S. D., & Halpern, B. S. Mapping the global potential for marine aquaculture. Nature Ecology & Evolution, 1, 1317-1324 (2017).

GEBCO Compilation Group (2022) GEBCO_2022 Grid (doi:10.5285/e0f0bb80-ab44-2739-e053-6c86abc0289c).

NOAA Coral Reef Watch. "Daily Global 5km Satellite Sea Surface Temperature Anomaly (Version 3.1, Released August 1, 2018)." Accessed December 3, 2024. https://coralreefwatch.noaa.gov/product/5km/index_5km_ssta.php.

R. Oliver, EDS 223 - Geospatial Analysis and Remote Sensing, Course Notes. 2024. [Online]. Available: https://eds-223-geospatial.github.io/

SeaLifeBase. "Penaeus setiferus (Linnaeus, 1767) - Northern White Shrimp." Accessed December 3, 2024. https://sealifebase.org.

SeaLifeBase. "Ostrea edulis (Linnaeus, 1758) - Edible Oyster." Accessed December 3, 2024. https://sealifebase.org.
