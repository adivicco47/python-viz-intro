This file contains some notes on the source of the data used in this course and how it was prepared.

barotropic.nc - Barotropic vorticity model, kindly provided by Phil Browne. The original file contained 241 timesteps, but we extracted just the first five, using the NetCDF operators command "ncks -d Timestep,0,4 ptcl0000.nc barotropic.nc".

pottmp.2014.1time.nc - NCEP Global Ocean Data Assimilation System (http://www.esrl.noaa.gov/psd/data/gridded/data.godas.html) - original file truncated to contain 1 timestep for reasons of file size.