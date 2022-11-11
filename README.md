# mapserver-demo
Demo of QGIS Server + Mapproxy + sphere Map API

* *** For testing only, NOT SAFE for production use *** (folders permission, unnecessary data in document root, etc.)
* see docker-compose.yml for the available services.
* see mapproxy_configuration/mapproxy.yaml for available layers
* see web/index.html for demo layers
* Put .qgs files and other data for QGIS server in the qgis_project/ folder
* NOTE: the permission of mapproxy_configuration/cache_data/ needs to be writable by uid:gid 1000:1000.

# References
* This is derived from https://github.com/kartoza/docker-mapproxy
