geojsontoosm
============

Converts [GeoJSON](http://www.geojson.org/) to [OSM](http://openstreetmap.org) [data](http://wiki.openstreetmap.org/wiki/OSM_XML).

The only difference with https://github.com/tyrasd/geojsontoosm is that this generates positive IDs

Usage
-----

* as a **command line tool**:
  
        $ npm install -g geojsontoosm
        $ geojsontoosm file.geojson > file.osm
  
* as a **nodejs library**:
  
        $ npm install geojsontoosm
  
        var geojsontoosm = require('geojsontoosm');
        geojsontoosm(geojson_data);
