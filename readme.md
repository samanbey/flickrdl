<img align="right" src="icon.png" />

# flickrdl
Flickr geotagged photo metadata downloader plugin for QGIS 3

This plugin lets you to download the metadata of geotagged public photograps in Flickr of a given geographic quadrangle (defined by boundary latitudes/longitudes).
To use the plugin you need to obtain a Flickr API key here:
https://www.flickr.com/services/api/misc.api_keys.html

## Setup
- Download and unzip this package to QGIS 3 plugins folder:
%APPDATA%\QGIS\QGIS3\profiles\default\python\plugins
- (Re-)start QGIS
- Go to Plugin Manager (remember to check "Show also experimental plugins") and enable 'Flickr Metadata Downloader'

## Usage
- (Obtain a Flickr API key)
- (Create a Spatialite database file in QGIS)
- Start the plugin from Web menu. Select the database file, set the API key, change the table name (if you want)
- Set the bounding latitudes/longuitudes of the area to download
- Press "Start"
- The result is a new Spatialite table with point geometries
