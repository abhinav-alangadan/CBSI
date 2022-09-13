# CBSI

This package performs Choice Based Sensor Independent Calculations on Satellite Images.

# Installation

pip install cbsi

# Usage

import cbsi <br/>
import numpy as np <br/>
from osgeo import gdal <br/>
import matplotlib.pyplot as plt <br/>
<br/>
<br/>
x = gdal.Open('Layerstacked Raster Image Address').ReadAsArray()<br/>
cbsi_ndvi = cbsi.ndvi(f)<br/>
<br/>
plt.imshow(cbsi_ndvi)

# Notes

This Package is designed to perform operations on indices similar to NDVI <b>only</b>

# Authors

Abhinav A
