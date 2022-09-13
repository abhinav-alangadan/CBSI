# CBSI

This package performs Choice Based Sensor Independent Calculations on Satellite Images.

# Installation

pip install cbsi

# Usage

import cbsi
import numpy as np
from osgeo import gdal
import matplotlib.pyplot as plt


x = gdal.Open('/content/drive/MyDrive/Colab Notebooks/band3.tif').ReadAsArray()
cbsi_ndvi = cbsi.ndvi(f)

plt.imshow(cbsi_ndvi)

# Notes

This Pacage is designed to perform operations on indices similar to NDVI <b>only<//b>

# Authors

Abhinav A
