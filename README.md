# open-source-gis

Information on open source GIS and data set sources

## Maps

* [Maps Are Territories: Science is an Atlas](http://territories.indigenousknowledge.org/home/contents.html)

## Map Projections

* [Investigating Map Projections](https://www.nationalgeographic.org/activity/investigating-map-projections/)
* [What are Map Projections? (And Why They Are Deceiving To Us)](https://gisgeography.com/map-projections/)
* [Map projection on Wikipedia](https://en.wikipedia.org/wiki/Map_projection)
* [List of map projections](https://en.wikipedia.org/wiki/List_of_map_projections)
* [Jenny, Bernhard, Tom Patterson, and Lorenz Hurni. "Flex Projector–interactive software for designing world map projections." Cartographic Perspectives 59 (2008): 12-27.](https://www.researchgate.net/publication/266016878_Flex_Projector-Interactive_Software_for_Designing_World_Map_Projections)
* [Equal Earth projection](http://equal-earth.com/equal-earth-projection.html) &mdash; The Equal Earth map projection is a new equal-area pseudocylindrical projection for world maps jointly developed by Bojan Šavrič (Esri), Tom Patterson (US National Park Service), and Bernhard Jenny (Monash University). It was created to provide a visually pleasing alternative to the Gall-Peters projection, which some schools and socially concerned groups have adopted out of concern for fairness. Their priority is to show developing countries in the tropics and developed countries in the north with correctly proportioned sizes.
  * [Introducing the Equal Earth Projection (Video)](https://www.youtube.com/watch?v=m5Te3JZfPDM)

## Learning GIS

* [NCSU GIS/MEA582: Geospatial Modeling and Analysis](http://ncsu-geoforall-lab.github.io/geospatial-modeling-course/)
* [GIS Practicum](https://www.baruch.cuny.edu/confluence/display/geoportal/GIS+Practicum)
* [GEOG 585: Open Web Mapping](https://www.e-education.psu.edu/geog585/)

## Data Sources

### Data formats

There are a few different formats in which data is stored and shared. Knowing about these is important for building geospatial applications. Each format has a specific purpose. Some formats are specifically for storing vector shapes, some encode the surface of Earth in a grid of pixels, some encode 3D point clouds, and yet others are intended for sharing data on the semantic web.

This only lists the file formats I've recently come across. This is not a comprehensive list. For more exhaustive lists see GDAL's [Raster driver](https://gdal.org/drivers/raster/index.html) and [Vector driver](https://gdal.org/drivers/vector/index.html) pages.

* [Coverage data](https://en.wikipedia.org/wiki/Coverage_data)

#### 2d Vector

* [GeoParquet](https://geoparquet.org/)
  * [Introducing the Geoparquet data format](https://getindata.com/blog/introducing-geoparquet-data-format/)
* [GeoPackage](https://en.wikipedia.org/wiki/GeoPackage) &mdash; both GeoPackage and SpatiaLite (newer versions are a reference implementation of GeoPackage) allow creating a single indexed database file for sharing vector databases in a SQLite DB format.
  * [SpatiaLite](https://en.wikipedia.org/wiki/SpatiaLite)
* [GeoJSON](https://en.wikipedia.org/wiki/GeoJSON)
* [Geography Markup Language (GML)](https://en.wikipedia.org/wiki/Geography_Markup_Language)
  * [GML Spec](https://www.ogc.org/standards/gml)
* [Keyhole Markup Language (KML)](https://en.wikipedia.org/wiki/Keyhole_Markup_Language) &mdash; Allows placing COLLADA 3d models on a map.
* [Geographic Data Files (GDF)](https://en.wikipedia.org/wiki/Geographic_Data_Files)
* [Shapefile](https://en.wikipedia.org/wiki/Shapefile)
* [MapInfo TAB format](https://en.wikipedia.org/wiki/MapInfo_TAB_format) &mdash; [MapInfo Interchange Format](https://en.wikipedia.org/wiki/MapInfo_Interchange_Format)
* [Well-known text representation of geometry](https://en.wikipedia.org/wiki/Well-known_text_representation_of_geometry)
* [Well-known text representation of coordinate reference systems](https://en.wikipedia.org/wiki/Well-known_text_representation_of_coordinate_reference_systems) &mdash; simple file format for defining the coordinate reference system
* [World file](https://en.wikipedia.org/wiki/World_file) &mdash; raster image sidecar file which defines the 6 matrix elements used for affine transformations of a raster image

#### 3d Vector

* [3D Tiles Format Specification](https://github.com/CesiumGS/3d-tiles/tree/main/specification) &mdash; if you see a `b3dm` or `i3dm` extension, that's this format. Built on glTF.
  * [3d tiles samples](https://github.com/CesiumGS/3d-tiles-samples)
* [glTF](https://en.wikipedia.org/wiki/GlTF) &mdash; built on COLLADA.
* [COLLADA](https://en.wikipedia.org/wiki/COLLADA) &mdash; a widely supported 3d vector model format

#### Multiple format

* [CityGML](https://en.wikipedia.org/wiki/CityGML)
* [OGC Moving Features](https://www.ogc.org/standards/movingfeatures)
* [OGC API - Tiles - Part 1: Core](https://docs.ogc.org/is/20-057/20-057.html)
  * [OGC Two Dimensional Tile Matrix Set and Tile Set Metadata](https://docs.opengeospatial.org/is/17-083r4/17-083r4.html)
* [Network Common Data Form (NetCDF)](https://en.wikipedia.org/wiki/NetCDF)

#### Lidar

* [ASPRS LAS](https://en.wikipedia.org/wiki/LAS_file_format)
  * [ASPRS LAS Specification](https://github.com/ASPRSorg/LAS)

#### 2d Raster

* [Digital Terrain Elevation Data (DTED)](https://en.wikipedia.org/wiki/DTED)
* [USGS DEM](https://en.wikipedia.org/wiki/USGS_DEM) &mdash; used for elevation models such as [GTOPO30](https://en.wikipedia.org/wiki/GTOPO30)
* [National Imagery Transmission Format Standard (NITFS)](https://en.wikipedia.org/wiki/National_Imagery_Transmission_Format)
* [GML in JPEG 2000 (GMLJP2)](https://www.ogc.org/standards/gmljp2) &mdash; used to endow jpeg's with GML metadata
* [JPEG 2000](https://en.wikipedia.org/wiki/JPEG_2000) &mdash; standard for various kinds of imagery data that may map to geo coordinates, such as weather sattelite imagery, IR sattelite imagery, 
* [GeoTIFF](https://www.ogc.org/standards/geotiff)
* [TIFF](https://en.wikipedia.org/wiki/TIFF) &mdash; base format for GeoTIFF
* [Exif](https://en.wikipedia.org/wiki/Exif) &mdash; allows encoding an image location
* [MrSID](https://en.wikipedia.org/wiki/MrSID)
* [Enhanced Compression Wavelet(ECW)](https://en.wikipedia.org/wiki/ECW_(file_format))
* [Band Interleaved by Line (BIL) Image Encoding](https://www.loc.gov/preservation/digital/formats/fdd/fdd000304.shtml)
* [Digital Raster Graphic (DRG)](https://en.wikipedia.org/wiki/Digital_raster_graphic) &mdash; archaic

#### 2d Binary

* [GRIB](https://en.wikipedia.org/wiki/GRIB)
* [Esri ARC/INFO grid](https://en.wikipedia.org/wiki/Esri_grid) &mdash; also has an ASCII version
* [SEG-Y](https://en.wikipedia.org/wiki/SEG-Y)

#### Schemas

Also see [Spatial Data on the Web Best Practices](https://www.w3.org/TR/sdw-bp/).

* [OGC GeoSPARQL](https://en.wikipedia.org/wiki/OGC_GeoSPARQL) &mdash; A simple ontology for geo Features allowing geometry to be specified in GML or WKT along with predicates in [region cennection calculus](https://en.wikipedia.org/wiki/Region_connection_calculus) and [DE-9IM](https://en.wikipedia.org/wiki/DE-9IM).
* [W3C Geospatial Vocabulary](https://www.w3.org/2005/Incubator/geo/XGR-geo/)
* [GeoVocab.org](http://geovocab.org/)
* [GeoRDF](https://web.archive.org/web/20140123034509/http://www.w3.org/wiki/GeoRDF)
* [GeoRSS](https://web.archive.org/web/20220630194242/https://georss.org/)
* [GeoNames Ontology](http://www.geonames.org/ontology/documentation.html)
* [Basic Geo (WGS84 lat/long) Vocabulary](https://www.w3.org/2003/01/geo/)
* [xAL:AddressDetails](https://www.web3d.org/specifications/kml2.2/documentation/xAL_AddressDetails1.html) &mdash; has `AddressLatitude` and `AddressLongitude`, but no altitude or other geo data.
* Schema.org &mdash; this is definitely more oriented towards search results and not serious Geospatial applications.
  * [Schema.org GeospatialGeometry](https://schema.org/GeospatialGeometry) &mdash; Base class of all things geo in Schema.org. Note: `(Eventually to be defined as) a supertype of GeoShape designed to accommodate definitions from Geo-Spatial best practices.`
  * [Schema.org GeoShape](https://schema.org/GeoShape)
  * [Schema.org GeoCoordinates](https://schema.org/GeoCoordinates)
  * [Schema.org Place](https://schema.org/Place)
  * [Schema.org PostalAddress](https://schema.org/PostalAddress)
* [DublinCore Coverage](https://www.dublincore.org/specifications/dublin-core/dcmi-terms/terms/coverage/) &mdash; this is not at all for geo data.
  * > Spatial topic and spatial applicability may be a named place or a location specified by its geographic coordinates. Temporal topic may be a named period, date, or date range. A jurisdiction may be a named administrative entity or a geographic place to which the resource applies. Recommended practice is to use a controlled vocabulary such as the Getty Thesaurus of Geographic Names [TGN]. Where appropriate, named places or time periods may be used in preference to numeric identifiers such as sets of coordinates or date ranges. Because coverage is so broadly defined, it is preferable to use the more specific subproperties Temporal Coverage and Spatial Coverage.

#### Sensor Schemas

* [OM2](https://github.com/HajoRijgersberg/OM)
* [QUDT](https://qudt.org/)
* [ODM2](https://github.com/ODM2/ODM2)
* [Observations and Measurements (O&M)](https://en.wikipedia.org/wiki/Observations_and_Measurements)
  * [Observations & Measurements](http://www.opengeospatial.org/standards/om) (O&M) &mdash; The general models and XML encodings for observations and measurements. Not to be confused with OM2, this uses [UCUM](https://github.com/ucum-org/ucum)
* [PUCK Protocol Standard ](http://www.opengeospatial.org/standards/puck) &mdash; Defines a protocol to retrieve a SensorML description, sensor "driver" code, and other information from the device itself, thus enabling automatic sensor installation, configuration and operation.
* [Sensor Model Language](http://www.opengeospatial.org/standards/sensorml) (SensorML) &mdash; Standard models and XML Schema for describing the processes within sensor and observation processing systems.
* [Sensor Observation Service](http://www.opengeospatial.org/standards/sos) (SOS) &mdash; Open interface for a web service to obtain observations and sensor and platform descriptions from one or more sensors.
* [Sensor Planning Service](http://www.opengeospatial.org/standards/sps) (SPS) &mdash; An open interface for a web service by which a client can 1) determine the feasibility of collecting data from one or more sensors or models and 2) submit collection requests.
* [SWE Common Data Model](http://www.opengeospatial.org/standards/swecommon) &mdash; Defines low-level data models for exchanging sensor related data between nodes of the OGC(r) Sensor Web Enablement (SWE) framework.
* [SWE Service Model](http://www.opengeospatial.org/standards/swes) ­&mdash; Defines data types for common use across OGC Sensor Web Enablement (SWE) services. Five of these packages define operation request and response types.
* [SensorThings API](https://en.wikipedia.org/wiki/SensorThings_API)
  * [OGC SensorThings API Part 1: Sensing Version 1.1](https://docs.ogc.org/is/18-088/18-088.html) &mdash; uses OGC O&M
  * [OGC SensorThings API Part 2 – Tasking Core](http://docs.opengeospatial.org/is/17-079r1/17-079r1.html)
* [OBOE: Extensible Observation Ontology](https://github.com/NCEAS/oboe/) &mdash; has it's own unit standards
* [Semantic Sensor Network](https://www.w3.org/TR/vocab-ssn/) &mdash; can use either OM2 or QUDT
* [WaterML](https://www.ogc.org/standards/waterml)
* [WaterML-WQ](http://docs.opengeospatial.org/bp/14-003/14-003.html) &mdash; an O&M and WaterML 2.0 profile for water quality data

#### Earth Science & Biodiversity Schemas

* [GeoSciML](https://en.wikipedia.org/wiki/GeoSciML)
* [Geologic Timescale model](https://raw.githack.com/CGI-IUGS/timescale-ont/master/html/gts.html)
* [Pourabdollah, A., Leibovici, D. G., Simms, D. M., Tempel, P., Hallett, S. H., & Jackson, M. J. (2012). Towards a standard for soil and terrain data exchange: SoTerML. Computers & Geosciences, 45, 270-283.](https://www.researchgate.net/profile/Didier-Leibovici/publication/229087991_Towards_a_standard_for_soil_and_terrain_data_exchange_SoTerML/links/612b52a52b40ec7d8bcedb8b/Towards-a-standard-for-soil-and-terrain-data-exchange-SoTerML.pdf)
* [GeoScience Ontology (GSO)](https://zenodo.org/record/4750707) &mdash; Also see [its associated repo](https://github.com/Loop3D/GKM)
* [DarwinCore](https://dwc.tdwg.org/) &mdash; It includes a glossary of terms (in other contexts these might be called properties, elements, fields, columns, attributes, or concepts) intended to facilitate the sharing of information about biological diversity by providing identifiers, labels, and definitions. Darwin Core is primarily based on taxa, their occurrence in nature as documented by observations, specimens, samples, and related information.
  * [Wieczorek J, Bloom D, Guralnick R, Blum S, Döring M, et al. (2012) Darwin Core: An Evolving Community-Developed Biodiversity Data Standard. PLoS ONE 7(1): e29715.](https://doi.org/10.1371/journal.pone.0029715)

### Catalogs for look up specific data

* [United States Interagency Elevation Inventory](https://coast.noaa.gov/inventory/) &mdash; The U.S. Interagency Elevation Inventory is a comprehensive, nationwide listing of known high-accuracy topographic and bathymetric data for the United States and its territories.
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

### OpenStreetMap Data

* [OpenStreetMap Data Extracts](http://download.geofabrik.de/index.html)

### Natural Earth Map Data

* [Natural Earth Data](https://www.naturalearthdata.com/) &mdash; Natural Earth is a public domain map dataset available at 1:10m, 1:50m, and 1:110 million scales. Featuring tightly integrated vector and raster data, with Natural Earth you can make a variety of visually pleasing, well-crafted maps with cartography or GIS software.

### Paul Wessel's Data

* [GSHHG: A Global Self-consistent, Hierarchical, High-resolution Geography Database](https://www.soest.hawaii.edu/pwessel/gshhg/)
* [DCW-GMT: The Digital Chart of the World for GMT 6 or later](https://www.soest.hawaii.edu/pwessel/dcw/)
* [Global Seamount Database](https://www.soest.hawaii.edu/pwessel/smts/)

### Digital Elevation Maps

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

#### Multiresolution

* [Ryan, W.B.F., S.M. Carbotte, J.O. Coplan, S. O'Hara, A. Melkonian, R. Arko, R.A. Weissel, V. Ferrini, A. Goodwillie, F. Nitsche, J. Bonczkowski, and R. Zemsky (2009), Global Multi-Resolution Topography synthesis, Geochem. Geophys. Geosyst., 10, Q03014, doi:10.1029/2008GC002332.](https://www.gmrt.org/about/index.php) &mdash; The Global Multi-Resolution Topography (GMRT) Synthesis is maintained as a multi-resolution gridded global Digital Elevation Model (DEM) that includes cleaned processed ship-based multibeam sonar data at their full spatial resolution (~100m in the deep sea).
* [GMRTMapTool](https://www.gmrt.org/GMRTMapTool/) &mdash; This lets you view the data.
* [GMRT Web Services](https://www.gmrt.org/services/index.php)

#### 1/30 arc second (~1 meter)

* [1 meter Digital Elevation Models (DEMs) - USGS National Map 3DEP Downloadable Data Collection](https://catalog.data.gov/dataset/usgs-national-elevation-dataset-ned-1-meter-downloadable-data-collection-from-the-national-map-) &mdash; `This is a tiled collection of the 3D Elevation Program (3DEP) and is one meter resolution.`
  * This only had a subset of the US and Mexico, including Hawai'i.
  * Land only.
  * WMS Url: https://services.nationalmap.gov/arcgis/services/3DEPElevationIndex/MapServer/WMSServer?request=GetCapabilities&service=WMS

#### 1/9 arc second (~3 meter)

* [1/9th Arc-second Digital Elevation Models (DEMs) - USGS National Map 3DEP Downloadable Data Collection](https://catalog.data.gov/dataset/national-elevation-dataset-ned-1-9-arc-second-downloadable-data-collection-national-geospatial) &mdash; `This is a tiled collection of the 3D Elevation Program (3DEP) and is 1/9 arc-second (approximately 3 m) resolution.`
  * `The seamless 1/9 arc-second DEM layer project-based coverage for portions of the conterminous United States, limited areas of Alaska, and Guam.`

#### 1/3 arc second (~10 meter)

* [NHDPlus High Resolution](https://www.usgs.gov/core-science-systems/ngp/national-hydrography/nhdplus-high-resolution) &mdash; `The NHDPlus HR is a national, geospatial model of the flow of water across the landscape and through the stream network. The NHDPlus HR is built using the National Hydrography Dataset High Resolution data at 1:24,000 scale or better, the 1/3 arc-second (10 meter ground spacing) 3D Elevation Program data, and the nationally complete Watershed Boundary Dataset.`

#### 1 arc second (~30 meter)

* [Shuttle Radar Topography Mission](https://www2.jpl.nasa.gov/srtm/)
  * [SRTM](https://wiki.openstreetmap.org/wiki/SRTM) &mdash; `The Shuttle Radar Topography Mission (SRTM) (Wikipedia article) is a NASA mission conducted in 2000 to obtain elevation data for most of the world. It is the current dataset of choice for digital elevation model (DEM) data since it has a fairly high resolution (1 arc-second, or around 25 meters), has near-global coverage (from 56°S to 60°N), and is in the public domain.`
  * [30-Meter SRTM Tile Downloader](https://dwtkns.com/srtm30m/) &mdash; This interface attempts to ease the pain of downloading 30-meter resolution elevation data from the Shuttle Radar Topography Mission.
  * Land only.
* [AW3D30](https://wiki.openstreetmap.org/wiki/AW3D30) &mdash; The ALOS Global Digital Surface Model "ALOS World 3D - 30m" (AW3D30) is the dataset with a horizontal resolution of approximately 30-meter mesh (1 arcsec), provided by Japan Aerospace Exploration Agency (JAXA) free of charge.
  * Land only.
* [ASTER Global Digital Elevation Map](https://asterweb.jpl.nasa.gov/gdem.asp) &mdash; Advanced Spaceborne Thermal Emission and Reflection Radiometer.
  * [NASA/METI/AIST/Japan Spacesystems, and U.S./Japan ASTER Science Team (2019). ASTER Global Digital Elevation Model V003 [Data set]. NASA EOSDIS Land Processes DAAC. Accessed 2019-10-22 from https://doi.org/10.5067/ASTER/ASTGTM.003](https://search.earthdata.nasa.gov/search/granules/collection-details?p=C1575726572-LPDAAC_ECS&q=GDEM&tl=1555913685!4!!)
  * Land only.

#### 15 arc second (~500 meter)
* [SRTM15+V2.0](https://topex.ucsd.edu/WWW_html/srtm15_plus.html) &mdash; [FTP](ftp://topex.ucsd.edu/pub/srtm15_plus/) &mdash; [figshare](https://figshare.com/projects/SRTM15_V2_0/62045)
  * [Tozer, B. , D. T. Sandwell, W. H. F. Smith, C. Olson, J. R. Beale, and P. Wessel, Global bathymetry and topography at 15 arc seconds: SRTM15+, Accepted Earth and Space Science, August 3, 2019. DOI: 10.1029/2019EA000658](https://topex.ucsd.edu/sandwell/publications/180_Tozer_SRTM15+.pdf)
* [GEBCO 2019 Gridded Bathymetry Data](https://www.gebco.net/data_and_products/gridded_bathymetry_data/) &mdash; GEBCO’s gridded bathymetric data set, the GEBCO_2019 grid, is a global terrain model for ocean and land at 15 arc-second intervals.
  * [Blue Earth Bathymetry](http://www.shadedrelief.com/blue-earth/) &mdash; Generalized GEBCO Data for Seafloor Mapping.
* [SRTM15_PLUS](https://catalog.data.gov/dataset/srtm15-plus-data-fusion-of-shuttle-radar-topography-mission-srtm-land-topography-with-measured-) &mdash; To provide an improved mapping of the seafloor fabric globally, we have used available sounding data along with an improved global marine gravity model to develop at grid at 15 arcsecond resolution (~500 m). Land elevations are based on the best available data from SRTM, ASTER digital elevation models while the ice topography of Greenland and Antarctica is based on CryoSat-2 and IceSat. Ocean bathymetry is based on bathymetric predictions from the latest global gravity model from CryoSat-2 and Jason-1 along with 494 million carefully edited depth soundings at 15 arcsecond resolution. Bathymetry of the Arctic seafloor is based on the IBCAO grid with improved resolution in areas of multibeam coverage. We have used the bathymetry grid along with the improved gravity to construct a global map of abyssal hill amplitude and orientations and compare the orientations with predictions from seafloor age gradient analysis. Areas of disagreement reveal propagating rifts, microplates, and tectonic reorganizations. This SRTM15_PLUS provides the foundational bathymetry layer for Google Earth and is freely available at our ftp site (topex.ucsd.edu).

#### 30 arc seconds (~1 km)

* [USGS EROS Archive - Digital Elevation - Global 30 Arc-Second Elevation (GTOPO30)](https://www.usgs.gov/centers/eros/science/usgs-eros-archive-digital-elevation-global-30-arc-second-elevation-gtopo30?qt-science_center_objects=0#qt-science_center_objects) &mdash; GTOPO30 is a global digital elevation model (DEM) with a horizontal grid spacing of 30 arc seconds (approximately 1 kilometer). GTOPO30 was derived from several raster and vector sources of topographic information.
* [GMTED2010](https://www.usgs.gov/land-resources/eros/coastal-changes-and-impacts/gmted2010?qt-science_support_page_related_con=0#qt-science_support_page_related_con) &mdash; The USGS and the National Geospatial-Intelligence Agency (NGA) have collaborated on the development of a notably enhanced global elevation model called the Global Multi-resolution Terrain Elevation Data (GMTED2010), which has replaced GTOPO30 as the elevation dataset of choice for global and continental scale applications.
* [USGS EROS Archive - Digital Elevation - Global Multi-resolution Terrain Elevation Data 2010 (GMTED2010)](https://www.usgs.gov/centers/eros/science/usgs-eros-archive-digital-elevation-global-multi-resolution-terrain-elevation?qt-science_center_objects=0#qt-science_center_objects) &mdash; The Global Multi-resolution Terrain Elevation Data 2010 (GMTED2010) provides a new level of detail in global topographic data. The GMTED2010 product suite contains seven new raster elevation products for each of the 30-, 15-, and 7.5-arc-second spatial resolutions and incorporates the current best available global elevation data.

### Geological Data

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

### Paleobiological Data

* [Paleobiology Database](https://paleobiodb.org)
* [Paleobiology Database: UW-Madison on Github](https://github.com/paleobiodb)
* [EarthLife Consortium](http://earthlifeconsortium.org/)
* [EarthLife Consortium on Github](https://github.com/EarthLifeConsortium)
* [Neotoma Paleoecology Database and Community](https://www.neotomadb.org/)

## GIS Software

### Desktop Mapping Tools

* [OSGeoLive](https://live.osgeo.org/en/index.html) &mdash; self-contained bootable DVD, USB thumb drive or Virtual Machine based on Lubuntu, that allows you to try a wide variety of open source geospatial software without installing anything.
* [QGIS](https://qgis.org/en/site/) &mdash; A Free and Open Source Geographic Information System.
* [Alex's QGIS Python Plugins](https://plugins.bruy.me/plugins/plugins.xml) &mdash; A collection of QGIS plugins written by Alexander Bruy.
* [GRASS](https://grass.osgeo.org/) &mdash; GRASS GIS is a Geographic Information System used for geospatial data management and analysis, image processing, graphics/map production, spatial modeling, and visualization.
  * > **G**eographic **R**esources **A**nalysis **S**upport **S**ystem, commonly referred to as GRASS GIS, is a Geographic Information System (GIS) technology built for vector and raster geospatial data management, geoprocessing, spatial modelling and visualization.
* [gvGIS](http://www.gvsig.com/en/products/gvsig-desktop) &mdash; gvSIG Desktop (gvSIG from this point forward) is a Geographical Information System in free software, that is, a computer application aimed to represent, edit, analyze and manage information from the point of view of spatial relations.
* [WhiteboxTools Open Core](https://www.whiteboxgeo.com/geospatial-software/) &mdash; WhiteboxTools is an advanced geospatial software package and a data analysis platform developed at the University of Guelph’s Geomorphometry and Hydrogeomatics Research Group (GHRG). The project began in January 2017 and quickly evolved in terms of its analytical capabilities. Contains more than 450 tools for processing various types of geospatial data.
* [The Generic Mapping Tools](https://github.com/GenericMappingTools/gmt) &mdash; The Generic Mapping Tools (GMT) are widely used across the Earth, Ocean, and Planetary sciences and beyond. A diverse community uses GMT to process data, generate publication-quality illustrations, automate workflows, and make animations. Scientific journals, posters at meetings, Wikipedia pages, and many more publications display illustrations made by GMT. And the best part: it is free, open source software licensed under the LGPL.
  * > GMT is an open source collection of about 90 command-line tools for manipulating geographic and Cartesian data sets (including filtering, trend fitting, gridding, projecting, etc.) and producing high-quality illustrations ranging from simple x–y plots via contour maps to artificially illuminated surfaces, 3D perspective views and animations. The GMT supplements add another 50 more specialized and discipline-specific tools. GMT supports over 30 map projections and transformations and requires support data such as GSHHG coastlines, rivers, and political boundaries and optionally DCW country polygons.
* [GeoMapApp](http://www.geomapapp.org/)
  * > GeoMapApp is a map-based application for browsing, visualizing and analyzing a diverse suite of curated global and regional geoscience data sets. These cover geophysics, geology, geochemistry, physical oceanography, climatology, and more.
  * > GeoMapApp provides data layering, display customization and analytical tools to support the analysis of multidisciplinary data sets. Choose from Mercator, North polar and South polar projections. Save the images for papers and presentations.
  * __Not open source, but freely available.__
* [GPlates](http://www.gplates.org/index.html) &mdash; [Sourceforge](https://sourceforge.net/projects/gplates/)
  * > GPlates is a plate tectonics program. Manipulate reconstructions of geological and paleogeographic features through geological time. Interactively visualize vector, raster and volume data. PyGPlates is the GPlates Python library. Get fine-grained access to GPlates functionality in your Python scripts.
* [GeoGig](http://geogig.org/) &mdash; GeoGig is an open source tool that draws inspiration from Git, but adapts its core concepts to handle distributed versioning of geospatial data.
  * > Users are able to import raw geospatial data (currently from Shapefiles, PostGIS or SpatiaLite) in to a repository where every change to the data is tracked. These changes can be viewed in a history, reverted to older versions, branched in to sandboxed areas, merged back in, and pushed to remote repositories.
  * > GeoGig is written in Java, and available under the Eclipse Distribution License (a BSD 3 Clause license).

### Smartphone/Tablet

#### Android

* [Arbiter](https://github.com/ROGUE-JCTD/Arbiter-Android)

### 3D Relief Map Making

* [Blender GIS](https://github.com/domlysz/BlenderGIS) &mdash; Blender addons to make the bridge between Blender and geographic data.
  * [Making 3D landscape in Blender using GIS Addon (Video)](https://www.youtube.com/watch?v=6Cw_uJCp39k)
  * somethingaboutmaps
    * [CREATING SHADED RELIEF IN BLENDER](https://somethingaboutmaps.wordpress.com/2017/11/16/creating-shaded-relief-in-blender/)
    * [ADDING SHADED RELIEF IN PHOTOSHOP](https://somethingaboutmaps.wordpress.com/2014/10/26/adding-shaded-relief-in-photoshop/)
    * [TERRAIN IN PHOTOSHOP: LAYER BY LAYER](https://somethingaboutmaps.wordpress.com/2016/10/03/terrain-in-photoshop/)
    * [TOWARDS LESS BLENDER-Y RELIEF](https://somethingaboutmaps.wordpress.com/2022/01/13/towards-less-blender-y-relief/)
    * [A GENERALIZATION RAMBLE](https://somethingaboutmaps.wordpress.com/2022/01/31/a-generalization-ramble/)
  * The Wandering Cartographer
    * [Shaded relief with BlenderGIS (2020), part 1](https://wanderingcartographer.wordpress.com/2019/11/08/making-shaded-relief-with-blendergis-2019/)
    * [Shaded Relief with BlenderGIS (2019), part 2](https://wanderingcartographer.wordpress.com/2019/11/08/shaded-relief-with-blendergis-2019-part-2/)
    * [Shaded relief with BlenderGIS (2019), part 3](https://wanderingcartographer.wordpress.com/2019/11/24/shaded-relief-with-blendergis-2019-part-3/)
    * [Cutting large DEMs into square, partially overlapping tiles](https://wanderingcartographer.wordpress.com/2014/11/14/cutting-large-dems-into-square-partially-overlapping-tiles/)
    * [A new map of the Bulkley Valley](https://wanderingcartographer.wordpress.com/2015/05/27/a-new-map-of-the-bulkley-valley/)
* [Raster Chunk Processing (rcp)](https://github.com/jacobdadams/rcp) &mdash; Parallelized raster chunk processing. [Makes some of the prettiest relief maps. -JB]
  * [Part I: Introducing raster_chunk_processing.py (aka, RCP)](https://gisjake.blogspot.com/2018/10/introducing-rasterchunkprocessingpy-aka.html)
  * [Part II: raster_chunk_processing.py Installation and Usage](https://gisjake.blogspot.com/2018/10/rasterchunkprocessingpy-installation.html)
  * [Part III: raster_chunk_processing.py Examples](https://gisjake.blogspot.com/2018/10/rasterchunkprocessingpy-examples.html)
  * [rcp: UGIC 2019 Presentation](https://drive.google.com/file/d/1fW8m9r2CcVDMlAPGgA0uyrg56LL9CLYM/view)
  * [Shaded Relief using Skymodels, courtesy of Raster Chunk Processing](https://wanderingcartographer.wordpress.com/2020/05/08/shaded-relief-using-skymodels-courtesy-of-raster-chunk-processing/)
    * [Skymodels gallery](https://wanderingcartographer.wordpress.com/skymodels-gallery/)
  * [Skymodels With rcp: A Couple Quick Notes](https://gisjake.blogspot.com/2020/05/skymodels-with-rcp-couple-quick-notes.html)
  * [Kennelly, Patrick J., and A. James Stewart. "General sky models for illuminating terrains." International Journal of Geographical Information Science 28, no. 2 (2014): 383-406.](http://myweb.liu.edu/pkennell/reprints/peer-reviewed/GeneralSkyModels.pdf)
* [Shaded Relief](http://www.shadedrelief.com/index.html) &mdash; This site started out as a resource for cartographers creating shaded relief, panoramas, land cover, and related raster art on maps. It has since grown to include my other cartographic interests and has become a repository for my maps, all of which are in the public domain. &mdash; Tom Patterson
  * The tools covered in here are not all open source, but the principles still apply.

### Frontend Frameworks (Client Only)

  * [Dymaxion projection in OpenLayers](https://indiemaps.com/blog/2011/04/dymaxion-projection-in-openlayers/)
* [GeoMoose](https://www.geomoose.org/) &mdash; GeoMoose is a Web Client JavaScript Framework for displaying distributed cartographic data. GeoMoose has a number of strengths including modularity, configurability, and delivers a number of core functionalities in its packages. GeoMoose is also very light weight for servers making it easy to handle a large number of users, with a large number of layers, and a large number of services without stressing a server.
* [GeoExt](https://www.geoext.org/) &mdash; JavaScript Toolkit for Rich Web Mapping Applications
  * Uses Ext and OpenLayers.

### Front End Libraries

* [CesiumJS](https://github.com/AnalyticalGraphicsInc/cesium) &mdash; An open-source JavaScript library for world-class 3D globes and maps. :earth_americas:
* [Leaflet](https://leafletjs.com/) &mdash; Leaflet is the leading open-source JavaScript library for mobile-friendly interactive maps. Weighing just about 39 KB of JS, it has all the mapping features most developers ever need.
  * [Mapping with gpu.js](https://geoexamples.com/other/2018/04/30/mapping-with-gpujs.html/)
    * [L.CanvasLayer](https://github.com/Sumbera/gLayers.Leaflet) &mdash; full screen generic canvas layer for leaflet.
    * [Complex GIS calculations with gpu.js: Temperature interpolation](https://geoexamples.com/other/2018/09/17/gpujs-example.html/)
  * [Leaflet.heat](https://github.com/Leaflet/Leaflet.heat) &mdash; A tiny, simple and fast heatmap plugin for Leaflet.
* [NASA WorldWind](https://worldwind.arc.nasa.gov/web/)
* [OpenLayers](https://openlayers.org/) &mdash; OpenLayers makes it easy to put a dynamic map in any web page. It can display map tiles, vector data and markers loaded from any source. OpenLayers has been developed to further the use of geographic information of all kinds. It is completely free, Open Source JavaScript, released under the 2-clause BSD License (also known as the FreeBSD).
* [geotiff.js](https://geotiffjs.github.io/) &mdash; geotiff.js aims to support as many TIFF features as possible, including various image compression methods, geographical information, internal tiling, pixel or band interleaving, automatic transformation from several color spaces to RGB, and much more.
* [plotty.js](https://github.com/santilland/plotty/) &mdash; Plotting library experiments using WebGL and Canvas2D to apply color scale to a bufferarray object.
  * [GEOTIFF.JS AND PLOTTY.JS VISUALIZING SCIENTIFIC RASTER DATA IN THE BROWSER](https://constantinius.github.io/foss4g-geotiff.js-plotty.js/#/)
* [GPU.JS](https://gpu.rocks/) &mdash; GPU.js is a JavaScript Acceleration library for GPGPU (General purpose computing on GPUs) in JavaScript for Web and Node. GPU.js automatically transpiles simple JavaScript functions into shader language and compiles them so they run on your GPU. In case a GPU is not available, the functions will still run in regular JavaScript. For some more quick concepts, see Quick Concepts on the wiki.

### Application Frameworks (Client/Server Combined)

* [GeoNode](https://geonode.org/) &mdash; GeoNode is a web-based application and platform for developing geospatial information systems (GIS) and for deploying spatial data infrastructures (SDI).
  * > GeoNode is a geospatial content management system, a platform for the management and publication of geospatial data. It brings together mature and stable open-source software projects under a consistent and easy-to-use interface allowing non-specialized users to share data and create interactive maps.
  * > GeoNode is built upon a platform of proven open source components including Django, GeoServer, pycsw, OpenLayers and GeoExt. GeoNode implements many Open Geospatial Consortium (OGC) standards, including Web Map Service (WMS), Web Feature Service (WFS), Web Coverage Service (WCS), KML, and Catalogue Service for Web (CSW). GeoNode development also contributes to the underlying open source projects and software libraries.
  * [GeoSHAPE](https://github.com/ROGUE-JCTD/rogue_geonode) &mdash; A Django package that adds GeoSHAPE functionality to GeoNode.
  * [MapLoom](https://github.com/ROGUE-JCTD/MapLoom) &mdash; MapLoom is a web mapping client based on OpenLayers 3. It provides full-featured editing capabilities for data stores in GeoServer - including PostGIS and GeoGig. For GeoGig layers, it lets you view history, and sync with other GeoGig repositories.
  * [GeoGig](http://geogig.org/) &mdash; GeoGig is an open source tool that draws inspiration from Git, but adapts its core concepts to handle distributed versioning of geospatial data.
* [Geomajas](http://www.geomajas.org/) &mdash; Geomajas is a collection of free and open source GIS libraries, tools and API's for a complete end-to-end web mapping solution.
* [MapFish](http://www.mapfish.org/) &mdash; MapFish is a flexible and complete framework for building rich web-mapping applications. It emphasizes high productivity, and high-quality development. MapFish is based on the Pylons Python web framework. MapFish extends Pylons with geospatial-specific functionality. For example MapFish provides specific tools for creating web services that allows querying and editing geographic objects.
* [GeoSHAPE (Geospatial capabilities for Security, Humanitarian Assistance, Partner Engagement) [This seems to not be available anymore. -JB]](http://web.archive.org/web/20191130064700/http://geoshape.org/) &mdash; GeoSHAPE gives organizations the ability to create, share, and visualize information through dynamic, collaborative maps.
  * See GeoNode above.
  * > Geospatial capabilities for Security, Humanitarian Assistance, Partner Engagement – is designed to enable collaboration on geospatial information between mission partners in connected and disconnected operations. GeoSHAPE has been built utilizing open source software and open standards to make it available for partners and to maximize interoperability. GeoSHAPE is the integration of a geospatial portal (GeoNode), a web mapping client (MapLoom), and a mobile application (Arbiter), that leverages the infrastructure provided by a geospatial server and database components. GeoSHAPE is the outcome of the Rapid Open Geospatial User-Driven Enterprise (ROGUE) Joint Capability Technology Demonstration (JCTD).
  * [ROGUE GeoTech2013 Talk](https://speakerdeck.com/scottevil/rogue-geotech2013-talk)
  * [Distributed Versioned Editing in Action](https://speakerdeck.com/scottevil/distributed-versioned-editing-in-action)
  * [Arbiter GeoDC Lightning Talk](https://speakerdeck.com/scottevil/arbiter-geodc-lightning-talk)
  * [Case Study: Developing OpenLayers-based Mobile Applications — Syrus Mesdaghi, LMN Solutions / NSP-Noblis, Kevin Zusy, No](https://vimeo.com/106852747)

### GIS Servers (Server Only)

* [GeoServer](http://geoserver.org/) &mdash; GeoServer is an open source server for sharing geospatial data. Written in Java, GWT, & Javascript.
* [Tegola](https://www.tegola.io/) &mdash; An open source vector tile server written in Go, Tegola takes geospatial data and slices it into vector tiles that can be efficiently delivered to any client.
* [IstSOS](http://istsos.org/) &mdash; IstSOS is an OGC SOS server implementation written in Python.
  * _SOS_ stands for Sensor Observation Service.
* [deegree](https://www.deegree.org/) &mdash; deegree is open source software for spatial data infrastructures and the geospatial web. deegree offers components for geospatial data management, including data access, visualization, discovery and security. Open standards are at the heart of deegree.
  * > deegree webservices are implementations of the geospatial webservice specifications of the Open Geospatial Consortium (OGC) and the INSPIRE Network Services. deegree webservices 3.4 includes the following services:
    * [Web Feature Service (WFS)](http://www.opengeospatial.org/standards/wfs): Provides access to raw geospatial data objects
    * [Web Map Service (WMS)](http://www.opengeospatial.org/standards/wms): Serves maps rendered from geospatial data
    * [Web Map Tile Service (WMTS)](http://www.opengeospatial.org/standards/wmts): Serves pre-rendered map tiles
    * [Catalogue Service for the Web (CSW)](http://www.opengeospatial.org/standards/cat): Performs searches for geospatial datasets and services
    * [Web Processing Service (WPS)](http://www.opengeospatial.org/standards/wps): Executes geospatial processes
  * > With a single deegree webservices installation, you can set up one of the above services, all of them or even multiple services of the same type. The remainder of this chapter introduces some notable features of the different service implementations and provides learning trails for learning the configuration of each service.
* [collada2gltf-web-service](https://github.com/AnalyticalGraphicsInc/collada2gltf-web-service) &mdash; Simple Node.js web service to convert 3D models from COLLADA to glTF.
* [PostGIS](https://postgis.net/) &mdash; PostGIS is a spatial database extender for PostgreSQL object-relational database. It adds support for geographic objects allowing location queries to be run in SQL.

### Data at Scale (Tools for Building Massive Systems to Process Data)

* [SELEN](https://geodynamics.org/cig/software/selen/) &mdash; Program for solving the sea level equation.
* [GeoMesa](https://www.geomesa.org/) &mdash; Store, index, query, and transform spatio-temporal data at scale.
in HBase, Accumulo, Cassandra, Kafka and Spark.
* [GeoWave](https://locationtech.github.io/geowave/) &mdash; GeoWave provides geospatial and temporal indexing on top of Accumulo and HBase.
* [GeoTrellis](https://geotrellis.io/) &mdash; GeoTrellis is a geographic data processing engine for high performance applications.
* [Pangeo](https://pangeo.io/) &mdash; "Pangeo is first and foremost a community promoting open, reproducible, and scalable science. This community provides documentation, develops and maintains software, and deploys computing infrastructure to make scientific research and programming easier. The Pangeo software ecosystem involves open source tools such as xarray, iris, dask, jupyter, and many other packages. There is no single software package called 'pangeo'; rather, the Pangeo project serves as a coordination point between scientists, software, and computing infrastructure."
* [EOSDIS Data in the Cloud: User Requirements](https://earthdata.nasa.gov/eosdis-data-in-the-cloud-user-requirements) &mdash; "A primary objective of hosting EOSDIS data in the cloud is to 'level the playing field' so anyone can work with these Big Data collections. The ideal user experience (UX) allows data users to work next to EOSDIS data in the cloud, meaning that a user can simply point their analysis software to a data location in the cloud and begin analyzing without the need to transfer or download data. After completing their analyses, a user can view or download the results. An integral part of facilitating this is preprocessing these data into Analysis Ready Data (ARD), which enables end-users to begin working with data immediately."
* [Earthdata Developer Portal](https://developer.earthdata.nasa.gov/) &mdash; The Earthdata Developer Portal is the central location for all publicly accessible developer documentation related to EOSDIS enterprise services and applications.
* [Energy Exascale Earth System Model](https://e3sm.org/) &mdash; DOE's E3SM is a state-of-the-science Earth system model development and simulation project to investigate energy-relevant science using code optimized for DOE's advanced computers.
* [Energy Exascale Earth System Model source code](https://github.com/E3SM-Project/E3SM)
* [Common Infrastructure for Modeling the Earth (CIME - pronounced “SEAM”)](http://esmci.github.io/cime/index.html) &mdash; The Common Infrastructure for Modeling the Earth (CIME - pronounced “SEAM”) provides a Case Control System for configuring, compiling and executing Earth system models, data and stub model components, a driver and associated tools and libraries.
* [MOAB — The Mesh-Oriented datABase](https://press3.mcs.anl.gov/sigma/moab-library/) &mdash; "The Mesh-Oriented datABase (MOAB) is a component for representing and evaluating mesh data. MOAB can store structured and unstructured mesh, consisting of elements in the finite element 'zoo' plus polygons and polyhedra. The functional interface to MOAB is simple yet powerful, allowing the representation of many types of metadata commonly found on the mesh. MOAB is optimized for efficiency in space and time, based on access to mesh in chunks rather than through individual entities, while also versatile enough to support individual entity access. The MOAB library can naturally represent finite element and other types of mesh data [1]. Various types of meta-data are often used in conjunction with a mesh. Examples include boundary condition groupings, material types, and provenance information for the mesh. Because the data model used in MOAB is so abstract, conventions are useful for describing how meta-data is stored into that data model."
* [Parvis](https://trac.mcs.anl.gov/projects/parvis) &mdash; Parallel Analysis Tools and New Visualization Techniques for Ultra-Large Climate Data Sets.
* [pagoda](https://github.com/jeffdaily/pagoda) &mdash; Parallel Analysis of GeOscienceData.
* [Swift](http://swift-lang.org/main/index.php) &mdash; A simple tool for fast, easy scripting on big machines.
* [PVFS: Parallel Virtual File System](https://www.anl.gov/mcs/pvfs-parallel-virtual-file-system) &mdash; PVFS (Parallel Virtual File System) serves as both a platform for I/O research, and a production file system for the cluster computing community.
* [JIGSAW(GEO)](https://github.com/dengwirda/jigsaw-geo-matlab) &mdash; JIGSAW(GEO) is an unstructured mesh generator for geoscientific modelling.

### Libraries

* [Terraformer](http://terraformer.io/) &mdash; Terraformer is an open source (MIT licensed) Javascript geo toolkit, built for the server and the browser.
* [LocationTech JTS Topology Suite](https://projects.eclipse.org/projects/locationtech.jts) &mdash; The LocationTech JTS Topology Suite (JTS) is an open source Java software library that provides an object model for planar geometry together with a set of fundamental geometric functions.
* [GEOS - Geometry Engine, Open Source](http://trac.osgeo.org/geos) &mdash; GEOS (Geometry Engine - Open Source) is a C++ port of the ​JTS Topology Suite (JTS). It aims to contain the complete functionality of JTS in C++. This includes all the ​OpenGIS Simple Features for SQL spatial predicate functions and spatial operators, as well as specific JTS enhanced functions. GEOS provides spatial functionality to many other projects and products.
* [PDAL - Point Data Abstraction Library](https://pdal.io/index.html) &mdash; PDAL is a C++ BSD library for translating and manipulating point cloud data. It is very much like the GDAL library which handles raster and vector data.
* [LAStools](https://github.com/LAStools/LAStools) &mdash; efficient tools for LiDAR processing.
* [OBJ2GLTF](https://github.com/CesiumGS/obj2gltf)
* [CDB to 3D Tiles](https://github.com/CesiumGS/cdb-to-3dtiles)
* [b3dm.tooling](https://github.com/bertt/b3dm.tooling)
* [GDAL - Geospatial Data Abstraction Library](https://gdal.org/) &mdash; GDAL is a translator library for raster and vector geospatial data formats that is released under an X/MIT style Open Source license by the Open Source Geospatial Foundation.
* [Parallel I/O Libraries (PIO)](https://ncar.github.io/ParallelIO/) &mdash; The Parallel IO libraries (PIO) are high-level parallel I/O C and Fortran libraries for structured grid applications. PIO provides a netCDF-like API, and allows users to designate some subset of processors to perform IO. Computational code calls netCDF-like functions to read and write data, and PIO uses the IO processors to perform all necessary IO.
* [PnetCDF](https://trac.mcs.anl.gov/projects/parallel-netcdf) &mdash; PnetCDF is a high-performance parallel I/O library for accessing files in format compatibility with ​Unidata's NetCDF, specifically the formats of CDF-1, 2, and 5. The CDF-5 file format, an extension of CDF-2, supports unsigned data types and uses 64-bit integers to allow users to define large dimensions, attributes, and variables (> 2B array elements).
* [ROMIO](https://www.mcs.anl.gov/projects/romio/) &mdash; ROMIO is a high-performance, portable implementation of MPI-IO, the I/O chapter in MPI-2. ROMIO is optimized for noncontiguous access patterns, which are common in parallel applications. It has an optimized implementation of collective I/O, an important optimization in parallel I/O.
* [GeoTools](https://geotools.org/) &mdash; GeoTools is an open source Java library that provides tools for geospatial data.
* [Orfeo ToolBox](https://www.orfeo-toolbox.org/) &mdash; Orfeo ToolBox is an open-source project for state-of-the-art remote sensing, including a fast image viewer, apps callable from Bash, Python or QGIS, and a powerful C++ API.
* [pygplates](https://sourceforge.net/projects/gplates/files/pygplates/beta-revision-18/)
* [PlateTectonicTools](https://github.com/EarthByte/PlateTectonicTools)
* [spatial-temporal-exploration](https://github.com/EarthByte/spatial-temporal-exploration)
* [predicting-sediment-thickness](https://github.com/EarthByte/predicting-sediment-thickness)
* [paleoclimate-reconstruction](https://github.com/EarthByte/paleoclimate-reconstruction)
* [GPplus](https://github.com/sebhaan/GPplus)
* [UW-Deepdive-Infrastructure/blackstack](https://github.com/UW-Deepdive-Infrastructure/blackstack)
* [CitcomS with Data Assimilation](https://github.com/EarthByte/citcoms)
  * [Bower DJ, Gurnis M, Flament N (2015) Assimilating lithosphere and slab history in 4-D Earth models. Phys. Earth Planet. Inter., 238: 8-22. doi: 10.1016/j.pepi.2014.10.013.](https://eartharxiv.org/9aey5/)
* [PyBacktrack](https://github.com/EarthByte/pyBacktrack) &mdash; A tool for reconstructing paleobathymetry on oceanic and continental crust.
  * [Müller RD, Cannon J, Williams S, Dutkiewicz A (2018) PyBacktrack 1.0: A Tool for Reconstructing Paleobathymetry on Oceanic and Continental Crust. Geochemistry, Geophysics, Geosystems. 19: 1898-1909. doi: 10.1029/2017GC007313](https://www.researchgate.net/publication/325045269_PyBacktrack_10_A_Tool_for_Reconstructing_Paleobathymetry_on_Oceanic_and_Continental_Crust)
* [EarthByte/UW2-tests-and-benchmarks](https://github.com/EarthByte/UW2-tests-and-benchmarks)
* [LavaVu](https://github.com/lavavu/LavaVu) &mdash; Lightweight, Automatable Visualisation & Analysis Viewing Utility
  * [Kaluza O, Moresi L, Mansour J, Barnes DG. lavavu/LavaVu: v1.4.6. Zenodo; 2019. doi:10.5281/zenodo.3470773](http://doi.org/10.5281/zenodo.3470773)
* [stripy](https://github.com/underworldcode/stripy) &mdash; 2D spherical and Cartesian triangulation toolkit using tripack, stripack, srfpack and ssrfpack.
  * [Moresi L and Mather BR, (2019) Stripy: A Python module for (constrained) triangulation in Cartesian coordinates and on a sphere. Journal of Open Source Software. 4(38): 1410.](https://doi.org/10.21105/joss.01410)
* [underworld2](https://github.com/underworldcode/underworld2) &mdash; A parallel, particle-in-cell, finite element code for Geodynamics.
  * [jmansour, Kaluza O, Giordani J, Beucher R, Farrington R, Kennedy G, et al. underworldcode/underworld2: v2.8.1b. Zenodo; 2019. doi:10.5281/zenodo.3384283](http://doi.org/10.5281/zenodo.3384283)
* [Underworld Geodynamics](https://github.com/underworldcode/UWGeodynamics)
  * [Beucher R, Laik A, Giordani J, Mondy L, Farrington R, Barba LA, et al. underworldcode/UWGeodynamics: UWGeodynamics v2.8. Zenodo; 2019. doi:10.5281/zenodo.3366398](http://doi.org/10.5281/zenodo.3366398)
  * [Beucher R et al. (2019) UWGeodynamics: A teaching and research tool for numerical geodynamic modelling. Journal of Open Source Software. 4(36): 1136](https://doi.org/10.21105/joss.01136)
* [Loop3D/surfe](https://github.com/Loop3D/surfe) &mdash; Surface modelling engine for geological applications
* [Loop3D/LoopStructural](https://github.com/Loop3D/LoopStructural) &mdash; LoopStructural is an open-source 3D structural geological modelling library.
* [Map2Loop 2.0](https://github.com/Loop3D/map2loop-2)
* [Loop : Enabling Stochastic 3D Geological Modelling](https://loop3d.github.io/)

## Learning QGIS

* [A Gentle Introduction to GIS](https://docs.qgis.org/3.4/en/docs/gentle_gis_introduction/index.html)
* [QGIS Training Manual](https://docs.qgis.org/3.4/en/docs/training_manual/index.html)
* [QGIS User Guide](https://docs.qgis.org/3.4/en/docs/user_manual/index.html)
* [Introduction to GRASS GIS](https://www.osgeo.org/resources/introduction-to-grass-gis/)
  * [Slides GRASS GIS intro – PDF](http://geostat-course.org/system/files/GRASS_geostat_landau_2011_intro.pdf)
  * [Slides GRASS GIS and Geostatistics (Exercises) – PDF](http://geostat-course.org/system/files/GRASS_geostat_landau_2011_exercise.pdf)
* [GRASS 6.4 workshop](https://www.osgeo.org/resources/grass-6-4-workshop/)
  * [First part of the workshop](http://www.agt.bme.hu/gis/grass/grass_workshop_1.pdf)
  * [Second part of the workshop](http://www.agt.bme.hu/gis/grass/grass_workshop_2.pdf)
  * [Sample data](http://www.agt.bme.hu/gis/grass/grass_demo.zip)
* [Introduction to FOSS GIS using QGIS .8, PostgreSQL, PostGIS, and the Grass plugin for QGIS](https://www.osgeo.org/resources/introduction-to-foss-gis-using-qgis-8-postgresql-postgis-and-the-grass-plugin-for-qgis/)
  * [QGIS .8 Overview Exercise](http://trac.osgeo.org/osgeo/browser/education/Releases/UMass/IntroductionToGisUsingQgisV0.8/M1-Exercise-QGISOverview/PDF/QGIS%20Overview.pdf?format=raw)
  * [Installing QGIS](http://trac.osgeo.org/osgeo/browser/education/Releases/UMass/IntroductionToGisUsingQgisV0.8/M4-Exercise-InstallingQGIS/PDF/InstallingQGIS.pdf?format=raw)
  * [Internet GIS Data Resources – USA and Global](http://trac.osgeo.org/osgeo/browser/education/Releases/UMass/IntroductionToGisUsingQgisV0.8/M5-Exercise-WebGISDataResources-USandGlobal/PDF/DataResourcesUSandGlobal.pdf?format=raw)
  * [An Example of Regional Data Resources – A Massachusetts Exercise](http://trac.osgeo.org/osgeo/browser/education/Releases/UMass/IntroductionToGisUsingQgisV0.8/M6-Exercise-AnExampleOfRegionalWebResource-Massachusetts%2CUSADigitalData/PDF/ExampleMaUSADigitalData.pdf?format=raw)
  * [Georeferencing with QGIS .8.0 Exercise](http://trac.osgeo.org/osgeo/browser/education/Releases/UMass/IntroductionToGisUsingQgisV0.8/M8-%20Exercise-%20Georeferencing%20with%20QGIS/PDF/ExGeoreferencingWithQGIS.pdf?format=raw)
  * [Online Digitizing and Adding Attribute Data with QGIS .8 Exercise](http://trac.osgeo.org/osgeo/browser/education/Releases/UMass/IntroductionToGisUsingQgisV0.8/M10-%20Exercise-%20Online%20Digitizing%20and%20Adding%20Attribute%20Data%20using%20QGIS/PDF/DigitizingandAddingAttributeData.pdf?format=raw)
  * [GPS field exercise](http://trac.osgeo.org/osgeo/browser/education/Releases/UMass/IntroductionToGisUsingQgisV0.8/M12-Exercise-GPSFieldExercise%28ForPeopleWithAGPS%29/PDF/GPSFieldExercise.pdf?format=raw)
* [Introduction to QGIS](https://www.osgeo.org/resources/introduction-to-qgis/)
  * [Introduction to QGIS](http://www.geod.bme.hu/gis/qgis/qgis_tutor_2.0.pdf)
  * [Digitizing in QGIS](http://www.geod.bme.hu/gis/qgis/vektorizalas2.pdf)
  * [Editing maps](http://www.geod.bme.hu/gis/qgis/qgis_editing2.pdf)
  * [Importing table data (csv, odc, xls)](http://www.geod.bme.hu/gis/qgis/ods.pdf)
* [PostGIS workshop](https://www.osgeo.org/resources/postgis-workshop/)
  * [Workshop presentation](http://www.gita.hu/e2013/b3/teradat_workshop.pdf)
  * [Sample data 1st part](http://www.gita.hu/e2013/b3/mo.zip)
  * [Sample data 2nd part](http://www.gita.hu/e2013/b3/kozmu.zip)
* [QGIS Python programming - Hungarian](https://www.osgeo.org/resources/qgis-python-programming/)
  * [Python in a nutshell](http://www.agt.bme.hu/gis/python/python_oktato.pdf)
  * [Python injection points to QGIS](http://www.agt.bme.hu/gis/qgis/qgis_and_python.pdf)
  * [Script runner plugin](http://www.agt.bme.hu/gis/qgis/script_runner.pdf)
  * [Python plugin programming](http://www.agt.bme.hu/gis/qgis/plugins_tutorial.pdf)
* [OSGeoLive Presentation](https://live.osgeo.org/en/presentation.html) &mdash; also links to stuff which should be included in the above list.
* [Tutorial QuantumGIS/GRASS - Italian](http://www.ing.unitn.it/~grass/docs/tutorial_qgis/tutorial_qgis.html)
* [QGIS Worksheet Sections](http://changelog.qgis.org/en/qgis/section/list/)
* [Spatio-temporal data handling and visualization in GRASS GIS](https://github.com/ncsu-geoforall-lab/grass-temporal-workshop) &mdash; GitHub Repo
* [Spatio-temporal data handling and visualization in GRASS GIS](https://ncsu-osgeorel.github.io/grass-temporal-workshop/)
* [Scripting GRASS GIS 7 with Python](https://www.youtube.com/watch?v=PX2UpMhp2hc) &mdash; YouTube Video
* [QGIS Training Materials](https://github.com/kartoza/QGISTrainingWorkshop)
* [PyQGIS Developer Cookbook](https://docs.qgis.org/3.4/en/docs/pyqgis_developer_cookbook/index.html)

## Learning GPlates

* [GPlates Tutorials](https://sites.google.com/site/gplatestutorials/)
* [GPlates User Manual](http://www.gplates.org/user-manual/)
* [Standard file formats for GPlates](https://www.earthbyte.org/standard-file-formats-for-gplates/)
* [GPlatesPortal](http://portal.gplates.org/)
* [GPlates versus pyGPlates](https://www.gplates.org/docs/pygplates/pygplates_introduction.html#gplates-versus-pygplates)
