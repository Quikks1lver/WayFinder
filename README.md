# WayFinder
### A way to draw relationships between ways and find node information in [Open Street Map](https://www.openstreetmap.org/) ``XML`` files

### Why?
- Finding how roads connect can, of course, be of great interest for mapping applications
- These Jupyter notebooks can help with finding relationships between XML data

### Structure
- The ``WayFinder`` notebook finds relationships between ways in an Open Street Map ``xml`` file
- Outputs to a file called ``waysData.json``
- the JS object in the above file has such a format: ``wayID: [list of wayIDs that connect to it]``
  - the version on the CoLab link structures the data bit differently: ``wayID: [list of nodes: ways that connect to it]``

- The ``NodeXYExtractor`` notebook extracts a node's X/Y (lat/long) info

### How to Use
To run the program(s):
- open in Google CoLab
- run the cells, selecting an extracted XML file from [Open Street Map](https://www.openstreetmap.org/#map=19/28.60952/-81.21443)
- Enjoy!
