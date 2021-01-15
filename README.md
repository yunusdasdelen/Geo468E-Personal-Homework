![ITU LOGO](https://github.com/yunusdasdelen/Geo468E-Personal-Homework/blob/main/Image%20for%20read%20me/ITU_logo.png)
# Geo468E-Personal-Homework          
## Prepared By Yunus Daşdelen

This repository contains documentation and code for Geo468e lecture

# Vegetation Change Detection

The aim of this project is to find the vegetation difference between 2016 and 2020 in Catalca district in Istanbul. The project images have been downloaded from usgsnin https://earthexplorer.usgs.gov/ site. With the help of Landsat8 data, satellite images of Çatalca in 2016 and July 2020 were used and NDVI was calculated.

# Libraries Used in Jupyter Notebook
Libraries to use in conda environment
- rasterio
- matplotlib
- numpy

# Input Bands for landsat8
-Band4 (RED)

-Band5 (NIR)

# NDVI Calculations
NDVI measures the difference between red and near-infrared (NIR) light reflectance from vegetation to create a photosynthetic creatures.


![NDVI calculation](https://github.com/yunusdasdelen/Geo468E-Personal-Homework/blob/main/Image%20for%20read%20me/ndvi.PNG)

# Output Images

- NDVI 2016

![](https://github.com/yunusdasdelen/Geo468E-Personal-Homework/blob/main/Image%20for%20read%20me/ndvi2016.PNG)





-NDVI 2020


![](https://github.com/yunusdasdelen/Geo468E-Personal-Homework/blob/main/Image%20for%20read%20me/ndvi2020.PNG)


As can be seen from the ndvi images, changing vegetation areas are seen in 4 years.



# Reference
- ["Hatarilabs NDVI calculation"](https://www.hatarilabs.com/ih-en/ndvi-calculation-from-landsat8-images-with-python-3-and-rasterio-tutorial)
- ["NDVI informations and NDVI image"](https://earthobservatory.nasa.gov/features/MeasuringVegetation/measuring_vegetation_2.php)




