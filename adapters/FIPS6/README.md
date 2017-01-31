
FIPS6 data can be found here -- 

http://www.nws.noaa.gov/geodata/


Specifically, public forecast zones:: http://www.nws.noaa.gov/geodata/catalog/wsom/html/pubzone.htm

http://www.nws.noaa.gov/geodata/catalog/wsom/data/z_04ap17.zip



ogr2ogr -f CSV fips6.csv ./z_04ap17.shp
