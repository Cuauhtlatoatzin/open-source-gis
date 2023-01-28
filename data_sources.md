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

## Ecoregions/Bioregions/Biomes

See definitions at [Ecoregion](https://en.wikipedia.org/wiki/Ecoregion), [Bioregion](https://en.wikipedia.org/wiki/Bioregion), [Biome](https://en.wikipedia.org/wiki/Biome).

* [Bailey, R. G. 1983. Delineation of ecosystem regions. Environmental Management 7: 365-373.](https://www.researchgate.net/publication/227182025_Delineation_of_Ecosystem_Regions)
  * [Bailey's ecoregions and subregions of the United States, Puerto Rico, and the U.S. Virgin Islands](https://www.fs.usda.gov/rds/archive/products/RDS-2016-0003/_metadata_RDS-2016-0003.html)
* [Brown, D.E., Reichenbacher, F. and Franson, S.E. (1998). A Classification of North American Biotic Communities. University of Utah Press, Salt Lake City, Utah. 141p.](https://www.google.com/books/edition/A_Classification_of_North_American_Bioti/UjYUAQAAIAAJ?hl=en)
* [Olson, D. M., Dinerstein, E., Wikramanayake, E. D., Burgess, N. D., Powell, G. V. N., Underwood, E. C., D'Amico, J. A., Itoua, I., Strand, H. E., Morrison, J. C., Loucks, C. J., Allnutt, T. F., Ricketts, T. H., Kura, Y., Lamoreux, J. F., Wettengel, W. W., Hedao, P., Kassem, K. R. 2001. Terrestrial ecoregions of the world: a new map of life on Earth. Bioscience 51(11):933-938.](https://doi.org/10.1641/0006-3568(2001)051[0933:TEOTWA]2.0.CO;2)
* [Assessment Millenium Ecosystem. (2005). Current state and trends. Washington, DC.](https://www.millenniumassessment.org/en/Condition.html)
  * > Throughout this chapter, and elsewhere in the MA, the 14 biomes of the WWF terrestrial biome classification are used, based on WWF terrestrial ecoregions (Olson et al. 2001).
* [Rutherford, M. C., Mucina, L., & Powrie, L. W. (2006). Biomes and bioregions of southern Africa. The vegetation of South Africa, Lesotho and Swaziland, 19, 30-51.](https://www.researchgate.net/publication/236982065_Biomes_and_bioregions_of_Southern_Africa)
* [USGS. Global Ecosystems](https://www.usgs.gov/centers/geosciences-and-environmental-change-science-center/science/global-ecosystems?qt-science_center_objects=0#publications)
* [WWF. (2012) Terrestrial Ecoregions of the World](https://www.worldwildlife.org/publications/terrestrial-ecoregions-of-the-world)
  * This is based on Olson et al. 2001.
  * > There are 867 terrestrial ecoregions, classified into 14 different biomes such as forests, grasslands, or deserts. Ecoregions represent the original distribution of distinct assemblages of species and communities.
* [Rehfeldt, G.E., N.L. Crookston, C. Sáenz-Romero and E.M. Campbell (2012) North American vegetation model for land-use planning in a changing climate: a solution to large classification problems. Ecological Applications, 22(1):119-141](https://www.jstor.org/stable/41416748)
* [Stein, H., Griebler, C., Berkhoff, S., Matzke, D., Fuchs, A., & Hahn, H. J. (2012). Stygoregions–a promising approach to a bioregional classification of groundwater systems. Scientific reports, 2(1), 1-9.](https://doi.org/10.1038/srep00673)
* [Sayre, R., Dangermond, J., Frye, C., Vaughan, R., Aniello, P., Breyer, S., ... & Comer, P. (2014). A new map of global ecological land units—an ecophysiographic stratification approach. Washington, DC: Association of American Geographers, 46.](https://pubs.er.usgs.gov/publication/70187380)
* [Dinerstein, E., Olson, D., Joshi, A., Vynne, C., Burgess, N. D., Wikramanayake, E., ... & Saleem, M. (2017). An ecoregion-based approach to protecting half the terrestrial realm. BioScience, 67(6), 534-545.](https://doi.org/10.1093/biosci/bix014)
  * > More recently, the scientific basis for protecting half the terrestrial realm was strengthened by Wilson's (2016) analysis of extinction in relation to area of natural habitat loss, of greatest concern in habitats rich in endemic species. Even before these biodiversity-based analyses of the land area required for conservation, Odum and Odum (1972) pointed to the need to conserve half of the land to maintain ecosystem function for the benefit of humans. On the question of how much to conserve, a species-conservation approach derived the same answer as an ecosystem-services paradigm—a striking example of convergence. Therefore, the aspirational goal of 50% protected has emerged and the science codified in several advocacy and policy papers under the name **Nature Needs Half (NNH; e.g., Locke 2013)**.
  * > We conducted this analysis across all **846 terrestrial ecoregions** distributed among the Earth's 14 terrestrial biomes (supplemental appendix S1). We then sorted ecoregions into four categories defined by the extent of both remaining natural habitat and protected land:<br/><br/>(1) Half Protected: More than 50% of the total ecoregion area is protected. (2) Nature Could Reach Half: Less than 50% of the total ecoregion area is protected but the sum of total ecoregion protected and unprotected natural habitat remaining is more than 50%. Ecoregions in this category have enough remaining natural habitat to reach Half Protected if additional protected areas or other types of conservation areas are added to the system. (3) Nature Could Recover: The sum of the amount of natural habitat remaining and the amount of the total ecoregion that is protected is less than 50% but more than 20%. Ecoregions in this category would require restoration to reach Half Protected because the amount of available habitat outside protected areas plus the existing protected areas is below 50%. (4) Nature Imperiled: The sum of the amount of natural habitat remaining and the amount of the total ecoregion that is protected is less than or equal to 20%.
  * From the supplemental material SM1:
    * > For this paper, a global review of units and boundaries was undertaken to incorporate advances in biogeographic scholarship since publication of the 2001 map. We recommend that this new version &mdash;Ecoregions2017<sup>©RESOLVE</sup>&mdash; be substituted for the map published in Olson et al. (2001).
    * For more see the supplementary material.
  * [Ecoregions](https://ecoregions.appspot.com/)
  * [Terrestrial Ecoregions GIS Data](https://www.gislounge.com/terrestrial-ecoregions-gis-data/)
* [Mucina, L. (2019). Biome: evolution of a crucial ecological and biogeographical concept. New Phytologist, 222(1), 97-114.](https://doi.org/10.1111/nph.15609)
* [Freitas, C. G., Bacon, C. D., Souza-Neto, A. C., & Collevatti, R. G. (2019). Adjacency and area explain species bioregional shifts in neotropical palms. Frontiers in plant science, 10, 55.](https://doi.org/10.3389/fpls.2019.00055)
* [Dinerstein, E., Joshi, A. R., Vynne, C., Lee, A. T. L., Pharand-Deschênes, F., França, M., ... & Olson, D. (2020). A “Global Safety Net” to reverse biodiversity loss and stabilize Earth’s climate. Science advances, 6(36), eabb2824.](https://doi.org/10.1126/sciadv.abb2824)
* [Bioregions 2020](https://www.oneearth.org/bioregions-2020/)
  * This model divides the Dinerstein et al. 2017 SM1 figure S1 model's 8 realms into [14 biogeographical realms](https://images.takeshape.io/86ce9525-f5f2-4e97-81ba-54e8ce933da7/dev/2a516318-4eb3-4f07-be09-bf0bcb02e99f/OneEarthMasterMapsCS5-bioreg-v5.5-REALMS-web.webp). These are further divided into [52 subrealms](https://images.takeshape.io/86ce9525-f5f2-4e97-81ba-54e8ce933da7/dev/c93705b0-7868-4e96-86c4-19a7be4c4a86/OneEarthMasterMapsCS5-bioreg%20v5.5-SUBREALM%20med.jpg). These are further divided into [185 bioregions](https://images.takeshape.io/86ce9525-f5f2-4e97-81ba-54e8ce933da7/dev/09f34b5d-27cd-4fb8-90e8-94a2be2bc14f/OneEarthMasterMapsCS5-bioreg%20v5.5-BIOREGION%20med.jpg). Then these can be even further divided into the [846 terrestial bioregions](https://images.takeshape.io/86ce9525-f5f2-4e97-81ba-54e8ce933da7/dev/be968ab3-e4c1-4641-9ec3-a3c691a247c2/OneEarthMasterMapsCS5-bioreg%20v5.5-ECOREG%20med.jpg) from Dinerstein et al. 2017.
  * > One Earth presents a novel biogeographical framework called Bioregions 2020, which builds upon 844 terrestrial ecoregion divisions (Dinerstein et al. 2017) to delineate 185 discrete bioregions organized within the world's major biogeographical realms. [Dinerstein et al. says 846]
  * > “Marine Ecoregions of the World” (Spalding et al. 2007) is referenced in Bioregions 2020, and in some cases informs the clustering of terrestrial ecoregions.
  * > There are 14 widely held biome types, [mapped below with an overlay of the 185 bioregions](https://images.takeshape.io/86ce9525-f5f2-4e97-81ba-54e8ce933da7/dev/8231bd6d-0fb1-4fd1-9a1d-3d51ef8b7b6e/OneEarthMasterMapsCS5-bioreg%20v5.5-BIOME%20med.jpg) [matches up with WWF biome types]
  * https://www.oneearth.org/api/realms.json
  * https://www.oneearth.org/api/bioregions.json
* [Kauffman, M. J., Cagnacci, F., Chamaillé-Jammes, S., Hebblewhite, M., Hopcraft, J. G. C., Merkle, J. A., ... & Zuther, S. (2021). Mapping out a future for ungulate migrations. Science, 372(6542), 566-569.](https://doi.org/10.1126/science.abf0998)
* [Vynne, C., Gosling, J., Maney, C., Dinerstein, E., Lee, A. T., Burgess, N. D., ... & Svenning, J. C. (2022). An ecoregion‐based approach to restoring the world's intact large mammal assemblages. Ecography, 2022(4).](https://doi.org/10.1111/ecog.06098)

**Often times, various countries will have their own classification of the regions.**

* [Ecoregions of North America](https://www.epa.gov/eco-research/ecoregions-north-america)
* [Australia's ecoregions](https://www.dcceew.gov.au/environment/land/nrs/science/ibra/australias-ecoregions)