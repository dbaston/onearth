# OnEarth

OnEarth is a software package consisting of image formatting and serving modules which facilitate the deployment of a web service capable of efficiently serving standards-based requests for georeferenced raster imagery at multiple spatial resolutions including, but not limited to, full spatial resolution.  The software was originally developed at the Jet Propulsion Laboratory ([JPL](http://www.jpl.nasa.gov/)) to serve global daily composites of MODIS imagery.  Since then, it has been deployed and repurposed in other installations, including at the Physical Oceanography Distributed Active Archive Center ([PO.DAAC](http://podaac.jpl.nasa.gov/)) in support of the State of the Oceans ([SOTO](https://podaac-tools.jpl.nasa.gov/soto/)) visualization tool, the Lunar Mapping and Modeling Project ([LMMP](https://moontrek.jpl.nasa.gov/)), and [Worldview](https://worldview.earthdata.nasa.gov/).

OnEarth is actively maintained by the NASA Global Imagery Browse Services (GIBS) Project. For more information, visit https://earthdata.nasa.gov/gibs

## Setup

* [Docker Build](docker/README.md)
* [Configuration](doc/configuration.md)
* [Storage](doc/storage.md)
* [Deployment](doc/deployment.md)

## Docker Containers

* [OnEarth](docker/README.md)
* [OnEarth Time Service](docker/date_service/README.md)
* [OnEarth WMS](docker/wms_service/README.md)

## Modules

* [mod_mrf](https://github.com/nasa-gibs/mod_mrf)
* [mod_ahtse_lua](https://github.com/nasa-gibs/mod_ahtse_lua)
* [mod_receive](https://github.com/nasa-gibs/mod_receive)
* [mod_reproject](https://github.com/nasa-gibs/mod_reproject)
* [mod_sfim](https://github.com/nasa-gibs/mod_sfim)
* [mod_twms](https://github.com/nasa-gibs/mod_twms)
* [mod_wmts_wrapper](src/modules/mod_wmts_wrapper/README.md)
* [GetCapabilities Service](src/gc_service/README.md)
* [Time Snapping](src/time_snap/README.md)

## Tools

* [mrfgen](src/mrfgen/README.md)
* [vectorgen](src/vectorgen/README.md)
* [OnEarth Color Maps](src/colormaps/README.md)
* [OnEarth Legend Generator](src/generate_legend/README.md)
* [OnEarth Metrics](src/onearth_logs/README.md)
* [OnEarth Scripts](src/scripts/README.md)
* [OnEarth Empty Tile Generator](src/empty_tile/README.md)

## Other Information

* [OnEarth Demo](src/demo/README.md)
* [Tests](src/test/README.md)
* [Continuous Integration](ci/README.md)
* [Profiling](docker/profiler/README.md)
* [Meta Raster Format](https://github.com/nasa-gibs/mrf/blob/master/README.md)
* [Vector Handling](doc/vector_handling.md)
* [Contributing](CONTRIBUTING.md)

## Contact

Contact us by sending an email to
[support@earthdata.nasa.gov](mailto:support@earthdata.nasa.gov)