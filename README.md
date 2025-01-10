# Geology-from-points-and-lines
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.14629465.svg)](https://doi.org/10.5281/zenodo.14629465)
Geoprocessing tools for QGIS 3.x to generate Geological Units from the drawing of geological boundaries, with points containing geological information (ID code of the Geological Units).

To create polygons from lines and points in a GIS, follow these steps:

1) Insert the points: Add the points that represent the geographic or boundary information you want to use to create the polygons.
   
2) Create the lines: Use QGIS editing tools to draw the lines that define the boundaries of the future polygons. Ensure that the lines intersect or touch correctly to form closed areas.
   
3) Generate the polygons and lines (geological contacts): Use the plugin 'Geology from points and lines' to generate polygons and geological contacts. This tool connects the points and lines to create enclosed areas and attributes the geological information contained in the points.

QGIS model schema:
![Schema](https://github.com/user-attachments/assets/c9ba0da3-dd82-45e2-9f45-bd327e36277d)
