# Environmental data

NOAA data sources are compiled for easy comparison with dengue health data. These environmental data are from Iquitos, Peru and San Juan, Puerto Rico to correspond with the available dengue data. All data are provided in a csv format for easy access. All data are maintained and quality controlled by the programs that manage these data sources. Please be aware that data may still potentially contain quality issues and any user should inspect these data before use.

Environmental data provided for this study are from a variety of sources (ground observations, remote sensing, and reanalysis). Each source has different limitations and quality issues. Users of these data should be careful to utilize data that provide the most confidence for the actual representation of the surrounding conditions. Ground observations are generally an optimal representation of the actual local conditions. Remotely sensed observations are generally an excellent observation of precipitation and vegetation conditions for a location. Reanalysis data are a good representation of the conditions of a given area, especially when other data sources are not available.

Users should also be aware that these environmental data are at varying spatial scales. Station data are at a point-based estimate of the local climate conditions; whereas, the reanalysis and remotely sensed data are grid cells. For more information, please read the following descriptions to learn more about the differences.

Below is a description of the environmental data sources that are provided for analysis with dengue data. 

## Station data - Temperature and precipitation - NOAA's GHCN daily climate data 

The GHCN stations with daily temperature and precipitation data are available for both locations.

Additional data access and full description of data can be found here: [https://www.ncdc.noaa.gov/oa/climate/ghcn-daily/](https://www.ncdc.noaa.gov/oa/climate/ghcn-daily/)

Individual stations that are inside or near the city are listed here: San Juan, Puerto Rico: RQW00011641; Lat = 18.4325; Long = -66.0108; Elevation = 2.7; Start = 1956; End = 2015

Iquitos, Peru: PE000084377; Lat = -3.783; Long = -73.3; Elevation = 126; Start = 1973; End = 2015 

Temperature values are in Celsius; Precipitation values are in mm.

Values include Maximum Temperature, Minimum Temperature, Daily Average Temperature, Diurnal Temperature Range, and Daily Precipitation.

*Be aware that some stations may have missing days and/or missing values. Missing values are identified as -9999. Missing days are not identified in the record.*

*Station observations for San Juan are complete and have few missing values. However, there are multiple missing station observations for Iquitos and users should refer to other data sources provided.*

**Data (naming convention = CityNameIDENTIFICATION_NUMBER.csv):**

[Iquitos](IquitosPE000084377.csv)

[San Juan](SanJuanRQW00011641.csv) 

## Satellite precipitation - Precipitation - NOAA's CDR PERSIANN Precipitation Product 

PERSIANN is a global climatological data record of precipitation from remote sensing information using an artificial neural network. These data are available for each city on a daily basis from 1983-present.

The resolution of this data product is 0.25x0.25 degree.

Additional data access and full description of data can be found here: [http://www.ncdc.noaa.gov/cdr/operationalcdrs.html](http://www.ncdc.noaa.gov/cdr/operationalcdrs.html)

Precipitation data are from the grid surrounding the station located in the city.

Precipitation values are reported as daily sums in mm.

*Missing values are listed as -9999.*

**Data (naming convention = LOCATION_Precip.xlsx):**

[Iquitos](Iquitos_Precip.xlsx)

[San Juan](SanJuan_Precip.xlsx)

## Reanalysis - Temperature and precipitation - NOAA's NCEP Climate Forecast System Reanalysis 

Climate Forecast System Reanalysis is global, high-resolution, coupled atmosphere-ocean-land surface-sea ice system to provide the best estimate of the state of these coupled domains over the period of record.

Data are available from 1979-present.

Additional data access and full description of data can be found here: [http://rda.ucar.edu/datasets/ds093.0/#metadata/detailed.html?_do=y](http://rda.ucar.edu/datasets/ds093.0/#metadata/detailed.html?_do=y)

CFSR provides a variety of data that are not easily accessible from other data sources. This includes relative humidity, specific humidity and dew point.

*Temperature data values are available in Kelvin.*

*Resolution of the grid is 0.5 degree.*

**Data (naming convention = LOCATION.xlsx):**

[Iquitos](Iquitos.xlsx)

[San Juan](SanJuan.xlsx) 

## Satellite vegetation - Normalized difference vegetation index (NDVI) - NOAA's CDR Normalized Difference Vegetation Index 

NDVI CDR is a global climatological data record of vegetation. These data are available for each city on a weekly basis from 1981-present.

The resolution of the product is at 0.05x0.05 degree.

Additional data access and full description of data can be found here: [http://www.ncdc.noaa.gov/cdr/operationalcdrs.html](http://www.ncdc.noaa.gov/cdr/operationalcdrs.html)

Four pixels closest to the city centroid are provided for evaluation of vegetation change.

30-year climatologies were also provided for these sites.

*NDVI data are provided without quality flagged data removed. Quality flagged data are provided at the CDR webpage.* 

**Raw data (naming convention = LOCATION\_noqc.csv):**

[Iquitos](iquitos_noqc.csv)

[San Juan](sanJuan_noqc.csv) 

**Raw climatologies (naming convention = LOCATION\_clim\_noqc.csv):**

[Iquitos](iquitos_clim_noqc.csv)

[San Juan](sanJuan_clim_noqc.csv)
