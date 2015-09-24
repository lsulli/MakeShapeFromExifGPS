# CreateShapefileFromEXIFGPS
Python script to create a point shapefile (with .prj WGS84 geographic coordinate) from GPS data recorded in EXIF data of jpg image file (if exist). 

Type indipendent: tested with Canon and Panasonic

Usage: Copy in image directory and run with python idle, output shapefile will be create in the same directory

Run only with: 
Python 3x
exiftool.exe - http://www.sno.phy.queensu.ca/~phil/exiftool/
exiftool.py - http://smarnach.github.io/pyexiftool/
shapefile.py - https://github.com/GeospatialPython/pyshp
