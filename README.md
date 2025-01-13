# Geology-from-points-and-lines
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.14629465.svg)](https://doi.org/10.5281/zenodo.14629465)

This method allows for the creation of a digital geological map starting from point and line data, automating the process of generating geological units and simplifying the creation of detailed geological maps

Geoprocessing tools for QGIS 3.x to generate Geological Units from the drawing of geological boundaries, with points containing geological information (ID code of the Geological Units).

To create polygons from lines and points in a GIS, follow these steps:
   
1) Create the lines: Use QGIS editing tools to draw the lines (geological contacts) that define the boundaries of the future polygons. Ensure that the lines intersect or touch correctly to form closed areas.

2) Insert the points: Add the points that represent geological information you want to use to create the polygons.
   
3) Generate the polygons and lines (geological contacts): Use the plugin 'Geology from points and lines' to generate polygons and geological contacts. This tool connects the points and lines to create enclosed areas and attributes the geological information contained in the points.
   
![geology_plugin](https://github.com/user-attachments/assets/58548c20-a1e8-4a49-a04e-689e8d75cd3a)
