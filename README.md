# Urban & Regional Planning Resources [![Awesome](https://awesome.re/badge.svg)](https://github.com/sindresorhus/awesome) <!-- omit in toc -->
[![GitHub stars](https://img.shields.io/github/stars/APA-Technology-Division/planning-technology-resources)](https://github.com/APA-Technology-Division/planning-technology-resources/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/APA-Technology-Division/planning-technology-resources)](https://github.com/APA-Technology-Division/planning-technology-resources)
![GitHub contributors](https://img.shields.io/github/contributors/APA-Technology-Division/planning-technology-resources)
![GitHub last commit](https://img.shields.io/github/last-commit/APA-Technology-Division/planning-technology-resources)
[![GitHub license](https://img.shields.io/github/license/APA-Technology-Division/planning-technology-resources)](https://github.com/APA-Technology-Division/planning-technology-resources/blob/main/LICENSE) 

This repository contains curated list of different urban & regional planning data &amp; technology resources. Those interested in the built environement are invited to review and contribute to this repository.

---
<!--lint disable awesome-toc-->
## Contents

- [Public Data Resources](#public-data-resources)

  - [Built Environment](#built-environment)
  - [Climate](#climate)
  - [Demographic](#demographic)
  - [Education](#education)
  - [Employment](#employment)
  - [Environment and Ecosystem Services](#environment-and-ecosystem-services)
  - [Equity and Environmental Justice](#equity-and-environmental-justice)
  - [Health](#health)
  - [Historic Preservation](#historic-preservation)
  - [OpenStreetMap](#openstreetmap)
  - [Resilience and Natural Hazards](#resilience-and-natural-hazards)
  - [Transportation](#transportation)
- [Vendor Data Resources](#vendor-data-resources)

  - [Demographic](#demographic-1)
  - [Infrastructure](#infrastructure)
  - [Land Use](#land-use)
  - [Resilience and Natural Hazards](#resilience-and-natural-hazards-1)
  - [Urban Observation](#urban-observation)
  - [Travel Behavior](#travel-behavior)
- [Planning Data Specifications](#planning-data-specifications)

  - [Built Environment](#built-environment-1)
  - [Transportation](#transportation-1)
- [Planning Coding Resources](#planning-coding-resources)

  - [Python](#python)
  - [R](#r)
  - [Other](#other)
  - [Web and JS](#web-and-js)
- [Platforms and Software Resources](#platforms-and-software-resources)

  - [Geospatial Data and Visualization](#geospatial-data-and-visualization)
  - [Urban Design Tools and Platforms](#urban-design-tools-and-platforms)
  - [Urban Planning Tools and Platforms](#urban-planning-tools-and-platforms)
  - [Environmental and Climate Planning Tools and Platforms](#environmental-and-climate-planning-tools-and-platforms)
- [Educational and Informational Resources](#educational-and-informational-resources)

  - [AICP Resources](#aicp-resources)
  - [Literature Resources](#literature-resources)
  - [General Planning Information and News](#general-planning-information-and-news)
- [Other Resources](#other-resources)

  - [Other Technology Resource Aggregators](#other-technology-resource-aggregators)
- [Contributing](#contributing)

  - [Form Based Contributions](#form-based-contributions)
  - [GitHub Contributions](#github-contributions)
- [License and Citation](#license-and-citation)

---

## Public Data Resources
Data resources that are publicly available for use. Licenses may apply. 

Open Data Sites and national scale datasets should be near the top of each section.

---
### Built Environment

- [Smart Location Database](https://www.epa.gov/smartgrowth/smart-location-mapping#SLD) -  The Smart Location Database is a nationwide geographic data resource for measuring location efficiency. It includes more than 90 attributes summarizing characteristics such as housing density, diversity of land use, neighborhood design, destination accessibility, transit service, employment, and demographics. Most attributes are available for every census block group in the United States. 
- [USBuildingFootprints](https://github.com/microsoft/USBuildingFootprints) -  Microsoft Maps is releasing country wide open building footprints datasets in United States. This dataset contains ~130,000,000 computer generated building footprints derived using our computer vision algorithms on satellite imagery. This data is freely available for download and use. Additional Information:[Article](https://www.nytimes.com/interactive/2018/10/12/us/map-of-every-building-in-the-united-states.html).

### Climate
- [NCCS Data Services](https://www.nccs.nasa.gov/services/climate-data-services) - The NASA Center for Climate Simulation houses curated data collections that include atmosphere, ocean, land, and flood data, both current and historical, as well as operational Global Modeling and Assimilation Office (GMAO) weather analysis data and forecasts that are updated four times daily.
- [NCDC Storm Data](https://www.ncei.noaa.gov/access/metadata/landing-page/bin/iso?id=gov.noaa.ncdc:C00510) - United States storm data provided by the National Weather Service (NWS) and contain statistics on personal injuries and damage estimates.
- [NOAA Severe Weather Inventory](https://www.ncdc.noaa.gov/severe-weather/severe-weather-data-inventory) - The Severe Weather Data Inventory (SWDI) is an integrated database of severe weather records for the United States. The formats currently supported are Shapefile (for GIS), KMZ (for Google Earth), CSV (comma-separated), and XML.
- [NREL Solar Radiation](https://nsrdb.nrel.gov/) - The National Solar Radiation Database (NSRDB) is a serially complete collection of hourly and half-hourly values of meteorological data and the three most common measurements of solar radiation: global horizontal, direct normal and diffuse horizontal irradiance.
- [Temperature Severity Indicators](https://hudgis-hud.opendata.arcgis.com/datasets/HUD::temperature-severity-indicators/about) - The Temperature Severity Indicator data distills observational information of prolonged temperature events to inform housing and community development policy and decision making provided by US HUD. 
- [Urban Heat Disparities Project](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/1F72FB) - Census Tract level temperature data derived from a [paper](https://agupubs.onlinelibrary.wiley.com/doi/10.1029/2021EF002016) use remotely sensed land surface temperature measurements to explore the distribution of the United States urban heating burden by demographic group.
- [MACA](https://climate.northwestknowledge.net/MACA/) - The MACA method is a statistical downscaling method for removing biases from global climate model outputs. 
- [IPCC Atlas](https://interactive-atlas.ipcc.ch/) - A novel tools & data for flexible spatial and temporal analyses of much of the observed and projected climate change information underpinning the Working Group I contribution to the Sixth Assessment Report, including regional synthesis for Climatic Impact-Drivers (CIDs).

### Demographic

- [American Community Survey (ACS)](https://www.census.gov/programs-surveys/acs) - The American Community Survey (ACS) helps local officials, community leaders, and businesses understand the changes taking place in their communities. It is the premier source for detailed population and housing information for the United States. Additional Information: [Geodata Download](https://www.census.gov/geographies/mapping-files/time-series/geo/tiger-data.html)/[Table Data Access](https://data.census.gov/cedsci/)
- [Census Reporter](https://censusreporter.org/) - Census Reporter is an open-source website that makes it easy to explore and report census data. Census Reporter automatically provides descriptive statistics, downloadable tabular data, and interactive visualizations of American Community Survey (ACS) data for the United States. Visualizations can be [embedded as HTML](https://censusreporter.org/examples/embed-charts/) iframes. Additional Information:License: MIT License Geographic Coverage: Contains geographies matching the coverage and scale of the [ACS 2019 1-year and 5-year estimates.](https://web.archive.org/web/20210519000200/https://www.census.gov/programs-surveys/acs/geography-acs/areas-published.html) Provider: [About Page.](https://censusreporter.org/about/) Additional Links: [GitHub Repository.](https://github.com/censusreporter/censusreporter)
- [IPUMS National Historic GIS](https://www.nhgis.org/) - The National Historical Geographic Information System (NHGIS) provides easy access to summary tables and time series of population, housing, agriculture, and economic data, along with GIS-compatible boundary files, for years from 1790 through the present and for all levels of U.S. census geography, including states, counties, tracts, and blocks.

### Education 

- [National Center for Educational Statistics](https://nces.ed.gov/datalab/index.aspx) - The National Center for Education Statistics (NCES) is the primary federal entity for collecting and analyzing data related to education. Their data lab provides access to other 30+ education datasets and provides quick reporting and charting functionality for users. 
   
### Employment

- [Longitudinal Employer-Household Dynamics (LEHD)](https://lehd.ces.census.gov/) -  The LEHD program combines these administrative data, additional administrative data and data from censuses and surveys. From these data, the program creates statistics on employment, earnings, and job flows at detailed levels of geography and industry and for different demographic groups. Additional Information:[On The Map Download Page](https://onthemap.ces.census.gov/).
- [Bureau of Labor Statistics](https://www.bls.gov/) - The Bureau of Labor Statistics measures and provides access to data on labor market activity, working conditions, price changes, and productivity in the U.S. economy to support public and private decision making.

### Environment and Ecosystem Services

- [CropScape](https://nassgeodata.gmu.edu/CropScape/) - CropScape displays data from the USDA Cropland Data Layer (CDL), an annual, remote-sensing snapshot of crop cover during the main growing season across the contiguous United States.
- [EnviroAtlas](https://www.epa.gov/enviroatlas) - EnviroAtlas is a collection of interactive tools and resources that allows users to explore the many benefits people receive from nature, often referred to as ecosystem services within the United States.
- [National Hydrography](https://www.usgs.gov/core-science-systems/ngp/national-hydrography/access-national-hydrography-products) - The NHDPlus High Resolution (NHDPlus HR), National Hydrography Dataset (NHD), and Watershed Boundary Dataset (WBD) are available for download and as map services. These datasets can help inform environmental planning and storm water management efforts in the US. 
- [NLCD](https://www.usgs.gov/centers/eros/science/national-land-cover-database) - The National Land Cover Database is generated in cooperation with the Multi-Resolution Land Characteristics Consortium (MRLC), a partnership of Federal agencies working together to produce current, nationally consistent, land cover products for all 50 US states and Puerto Rico. 
- [National Wetland Inventory](https://www.fws.gov/wetlands/index.html) -  The US Fish & Wildlife Service (FWS) National Wetlands Inventory (NWI) is a publicly available resource that provides detailed information on the abundance, characteristics, and distribution of US wetlands.
- [Park Score](https://www.tpl.org/parkscore) - The Trust for Public Land curates a comprehensive evaluation of park access and quality in the 100 largest U.S. cities. 
- [Tree Canopy](https://data.fs.usda.gov/geodata/rastergateway/treecanopycover/) - The U.S. Forest Service (USFS) Geospatial Technology and Applications Center (GTAC) builds and maintains tree canopy cover (TCC) datasets.

### Equity and Environmental Justice

- [CDC Social Vulnerability Index](https://www.atsdr.cdc.gov/placeandhealth/svi/index.html) - CDC Social Vulnerability Index (CDC SVI) uses 15 U.S. census variables to help local officials identify communities that may need support before, during, or after disasters based on their level of social vulnerability. Additional Information: [Download](https://www.atsdr.cdc.gov/placeandhealth/svi/data_documentation_download.html).
- [EJ Screen](https://www.epa.gov/ejscreen/understanding-ejscreen-results) - EJSCREEN uses maps and reports to present three kinds of information: Environmental indicators, demographic indicators and EJ Indexes. Additional Information:[Download](https://www.epa.gov/ejscreen/download-ejscreen-data).
- [H+T Index](https://htaindex.cnt.org/) - The Housing and Transportation (H+T®) Affordability Index provides a comprehensive view of affordability that includes both the cost of housing and the cost of transportation at the neighborhood level. Provided by the Center for Neighborhood Technology.
- [Location Affordability Index](https://www.hudexchange.info/programs/location-affordability-index/) - The Location Affordability Index (LAI) works to close this gap by providing estimates of household housing and transportation costs at the neighborhood level along with constituent data on the built environment and demographics.  
- [Opportunity Atlas](https://www.opportunityatlas.org/) - These [datasets provided by Opportunity Insights](https://opportunityinsights.org/data/?geographic_level=0&topic=0&paper_id=1652#resource-listing) allow you to analyze social mobility and a variety of other outcomes from life expectancy to patent rates by neighborhood, college, parental income level, and racial background. 

### Health

- [County Health Rankings](https://www.countyhealthrankings.org/) - The annual Rankings provide a revealing snapshot of how health is influenced by where we live, learn, work, and play.
- [HealthData.gov](https://healthdata.gov/) - This site is dedicated to making high value health data in the United States more accessible to entrepreneurs, researchers, and policy makers in the hopes of better health outcomes for all.  

### Historic Preservation

- [National Register of Historic Places](https://www.nps.gov/subjects/nationalregister/data-downloads.htm) - The National Register of Historic Places is the official list of the Nation's historic places worthy of preservation.
- [UNESCO World Heritage Sites](https://whc.unesco.org/en/list/) - A World Heritage Site is a site on a list of properties maintained by the World Heritage Committee of UNESCO and called the World Heritage List "which it considers as having outstanding universal value".

### OpenStreetMap

- [OpenStreetMap](https://www.openstreetmap.org/) - OpenStreetMap is the free wiki world map. This colloborative project is one of the largest databases of volunteered geographic information in the world. Its contents include points of interest, routable networks, and other geodata. 
- [BBBike](https://download.bbbike.org/osm/bbbike/) - Provides shapefiles and raw OSM format for cities around the world, extracted weekly. This is useful if you are looking for data extracts for a single city.
- [Geofabrik](http://download.geofabrik.de/) - OpenStreetMap extracts prepared in either PBF or shapefile format for download daily.  
- [MetroExtracts](https://www.interline.io/osm/extracts/) - Each day, OSM Extracts by Interline mirrors the entire OpenStreetMap planet and creates city and region sized extracts ready for download into formats ready for GIS. 
- [Overpass Turbo](https://overpass-turbo.eu/) -  Overpass Turbo is a web-based data mining tool for OpenStreetMap. It runs any kind of Overpass API query, shows the results on an interactive map, and allows users to export query data in the form of GeoJSON files (which may be converted to Shapefiles). It also provides helpful support for new users in the form of the "Wizard" tool. Using Overpass Turbo, you can query virtually any location globally using dedicated tags in Open Street Map. 
 
 
### Resilience and Natural Hazards

- [Sea Level Rise Viewer](https://coast.noaa.gov/slr/) - NOAA provided map viewer is to provide federal, state, and local coastal resource managers and planners with a preliminary look at sea level rise and coastal flooding impacts.
- [Earth Quake Data](https://www.ngdc.noaa.gov/hazard/earthqk.shtml) - NOAA provided data includes a global record of significant earth quakes going back to 2150 BC to present with geographic information.
- [National Risk Index](https://www.fema.gov/flood-maps/products-tools/national-risk-index) - The National Risk Index is an online mapping application from FEMA that identifies communities most at risk to 18 natural hazards.
- [HIFLD](https://hifld-geoplatform.opendata.arcgis.com/) - This site provides National foundation-level geospatial data within the open public domain that can be useful to support community preparedness, resiliency, research, and more. 


### Transportation

- [BTS Open Data Site](https://data-usdot.opendata.arcgis.com/) - On the BTS Open Data site, browse geospatial data that is part of the BTS National Transportation Atlas Database (NTAD) product. NTAD is a set of nationwide (United States) geographic databases of public spatial information for transportation facilities and networks; flows of people, goods, vehicles, and craft over the transportation networks; and social, economic, and environmental conditions that affect or are affected by the transportation networks.
- [CTPP](https://ctpp.transportation.org/) - The CTPP Program procures tabulations of American Community Survey (ACS) 5-year (and historical Census decennial) data. The chief differences between ACS data and CTPP data are FLOWS from home to work and WORKPLACE BASED data at small Geographies.
- [HPMS](https://www.fhwa.dot.gov/policyinformation/hpms.cfm0) - The HPMS is a national level highway information system that includes data on the extent, condition, performance, use and operating characteristics of the nation's highways.
- [Transitland](https://transit.land) - Transitland is an open data platform that collects GTFS, GTFS Realtime, and other open data feeds from over 2,500 transit operators in over 55 countries. Additional Information: [Interline](https://www.interline.io/),[GitHub](https://github.com/transitland).
- [National Noise Map](https://www.bts.gov/geospatial/national-transportation-noise-map) - Data within the National Transportation Noise Map represent potential noise levels across the nation for an average annual day for the specified year. 
- [National Transit Database](https://www.transit.dot.gov/ntd/ntd-data) - Repository of operations, financial, and asset data that US transit agencies are required to report to the Federal Transit Administration. 
- [Global Urban Street Networks](https://geoffboeing.com/publications/street-network-models-indicators-world/) - Ready‐to‐use global street network models and calculated indicators in a GIS format. Additional Information:[Geopackage Download](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/E5TPDQ)
- [Rapid Transit Database](https://www.itdp.org/rapid-transit-database/) - Collection of all rapid transit corridors worldwide, including bus rapid transit, light rail, and subway, published by the Institute for Transportation & Development Policy. 
- [Transit Equity Dashboards](https://dashboard.transitcenter.org/) - Equity analysis of transit systems in seven (and counting) US cities, published by TransitCenter.

## Vendor Data Resources
Vendors that can provide purchased or licensed data for a variety of uses. 

---

### Demographic

- [Esri Tapestry Segmentation](https://www.esri.com/en-us/arcgis/products/tapestry-segmentation/zip-lookup) - Provides concise information on the demographic, economic, education and consumer characteristics of populations based on ZIP code.
- [Data Axle](https://www.data-axle.com/) - Data Axle offers some of the most comprehensive and accurate business and consumer databases, boasting almost 400 distinct attributes across businesses and consumers in the United States and Canada.  

### Infrastructure

- [Mapillary](https://www.mapillary.com/) - Access street-level imagery and AI-derived map data from all over the world. Fill in the gaps by requesting new coverage or capturing your own with an easy to use mobile app.
- [Ecopia](https://www.ecopiatech.com/) - Ecopia AI leverages AI to convert high resolution images of the earth into HD Vector Maps and to digitize infrastructure assets in a geospatial format. 

### Land Use

- [CoreLogic](https://www.corelogic.com/) - Provides high quality parcel data, providing instant access to detailed property characteristics, sales records, valuation and digital copies of current county assessor documents.
- [CoStar](https://www.costar.com/) - A commercial real estate information and analytics provider serving the UK, US, and Canada. 
- [EarthDefine](http://www.earthdefine.com/) - EarthDefine is using AI to transform earth sensor data into consumable geospatial information products including high resolution land cover classifications and building footprints. 

### Resilience and Natural Hazards

- [FloodFactor](https://firststreet.org/flood-factor/) - Provided by the First Street Foundation, this tool makes it easy to determine if a property has flooded from major events in the past, is currently at risk, and how that risk changes over time. It can also help estimate damage costs associated with flooding.

### Urban Observation

- [Numina](https://numina.co/) - Utilizes edge computing devices that measures all kinds of curb-level activity. Anonymously and in aggregate, Numina delivers the volume counts, paths, and traffic behaviors of travelers and objects in streets.
- [Transoft](https://safety.transoftsolutions.com/) - Transfoft ITS Safety solutions utilize computer vision to identify 'near-miss' behavior on streets. This technology was featured Planning Magazine in the [Art of Learning by Example](https://www.planning.org/planning/2020/oct/art-of-learning-by-example/).
- [Automotus](https://www.automotus.co/) - Computer vision based platform that helps cities, airports, fleets, and businesses monitor the curb in real time. Enables curbside management policies that increase revenue while making streets less congested, more sustainable, and more equitable. 
- [Vade](https://www.vadepark.com/) - Using custom IoT cameras and computer vision to bring real time parking availability easily queriable via web-based API's. 

### Travel Behavior

- [Replica](https://replicahq.com/platform) -  Replica is a data platform providing rich origin-destination, spend, and scenario impact analysis based on an activity based modeling process.
- [SafeGraph](https://www.safegraph.com/) -  Points of interest (POI) provider using mobile trace data to provide visitor insights data for commercial places in the United States.
- [WeJo](https://www.wejo.com/) - Wejo has made it simple and secure to share and access connected car data, on a global scale. This data can be used for everything from origin-destination analysis, safety & speed studies, and more. 
- [StreetLight Data](https://www.streetlightdata.com/) - Provides data using smartphones as sensors to measure vehicles, bikes, and pedestrians across North America. Carry out your mission on time and under budget, with 24/7 access to counts, O-D, and other metrics you need.
- [Strava](https://developers.strava.com/) - API for a popular tracking app for runners and cyclists. Data can be used to understand active transportation usage and patterns.

## Planning Data Specifications
A collection of urban planning related data specifications and standards for use as part of programs & projects.

---

### Built Environment

- [DTDL](https://github.com/Azure/opendigitaltwins-building) - The Digital Twins Definition Language is the language by which developers can define the language of the entities they expect to use in their topologies. 
- [BLDS](https://github.com/open-data-standards/permitdata.org/wiki/Core-Permits-Dataset-Requirements) - The BLDS data standard is a collaborative effort by civic technology companies, governments and other interested partiesto create a shared data specification for building and construction permit data.

### Transportation

- [SharedStreets](https://www.sharedstreets.io) - SharedStreets Referencing System is a global, non-proprietary linear referencing system for describing streets maintained by SharedStreets. Additional Information: [GitHub](https://github.com/sharedstreets/sharedstreets-ref-system)
- [CurbLR](https://www.curblr.org) -  An open data specification for curb regulations maintained by SharedStreets. Additional Information: [GitHub](https://www.github.com/sharedstreets/curblr), Demo: interactive [map and example feed](https://demo.curblr.org/), Blog post: [Why CurbLR was built](https://medium.com/sharedstreets/crossroads-for-the-curb-be3137154148).    
- [GTFS](https://developers.google.com/transit/gtfs) - The General Transit Feed Specification is a popular standard for describing transit systems.
- [shared-row](https://github.com/d-wasserman/shared-row) - A data specification for representing street right of ways. 
- [GBFS](https://github.com/NABSA/gbfs) - The General Bikeshare Feed Specification is a standardized data feed for shared mobility system availability.
- [MDS](https://github.com/openmobilityfoundation/mobility-data-specification) - The Mobility Data Specification is a data standard to enable communication between mobility companies and local governments.
- [MTLFS](https://github.com/vta/Managed-and-Tolled-Lanes-Feed-Specification) - The Managed and Tolled Lanes Feed Specification is intended to be used by the managed lanes and toll industry for the standardization and sharing of dynamic toll rates, and any managed lane purpose including but not limited to, ramp metering, bus only lanes, express lanes, especially if the resources are being priced dynamically.
- [GMNS](https://github.com/zephyr-data-specs/GMNS) - The General Modeling Network Specification defines a common human and machine readable format for sharing routable road network files.

## Planning Coding Resources
This is a curated list of Python, R, or other open-source libraries or programming tools can be useful for urban planning applications. 

---

### Python
Python Libraries & Related Resources.

- [Pandas](https://pandas.pydata.org/) - Flexible and powerful data analysis / manipulation library for Python, providing labeled data structures similar to R data.frame objects, statistical functions, and much more.
- [Arcpy](https://pro.arcgis.com/en/pro-app/latest/arcpy/get-started/what-is-arcpy-.htm) - ArcPy is a Python site package that provides a useful and productive way to perform geographic data analysis, data conversion, data management, and map automation with Python.
- [ArcGIS Python API](https://developers.arcgis.com/python/api-reference/) - The ArcGIS API for Python is a powerful, modern and easy to use Pythonic library to perform GIS visualization and analysis, spatial data management and GIS system administration tasks that can run both interactively, and using scripts. This library enables easy use of pandas within the ArcGIS platform. 
- [Geopandas](https://geopandas.org/) - GeoPandas is an open source project to make working with geospatial data in python easier. GeoPandas extends the datatypes used by pandas to allow spatial operations on geometric types.
- [Partridge](https://partridge.readthedocs.io/en/stable/readme.html) - Partridge is a Python 3.6+ library for working with GTFS feeds using pandas DataFrames.
- [Pandana](https://udst.github.io/pandana/) - Urban network analysis library intended to help planners compute quick accessibility metrics or shortest paths. Additional Information: License: AGPL-3.0 License: Provider: UrbanSim Inc. (UDST).
- [UrbanSim](https://github.com/udst/urbansim) - UrbanSim is a platform for building statistical models of cities and regions. These models help forecast long-range patterns in real estate development, demographics, and related outcomes, under various policy scenarios. Information: License: BSD License: Provider: UrbanSim Inc. (UDST).
- [Geosnap](https://github.com/spatialucr/geosnap) - Geospatial & temporal neighborhood analysis using US Census Data.
- [OSMnx](https://github.com/gboeing/osmnx) - Python for street networks. Retrieve, model, analyze, and visualize street networks and other spatial data from OpenStreetMap.
- [Pybikes](https://github.com/eskerda/pybikes) - Pybikes provides a set of tools to scrape bike sharing data from different websites and APIs, thus providing a coherent and generalized set of classes and methods to access this sort of information.


### R
R Packages & Related Resources.

- [R Shiny](https://shiny.rstudio.com/) - Create dynamic, web-friendly visualizations of data using R. Additional Information: [Shiny Tutorial](https://shiny.rstudio.com/tutorial/).
- [simplefeatures(sf)](https://cran.r-project.org/web/packages/sf/index.html) - Support for simple features, a standardized way to encode spatial vector data in R. 
- [ggplot2](https://ggplot2.tidyverse.org/) - Resource for plotting a wide range of data (useful for visualizing survey data). Additional Information: GNU GENERAL PUBLIC LICENSE.
- [tidytext](https://cran.r-project.org/web/packages/tidytext/vignettes/tidytext.html) - Go-to library for text mining--often used in tandem with ggplot or other text mining libraries.
- [leafgl](https://github.com/r-spatial/leafgl) - R package for fast web-gl rendering for leaflet maps.

### Other
Other coding libraries & resources.

- [civic-tech-patterns](https://github.com/codeforamerica/civic-tech-patterns) - Common patterns and anti-patterns for civic tech and civic applications. Additional Information: Provided by Code for America.

### Web and JS
Front-end web related packages and resources.

- [Bootstrap](https://getbootstrap.com/) - Widely-used, well documented library for quick design and customization of websites. Additional Information: [Documentation](https://getbootstrap.com/docs/5.0/getting-started/introduction/).
- [Chart.js](https://www.chartjs.org/) - Create simple (or advanced) visualizations of data for web and mobile. Additional Information: [GitHub](https://github.com/chartjs/Chart.js).
- [Leaflet](https://leafletjs.com/) - Open-source JavaScript library for mobile-friendly interactive maps. Plugins available to extend functionality (e.g., storymaps, heatmaps, animation). Additional Information: [Quickstart Guide](https://leafletjs.com/examples/quick-start/).
- [Turf.js](https://turfjs.org/) - Advanced geospatial analysis for browsers and Node.js. Additional Information: [GitHub](https://github.com/Turfjs/turf).
- [GTFS-Js](https://github.com/WSDOT-GIS/GTFS-JS) - JavaScript library for working with GTFS data. Additional Information: Unlicense: WSDOT.

## Platforms and Software Resources
Software and platforms for planners.

---

### Geospatial Data and Visualization


- [ArcGIS](https://www.esri.com/en-us/arcgis/about-arcgis/overview) - This platform is a geographic information system (GIS) for working with maps and geographic information maintained by the Environmental Systems Research Institute (Esri).
- [QGIS](https://qgis.org/en/site/) - This open source GIS suite allows users to create, edit, visualise, analyse and publish geospatial information on Windows, Mac, Linux, BSD and mobile devices.
- [CARTO](https://carto.com/) - CARTO is a world leading Location Intelligence platform, enabling organizations to host & use spatial data and enable analysis for more efficient delivery routes, better behavioural marketing, strategic store placements, and much more.
- [kepler.gl](https://kepler.gl/) - Kepler is a data agnostic, WebGL empowered, high-performance web application for geospatial analytic visualizations. Additional Information: [API Reference](https://docs.kepler.gl/docs/api-reference).
- [flowmap-blue](https://flowmap.blue) - Create geographic flow maps representing your data published in Google Sheets. Visualize numbers of movements between locations (origin-destination data).
- [ScapeToad](http://scapetoad.choros.place/index.php) - ScapeToad is a cross-platform, open-source application designed to adjust the size of polygons based on some attribute. Use a shapefile as input and output to generate cartograms, geometries whose sizes are distorted based on data. 
- [Omnisci](https://www.omnisci.com/) - Geotemporal enabled high performance database capable of doing GPU accelerated queries. 

### Urban Design Tools and Platforms

- [CityEngine](https://www.esri.com/en-us/arcgis/products/arcgis-cityengine/overview) - CityEngine is advanced 3D modeling software for creating huge, interactive and immersive urban environments in less time than traditional modeling techniques. The cities you create using CityEngine can be based on real-world GIS data and the procedural rules that can help quickly create [streets](https://github.com/d-wasserman/Complete_Street_Rule) & [buildings](https://www.arcgis.com/home/group.html?id=01695af30a384c1e823fa4d72497309d#overview).
- [SketchUp](https://www.sketchup.com/) - Easy to use interactive 3D modeling software for planning and design applications. Supported by a rich asset library for creating neighborhood designs. 
- [Rhino](https://www.rhino3d.com/) - This is a commercial 3D computer graphics and computer-aided design application software. Rhino has had multiple plug-ins built on top of it including Grasshopper and the Urban Network Analysis toolbox to enable complex modeling and analysis. 
- [Adobe Creative Suite](https://www.adobe.com/creativecloud.html) - Adobe's collection of 20+ desktop and mobile apps and services for photography, design, video, web, UX, and more. Popular products include Photoshop, Adobe Illustrator, and others. 
- [GIMP](https://www.gimp.org/) - GIMP is an open cross-platform image editor available for GNU/Linux, macOS, Windows and more operating systems.
- [Inkscape](https://inkscape.org/) - Inkscape is vector-based, open graphic manipulation tool often used as a counterpart to GIMP.
- [TestFit](https://testfit.io/) - TestFit features algorithms and co-creation tools help developers, architects, urban planners and more to solve hotel, parking or multifamily building site plans in seconds.
- [Delve](https://www.sidewalklabs.com/products/delve) - Delve uses generative design and AI to reveal the very best options for your project priorities and site design metrics. 

### Urban Planning Tools and Platforms
- [ArcGIS Urban](https://www.esri.com/en-us/arcgis/products/arcgis-urban/overview) - ArcGIS Urban enables planners and design professionals to publish living plans and collaborate across teams with a web-based 3D application that supports scenario planning and impact assessment. 
- [UrbanFootPrint](https://urbanfootprint.com/) - Web-based planning tool serving curated urban, environmental, and economic data to urban practitioners and equipping them with the analytic capabilities to plan and improve communities faster, better, and at lower cost.
- [Remix](https://www.remix.com/) - A platform to empower cities to plan the best possible transportation system — from public transit to safer streets to ever-increasing new modes of mobility. Remix provides tools to edit & test GTFS, generate multimodal streets, and explore relevant data.
- [Streetmix](https://streetmix.net/) - A collaborative civic engagement platform for urban design. Design, remix, and share your neighborhood street with Streetmix.
- [Space Syntax](https://www.spacesyntax.net/software/) - Spatial & Network Analysis software is available to professional practitioners and academic researchers for commercial and non-commercial use. 
- [A/B Street](https://www.abstreet.org) - Edit streets and intersections, explore the effects through traffic simulation on all modes, and use the resulting visualizations to communicate a proposal. Apache licensed, runs anywhere with OpenStreetMap, and works on the web or as an offline download.
- [UrbanCanvas](https://urbansim.com/urbancanvas) - UrbanCanvas Modeler is a web-based platform designed for planners and modelers to generate long-range, small area socioeconomic forecasts using [UrbanSim](https://github.com/UDST/urbansim) to inform Regional Transportation Plans. 

### Environmental and Climate Planning Tools and Platforms

- [iTree](https://www.itreetools.org/) - Quantifies the benefits and values of trees around the world. Is based on peer-reviewed, USDA Forest Service Research.
- [HAZUS](https://www.fema.gov/flood-maps/products-tools/hazus) - FEMA's Hazus Program provides standardized tools and data for estimating risk from earthquakes, floods, tsunamis, and hurricanes. Risk assessment resources and tools from the Hazus program are always freely available and transparently developed. 
- [Temperate](https://icleiusa.org/temperate-adaptation-planner/) - This user-friendly tool was developed by Azavea in partnership with ICLEI USA, with the primary purpose of facilitating a data-informed adaptation planning process in small-to-midsize communities with little to no devoted resources to plan for climate change impacts. 

## Educational and Informational Resources
Collections of planning related literature, information aggregators, or similar resources.

---


### AICP Resources
Resources pertaining to AICP certification test preparation, continuing education, and other resources.

- [AICP Get Certified! Webpage](https://www.planning.org/certification/) - The American Institute of Certified Planners's (AICP) offical resource repository that provides details on eligibility, registration, and preparation. Important dates for upcoming AICP "Certification Cycles" are also listed.
- [AICP Exam Prep. Webpage](https://www.planning.org/certification/register/#examprep/) - Details the AICP's "Five-Step Approach" for exam preparation and lists resources/materials to help you succeed on the AICP exam.
- [APA Knowledge Base](https://www.planning.org/knowledgebase/) - APA's Research KnowledgeBase connects APA members to curated collections of topically related resources — including plans, regulations, model codes, guides, articles, reports, and multimedia files. Each collection provides commentary and thematic groupings of resource records with bibliographic information, short descriptions, and links to the resources themselves. 
- [PlanningPrep](https://www.planningprep.com/) - A free web-based study resource to help planners prepare for the American Institute of Certified Planners' certification exam. As of summer 2021, the site contains 1668 practice questions and 12 practice exams.


### Literature Resources
Resources linking to peer-reviewed journals or federal research aggregators of interest. These are not specific papers, but their curators. 
- [NCHRP](http://www.trb.org/NCHRP/NCHRP.aspx) - The National Cooperative Highway Research Program is developed on the basis of research needs identified by chief administrators and other staff of the highway and transportation departments, by committees of AASHTO, and by FHWA. Topics of the highest merit are selected by the AASHTO Special Committee on Research and Innovation (R&I), and each year R&I's recommendations are proposed to the AASHTO Board of Directors, the National Academies, and FHWA.
- [TCRP](http://www.trb.org/TCRP/TCRP.aspx) - Sponsored by the Federal Transit Administration, the Transit Cooperative Research Program (TCRP) serves as one of the principal means by which the public transportation industry can develop innovative near-term solutions to meet demands placed on it. The TCRP has an established reputation for providing useful reports and other tools to help public transportation practitioners solve problems and inform decision makers.
- [Planning Advisory Service (PAS)](https://www.planning.org/pas/) - The Planning Advisory Service (PAS) is the American Planning Association's (APA) flagship research brand which is responsible for the following publications: [PAS Reports](https://www.planning.org/pas/reports) (quarterly), [*PAS Memo*](https://www.planning.org/pas/memo) (bimonthly), and [*PAS QuickNotes*](https://www.planning.org/pas/quicknotes) (bimonthly). Current publications and archives of previous issues are available for free download for APA members.
- [Policy Guides](https://www.planning.org/policy/guides/) - Policy Guides represent APA's official position on critical planning issues and arm planners with the tools to advocate for policies that create great communities for all.

### General Planning Information and News

- [Planopedia](https://www.planetizen.com/planopedia) - Organized by the Planning News aggregator [Planetizen](https://www.planetizen.com/) this mini-planning encyclopedia explores various urban planning concepts and terms.
- [ULI](https://uli.org/) - ULI is the oldest and largest network of cross-disciplinary real estate and land use experts in the world.

## Other Resources
Other types of planning data & technology resources. 

---

### Other Technology Resource Aggregators

These are other aggregators that bring together different planning related tools, software, data, and related resources. They are a good source of inspiration to contribute to this repo for example, but we don't need to duplicate efforts. 

- [awesome-transit](https://github.com/CUTR-at-USF/awesome-transit) - A collection of transit data tools and resources.
- [micromobility-tools-and-resources](https://github.com/NABSA/micromobility-tools-and-resources) - A collection of micromobility tools and data resources.
- [awesome-sustainable-technology](https://github.com/protontypes/open-sustainable-technology) - A curated list of open technology projects to sustain a stable climate, energy supply, and vital natural resources.
- [awesome-gis](https://github.com/sshuair/awesome-gis) - Awesome GIS is a collection of geospatial related sources, including cartographic tools, geoanalysis tools, developer tools, data, conference & communities, news, massive open online course, some amazing map sites, and more.
- [awesome-agriculture](https://github.com/brycejohnston/awesome-agriculture) - Open source technology for agriculture, farming, and gardening.
- [awesome-geojson](https://github.com/tmcw/awesome-geojson) - GeoJSON utilities that will make your life easier.
- [Urban Computing Foundation](https://github.com/ucfoundation) - Accelerating open source and community development that improves mobility, safety, infrastructure, traffic, and energy consumption in connected cities. Additional Information: [Landscape](https://landscape.uc.foundation/). 
- [Data.Gov](https://www.data.gov/) - United States federal repository of data, tools, and resources to conduct research, develop web and mobile applications, design data visualizations, and more.
- [Harvard Dataverse](https://dataverse.harvard.edu/) - Harvard Dataverse is a repository for research data. It contains a wide variety of datasets spanning the sciences, many with public domain dedications. 

---

## Contributing

### Form Based Contributions
If you don't have a GitHub, but have a resources that falls into the categories below you would like to contribute try putting the information in this Google Sheet here. We will look at incorporating it into the repository pending review. 
https://docs.google.com/forms/d/e/1FAIpQLSfGp_XC5V-uIzafsVBhR4xKX9YhgNOz22w84Sg0zo0ONDdV4w/viewform?usp=sf_link

### GitHub Contributions
We are actively looking for contributions from those interested in urban planning and technology. To find out more, visit the [Contribution](https://github.com/APA-Technology-Division/planning-technology-resources/blob/main/CONTRIBUTING.md) page to see our recommended format. For large contributions, file an issue first. The advantage of contributing to the repo in this manner is that your addition to this shared resource will be recorded. 

## License and Citation
Similar to other [resources aggregators](https://github.com/NABSA/micromobility-tools-and-resources/blob/master/README.md), this repository is released into CC 1.0. We do not require citation, but in order to generate more contributions for and understanding of this resource we do appreciate sharing this repository or citing it where appropriate. 


If you do cite this repository you can as: 

planning-technology-resources. (2020) APA Technology Division. Taken from: from https://github.com/APA-Technology-Division
