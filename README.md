# WayFinder
## A way to draw relationships between ways in an [Open Street Map](https://www.openstreetmap.org/) ``XML`` file

## Why?
- Finding how roads connect can, of course, be of great interest for mapping applications

- The above notebook finds relationships between ways in an Open Street Map ``xml`` file
- Outputs to a file called ``waysData.json``
- the JS object in the above file has such a format: ``wayID: [list of wayIDs that connect to it]``
  - the version on the CoLab link structures the data bit differently: ``wayID: [list of nodes: ways that connect to it]``

To run the program:
- open in Google CoLab
- run the cells, selecting an extracted XML file from [Open Street Map](https://www.openstreetmap.org/#map=19/28.60952/-81.21443)
- Enjoy!
