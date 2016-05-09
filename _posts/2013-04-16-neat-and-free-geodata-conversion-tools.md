---
title: Neat (and Free) Geodata Conversion Tools
redirect_from:
  - /general/2013/04/06/welcome-young-professionals
tags:
  - tips
---

by Mele Sax-Barnett

### Overview

Lots of great geodata conversion tools are available for free, and many of these are even open source, so you can see how they work and change them to suit your needs. Here are a few to get you started:

### File Bakery

[File Bakery](http://filebakery.com/), created by Max Ogden and Jessica Lord, Code for America alums. This site will convert a zipped shapefile or .mdb into a CSV lickety-split!

### GDB Flee

[GDB Flee](http://gdbflee-mweisman.rhcloud.com/), by Michael Weisman, helps you convert your .gdb databases into a variety of formats, including GeoJSON, KML, Shapefile, PostGIS DB dump, CSV, and more.

### OpenStreetMap converters

* [osm2gis](http://www.osm974.re/osm2gis/): download and convert OSM data into several different formats and a couple of different projections
* [osm2pgsql](http://wiki.openstreetmap.org/wiki/Osm2pgsql): in my opinion, the most robust way to get OSM data into a database (in this case, PostGIS), where you can easily organize and query for exactly what you're looking for.

### Quantum GIS

Finally, don't forget [Quantum GIS](http://www.qgis.org)! You can "Save As..." layers into all kinds of formats and coordinate systems, connect directly to PostGIS databases, create layers from delimited text files, and download OSM data all from inside QGIS. A couple of these functions require adding plugins, but they're easy to find and manage.
