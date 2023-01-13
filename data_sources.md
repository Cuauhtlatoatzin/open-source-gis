# Data Sources

## Catalogs for look up specific data

* [United States Interagency Elevation Inventory](https://coast.noaa.gov/inventory/) &mdash; The U.S. Interagency Elevation Inventory is a comprehensive, nationwide listing of known high-accuracy topographic and bathymetric data for the United States and its territories.
* [USGS 3DEP Lidar Point Cloud Now Available as Amazon Public Dataset | U.S. Geological Survey](https://www.usgs.gov/news/technical-announcement/usgs-3dep-lidar-point-cloud-now-available-amazon-public-dataset)
* [Earthdata](https://earthdata.nasa.gov/) &mdash; NASA promotes the full and open sharing of all its data to research and applications communities, private industry, academia, and the general public. In order to meet the needs of these different communities, NASA’s Earth Observing System Data and Information System (EOSDIS) has provided various ways to discover, access, and use the data.
* [Earthdata Data Recipes](https://earthdata.nasa.gov/learn/data-recipes) &mdash; Data recipes are tutorials or step-by-step instructions that have been developed by the Earth Observing System Data and Information System (EOSDIS) Distributed Active Archive Centers (DAACs) staff or EOSDIS systems engineers to help users learn how to discover, access, subset, visualize and use our data, information, tools and services. These recipes cover many different data products across the Earth science disciplines and different processing languages/software.
* [TopoView](https://ngmdb.usgs.gov/topoview/) &mdash; TopoView highlights one of the USGS's most important and useful products, the topographic map. In 1879, the USGS began to map the Nation's topography. This mapping was done at different levels of detail, to support various land use and other purposes. As the years passed, the USGS produced new map versions of each area. TopoView shows the many and varied topographic maps of each of these areas through history. This can be particularly useful for historical purposes, such as finding the names of natural and cultural features that have changed over time.
* [The National Map (Basic)](https://viewer.nationalmap.gov/basic/)
* [The National Map (Advanced)](https://viewer.nationalmap.gov/advanced-viewer/)
* [Giovanni](https://giovanni.gsfc.nasa.gov/giovanni/) &mdash; The Bridge Between Data and Science.
* [ECS Data Access](https://www.ngdc.noaa.gov/mgg/ecs/cruises.html) &mdash; NCEI archives bathymetric, gravity, magnetic, seismic, and geologic sample data from the U.S. coastal waters to the deep ocean. Data collected as part of the U.S. ECS Project are in the public domain and made available as rapidly as possible.
* [USGS EROS Archive - Products Overview](https://www.usgs.gov/centers/eros/science/usgs-eros-archive-products-overview?qt-science_center_objects=0#qt-science_center_objects) &mdash; Explore the world’s largest civilian collection of images of the Earth’s surface. Find satellite images and data, aerial photography, elevation and land cover datasets, digitized maps, and our Image Gallery collections.
* [Coastal Elevation Models](https://www.ngdc.noaa.gov/mgg/coastal/coastal.html) &mdash; NCEI builds and distributes high-resolution, coastal digital elevation models (DEMs) that integrate ocean bathymetry and land topography supporting NOAA's mission to understand and predict changes in Earth's environment, and conserve and manage coastal and marine resources to meet our Nation's economic, social, and environmental needs.
* [Digital Elevation Data](http://viewfinderpanoramas.org/dem3.html) &mdash; Links to many different sources of DEMs from around the world.

## OpenStreetMap Data

* [OpenStreetMap Data Extracts](http://download.geofabrik.de/index.html)

## Natural Earth Map Data

* [Natural Earth Data](https://www.naturalearthdata.com/) &mdash; Natural Earth is a public domain map dataset available at 1:10m, 1:50m, and 1:110 million scales. Featuring tightly integrated vector and raster data, with Natural Earth you can make a variety of visually pleasing, well-crafted maps with cartography or GIS software.

## Paul Wessel's Data

* [GSHHG: A Global Self-consistent, Hierarchical, High-resolution Geography Database](https://www.soest.hawaii.edu/pwessel/gshhg/)
* [DCW-GMT: The Digital Chart of the World for GMT 6 or later](https://www.soest.hawaii.edu/pwessel/dcw/)
* [Global Seamount Database](https://www.soest.hawaii.edu/pwessel/smts/)

## Digital Elevation Maps

Typical data sources include the following scales (adapted from [Getting USGS Data](http://vterrain.org/Misc/usgs_data.html)).

| Arc             | Meters (approximate) | Used for                         |
| --------------- | -------------------- | -------------------------------- |
| 1 degree        | 110 kilometers       |                                  |
| 7.5 arc minutes | 14 kilometers        | Size of a traditional map "quad" |
| 30 arc seconds  | 1 kilometer          | Global elevation                 |
| 15 arc seconds  | 0.5 kilometer        |                                  |
| 3 arc seconds   | 90 meters            | World-wide SRTM                  |
| 1 arc second    | 30 meters            | DEM from topo, USA SRTM          |
| 1/3 arc second  | 10 meters            | DEM from topo                    |
| 1/9 arc second  | 3.4 meters           | Newer DEM from LIDAR             |

### Multiresolution

* [Ryan, W.B.F., S.M. Carbotte, J.O. Coplan, S. O'Hara, A. Melkonian, R. Arko, R.A. Weissel, V. Ferrini, A. Goodwillie, F. Nitsche, J. Bonczkowski, and R. Zemsky (2009), Global Multi-Resolution Topography synthesis, Geochem. Geophys. Geosyst., 10, Q03014, doi:10.1029/2008GC002332.](https://www.gmrt.org/about/index.php) &mdash; The Global Multi-Resolution Topography (GMRT) Synthesis is maintained as a multi-resolution gridded global Digital Elevation Model (DEM) that includes cleaned processed ship-based multibeam sonar data at their full spatial resolution (~100m in the deep sea).
* [GMRTMapTool](https://www.gmrt.org/GMRTMapTool/) &mdash; This lets you view the data.
* [GMRT Web Services](https://www.gmrt.org/services/index.php)

### 1/30 arc second (~1 meter)

* [1 meter Digital Elevation Models (DEMs) - USGS National Map 3DEP Downloadable Data Collection](https://catalog.data.gov/dataset/usgs-national-elevation-dataset-ned-1-meter-downloadable-data-collection-from-the-national-map-) &mdash; `This is a tiled collection of the 3D Elevation Program (3DEP) and is one meter resolution.`
  * This only had a subset of the US and Mexico, including Hawai'i.
  * Land only.
  * WMS Url: https://services.nationalmap.gov/arcgis/services/3DEPElevationIndex/MapServer/WMSServer?request=GetCapabilities&service=WMS

### 1/9 arc second (~3 meter)

* [1/9th Arc-second Digital Elevation Models (DEMs) - USGS National Map 3DEP Downloadable Data Collection](https://catalog.data.gov/dataset/national-elevation-dataset-ned-1-9-arc-second-downloadable-data-collection-national-geospatial) &mdash; `This is a tiled collection of the 3D Elevation Program (3DEP) and is 1/9 arc-second (approximately 3 m) resolution.`
  * `The seamless 1/9 arc-second DEM layer project-based coverage for portions of the conterminous United States, limited areas of Alaska, and Guam.`

### 1/3 arc second (~10 meter)

* [NHDPlus High Resolution](https://www.usgs.gov/core-science-systems/ngp/national-hydrography/nhdplus-high-resolution) &mdash; `The NHDPlus HR is a national, geospatial model of the flow of water across the landscape and through the stream network. The NHDPlus HR is built using the National Hydrography Dataset High Resolution data at 1:24,000 scale or better, the 1/3 arc-second (10 meter ground spacing) 3D Elevation Program data, and the nationally complete Watershed Boundary Dataset.`

### 1 arc second (~30 meter)

* [Shuttle Radar Topography Mission](https://www2.jpl.nasa.gov/srtm/)
  * [SRTM](https://wiki.openstreetmap.org/wiki/SRTM) &mdash; `The Shuttle Radar Topography Mission (SRTM) (Wikipedia article) is a NASA mission conducted in 2000 to obtain elevation data for most of the world. It is the current dataset of choice for digital elevation model (DEM) data since it has a fairly high resolution (1 arc-second, or around 25 meters), has near-global coverage (from 56°S to 60°N), and is in the public domain.`
  * [30-Meter SRTM Tile Downloader](https://dwtkns.com/srtm30m/) &mdash; This interface attempts to ease the pain of downloading 30-meter resolution elevation data from the Shuttle Radar Topography Mission.
  * Land only.
* [AW3D30](https://wiki.openstreetmap.org/wiki/AW3D30) &mdash; The ALOS Global Digital Surface Model "ALOS World 3D - 30m" (AW3D30) is the dataset with a horizontal resolution of approximately 30-meter mesh (1 arcsec), provided by Japan Aerospace Exploration Agency (JAXA) free of charge.
  * Land only.
* [ASTER Global Digital Elevation Map](https://asterweb.jpl.nasa.gov/gdem.asp) &mdash; Advanced Spaceborne Thermal Emission and Reflection Radiometer.
  * [NASA/METI/AIST/Japan Spacesystems, and U.S./Japan ASTER Science Team (2019). ASTER Global Digital Elevation Model V003 [Data set]. NASA EOSDIS Land Processes DAAC. Accessed 2019-10-22 from https://doi.org/10.5067/ASTER/ASTGTM.003](https://search.earthdata.nasa.gov/search/granules/collection-details?p=C1575726572-LPDAAC_ECS&q=GDEM&tl=1555913685!4!!)
  * Land only.

### 15 arc second (~500 meter)
* [SRTM15+V2.0](https://topex.ucsd.edu/WWW_html/srtm15_plus.html) &mdash; [FTP](ftp://topex.ucsd.edu/pub/srtm15_plus/) &mdash; [figshare](https://figshare.com/projects/SRTM15_V2_0/62045)
  * [Tozer, B. , D. T. Sandwell, W. H. F. Smith, C. Olson, J. R. Beale, and P. Wessel, Global bathymetry and topography at 15 arc seconds: SRTM15+, Accepted Earth and Space Science, August 3, 2019. DOI: 10.1029/2019EA000658](https://topex.ucsd.edu/sandwell/publications/180_Tozer_SRTM15+.pdf)
* [GEBCO 2019 Gridded Bathymetry Data](https://www.gebco.net/data_and_products/gridded_bathymetry_data/) &mdash; GEBCO’s gridded bathymetric data set, the GEBCO_2019 grid, is a global terrain model for ocean and land at 15 arc-second intervals.
  * [Blue Earth Bathymetry](http://www.shadedrelief.com/blue-earth/) &mdash; Generalized GEBCO Data for Seafloor Mapping.
* [SRTM15_PLUS](https://catalog.data.gov/dataset/srtm15-plus-data-fusion-of-shuttle-radar-topography-mission-srtm-land-topography-with-measured-) &mdash; To provide an improved mapping of the seafloor fabric globally, we have used available sounding data along with an improved global marine gravity model to develop at grid at 15 arcsecond resolution (~500 m). Land elevations are based on the best available data from SRTM, ASTER digital elevation models while the ice topography of Greenland and Antarctica is based on CryoSat-2 and IceSat. Ocean bathymetry is based on bathymetric predictions from the latest global gravity model from CryoSat-2 and Jason-1 along with 494 million carefully edited depth soundings at 15 arcsecond resolution. Bathymetry of the Arctic seafloor is based on the IBCAO grid with improved resolution in areas of multibeam coverage. We have used the bathymetry grid along with the improved gravity to construct a global map of abyssal hill amplitude and orientations and compare the orientations with predictions from seafloor age gradient analysis. Areas of disagreement reveal propagating rifts, microplates, and tectonic reorganizations. This SRTM15_PLUS provides the foundational bathymetry layer for Google Earth and is freely available at our ftp site (topex.ucsd.edu).

### 30 arc seconds (~1 km)

* [USGS EROS Archive - Digital Elevation - Global 30 Arc-Second Elevation (GTOPO30)](https://www.usgs.gov/centers/eros/science/usgs-eros-archive-digital-elevation-global-30-arc-second-elevation-gtopo30?qt-science_center_objects=0#qt-science_center_objects) &mdash; GTOPO30 is a global digital elevation model (DEM) with a horizontal grid spacing of 30 arc seconds (approximately 1 kilometer). GTOPO30 was derived from several raster and vector sources of topographic information.
* [GMTED2010](https://www.usgs.gov/land-resources/eros/coastal-changes-and-impacts/gmted2010?qt-science_support_page_related_con=0#qt-science_support_page_related_con) &mdash; The USGS and the National Geospatial-Intelligence Agency (NGA) have collaborated on the development of a notably enhanced global elevation model called the Global Multi-resolution Terrain Elevation Data (GMTED2010), which has replaced GTOPO30 as the elevation dataset of choice for global and continental scale applications.
* [USGS EROS Archive - Digital Elevation - Global Multi-resolution Terrain Elevation Data 2010 (GMTED2010)](https://www.usgs.gov/centers/eros/science/usgs-eros-archive-digital-elevation-global-multi-resolution-terrain-elevation?qt-science_center_objects=0#qt-science_center_objects) &mdash; The Global Multi-resolution Terrain Elevation Data 2010 (GMTED2010) provides a new level of detail in global topographic data. The GMTED2010 product suite contains seven new raster elevation products for each of the 30-, 15-, and 7.5-arc-second spatial resolutions and incorporates the current best available global elevation data.

## Geological Data

* [Global Geology Data Sets. United States Naval Academy.](https://www.usna.edu/Users/oceano/pguth/md_help/html/global_geology.htm)
* [Manaugh G, Twilley N (2013) What Did the Continents Look Like Millions of Years Ago? The Atlantic. September 23](https://www.theatlantic.com/technology/archive/2013/09/what-did-the-continents-look-like-millions-of-years-ago/279892/) &mdash; Article related to the maps below.
* [Blakey R (2016) Global Paleogeography and Tectonics in Deep Time Series. Deep Time Maps. Colorado Plateau Geosystems Inc.](http://deeptimemaps.com/global-paleogeography-and-tectonics-in-deep-time-series/) &mdash; [Details](http://deeptimemaps.com/global-series-details/) &mdash; The series is completely proprietary, but it is interesting to look at.
* [Macrostrat](https://macrostrat.org/)
* [OneGeology](http://portal.onegeology.org/OnegeologyGlobal/) &mdash; This is an interface and initiative to provide a global, distributed set of data sources for geoscience.
* [How to serve a OneGeology level 1 conformant Web Map Service (WMS) - Cookbook 1](http://www.onegeology.org/wmsCookbook/home.html)
* [GeoSciML](http://www.onegeology.org/technical_progress/geosciml.html)
* [Wright et al. (2013) Towards community-driven paleogeographic reconstructions: integrating open-access paleogeographic and paleobiology data with plate tectonics. Biogeosciences 10:1529-1541](https://www.biogeosciences.net/10/1529/2013/bg-10-1529-2013.pdf)
* [Müller, R. D., Cannon, J., Qin, X., Watson, R. J., Gurnis, M., Williams, S., et al. 2018. GPlates: Building a virtual Earth through deep time. Geochemistry, Geophysics, Geosystems, 19. doi:10.1029/2018GC007584.](https://agupubs.onlinelibrary.wiley.com/doi/full/10.1029/2018GC007584)
* [Müller RD et al. (2019) A Global Plate Model Including Lithospheric Deformation Along Major Rifts and Orogens Since the Triassic. Tectonics. 38(6): 184-1907.](https://doi.org/10.1029/2018TC005462)
* [Müller D, Seton M, Zahirovic S (2019) How Earth’s continents became twisted and contorted over millions of years. The Conversation. May 8.](https://theconversation.com/how-earths-continents-became-twisted-and-contorted-over-millions-of-years-116168)
* [EarthByte Staff (2019) GPlates 2.2 software and data sets. EarthByte. September 5.](https://www.earthbyte.org/gplates-2-2-software-and-data-sets/) &mdash; Data the work with GPlates software. Contains research paper references required for anything derrived from the data.
* [EarthByte Data Collections Direct Link](https://www.earthbyte.org/webdav/ftp/Data_Collections/) &mdash; Data the work with GPlates software. Contains research paper references required for anything derrived from the data.
* [The Human-Induced Earthquake Database (HiQuake)](http://inducedearthquakes.org/)
  * Foulger, G. R., Wilson, M., Gluyas, J., Julian, B. R., & Davies, R. (2017). Global review of human-induced earthquakes. Earth-Science Reviews.
  * Wilson, M. P., Foulger, G. R., Gluyas, J. G., Davies, R. J., & Julian, B. R. (2017). HiQuake: The human‐induced earthquake database. Seismological Research Letters, 88(6), 1560-1565.
* [Exploring Ocean Tectonics from Space](https://topex.ucsd.edu/grav_outreach/)
  * [Sandwell DT, Müller RD, Smith WHF, Garcia E, Francis E (2013) New global marine gravity model from CryoSat-2 and Jason-1 reveals buried tectonic structure, Science. 346(6205): 65-67. doi: 10.1126/science.1258213](http://dx.doi.org/10.1126/science.1258213)
* [GPlates -- Paleogeographic Modelling Tools](http://web.gps.caltech.edu/~gurnis/Old/GPlates/gplates.html)
* [GeoMapApp](http://www.geomapapp.org/index.htm)
  * Cite with `Figure made with GeoMapApp (www.geomapapp.org) / CC BY / CC BY (Ryan et al., 2009)`
* [Geoblock](https://geoblock.sourceforge.net/) &mdash; The Geoblock program is integrated software for 2D/3D modelling, computational geometry and visualization of spatial datasets. The program can be used in Earth sciences particularly in such fields as geology modelling and mining, ore reserve estimations and prediction of mineral liberation under grinding and mineral processing operations.

## Paleobiological Data

* [Paleobiology Database](https://paleobiodb.org)
* [Paleobiology Database: UW-Madison on Github](https://github.com/paleobiodb)
* [EarthLife Consortium](http://earthlifeconsortium.org/)
* [EarthLife Consortium on Github](https://github.com/EarthLifeConsortium)
* [Neotoma Paleoecology Database and Community](https://www.neotomadb.org/)
