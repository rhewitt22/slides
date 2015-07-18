##  Command Line

 - [Geospatial Data Abstraction Library](http://www.gdal.org/): GDAL is the command line tool everyone uses under the hood.
 - [GDAL Cheatsheet](https://github.com/dwtkns/gdal-cheat-sheet) 


    brew install gdal
    
    # Convert ESRI Shapefile to GeoJSON
    ogr2ogr -f "GeoJSON" output.json input.shp  