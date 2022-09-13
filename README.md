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
x = gdal.Open('/content/drive/MyDrive/Colab Notebooks/band3.tif').ReadAsArray()<br/>
cbsi_ndvi = cbsi.ndvi(f)<br/>
<br/>
plt.imshow(cbsi_ndvi)

# Notes

This Pacage is designed to perform operations on indices similar to NDVI <b>only</b>

# Authors

Abhinav A
