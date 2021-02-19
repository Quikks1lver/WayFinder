This is a very important step in ensuring the Open Street Map XML data is as
useful as possible. This is a very powerful, very easy to run script that extracts
particular OSM "elements," such as ways/roads, individual nodes, etc.

command: ``osmosis --read-xml map.osm --tf accept-ways highway=motorway,trunk,primary,secondary,tertiary,unclassified,residential,motorway_link,trunk_link,primary_link,secondary_link,tertiary_link,living_street --used-node --write-xml highways.osm``

[Reference](https://wiki.openstreetmap.org/wiki/Key:highway#Highway)
