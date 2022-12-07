# data.gouv
 
from https://www.data.gouv.fr/fr/datasets/consommation-annuelle-delectricite-et-gaz-par-commune-et-par-secteur-dactivite/#resources

electricity/gas consumption 2011 - 2021

Panoply viewer for Netcdf files : 
https://www.giss.nasa.gov/tools/panoply/download/PanoplyWin-5.2.2.zip
https://www.giss.nasa.gov/tools/panoply/download/PanoplyMacOS-jfc-5.2.2.dmg
https://www.giss.nasa.gov/tools/panoply/download/PanoplyJ-5.2.2.tgz

Sample :

https://github.com/lucascraft/data.gouv/blob/main/2011_2021_consommation_gaz-elec.netcdf

![elec/gas consumption](image.png)


# packages

#!/usr/bin/env python3
#-*- coding:utf-8 -*-

 import sys
 !conda activate magics
 !conda install --yes -c conda-forge --prefix {sys.prefix} xarray
 !conda install --yes -c conda-forge --prefix {sys.prefix} netCDF4
 !conda install --yes -c conda-forge --prefix {sys.prefix} matplotlib
 !conda install --yes -c conda-forge --prefix {sys.prefix} python-dateutil
 !conda install --yes -c conda-forge --prefix {sys.prefix} dask
