# What is this?
An alternative GRIB Driver for GDAL using EcCodes, to maximize compatibility with GRIB1 and GRIB2 formats.
Tested on Ubuntu 20.04 with GDAL 3.1.2 (PROJ 7.1.0) and EcCodes 2.18.0 .

## How to try
```
git clone https://github.com/coppolafab/gdal_grib_demo.git
cd gdal_grib_demo
docker run --rm -it -v $PWD/gribs:/gribs coppolafab/gdal_grib_demo
gdalinfo /gribs/mn2t6.grb
```