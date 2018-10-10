# terria-map-examples
JSON configuration files for TerriaMaps

View raw content, copy path, append to:\
https://viewer.nationalmap.gov/advanced/terriajs-usgs \
use '#' at end of map url

Using The National Map viewer:\
https://viewer.nationalmap.gov/advanced/terriajs-usgs#https://raw.githubusercontent.com/ethoms-usgs/terria-map-examples/master/AKGeology1.json

Cleaning the hosted data catalog first using 'clean'\
https://viewer.nationalmap.gov/advanced/terriajs-usgs/#clean&https://raw.githubusercontent.com/ethoms-usgs/terria-map-examples/master/AKGeology1.json

Load Catalog group\
https://viewer.nationalmap.gov/advanced/terriajs-usgs/#clean&https://raw.githubusercontent.com/ethoms-usgs/terria-map-examples/master/ASC_csw.json

Load Catalog group without clean, keep TNM catalog\
ASC Data Release backups with include CSV, KML, WMS, GeoJSON, and ESRI MapServer set to true
https://viewer.nationalmap.gov/advanced/terriajs-usgs/#https://raw.githubusercontent.com/ethoms-usgs/terria-map-examples/master/ASC_csw.json

ASC Data Release backups with no service type filter, eg. all records\
https://viewer.nationalmap.gov/advanced/terriajs-usgs/#https://raw.githubusercontent.com/ethoms-usgs/terria-map-examples/master/ASC_csw_notypefilter.json

Load Catalog group: USGS Data Release Products on ScienceBase searching for AnyText=Alaska\
https://viewer.nationalmap.gov/advanced/terriajs-usgs/#clean&https://raw.githubusercontent.com/ethoms-usgs/terria-map-examples/master/sb_datarelease_AK.json

ScienceBase data release products AnyText=Alaska Science Center\
https://viewer.nationalmap.gov/advanced/terriajs-usgs/#clean&https://raw.githubusercontent.com/ethoms-usgs/terria-map-examples/master/sb_datarelease_ASC.json

ScienceBase data release products AnyText=Alaska Science Center and sb:collection=OGC-WFS\
trying to get results of:\
https://www.sciencebase.gov/catalog/item/5474ec49e4b04d7459a7eab2/csw?service=CSW&version=2.0.2&request=getRecords&CQL_TEXT&constraint=AnyText=alaska&sb:servicetype=OGC-WFS \
https://viewer.nationalmap.gov/advanced/terriajs-usgs/#clean&https://raw.githubusercontent.com/ethoms-usgs/terria-map-examples/master/sb_datarelease_AK_WFS.json
