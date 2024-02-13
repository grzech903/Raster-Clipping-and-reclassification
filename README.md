# Raster-Clipping-and-reclassification
Solution to practical task B 

I cut the rasters for each country. 
However, this method consumes a lot of memory. A better solution would be to use the GDAl library, but I have problems getting it to work on the colab platform. 
Therefore, I had to trim the largest countries manually using the gdal library implemented in the QGIS software. 

improvements to be made:
- Apply compression to tiff files 
-Try to reduce the amount of memory required 
- implement gdal library
- Optimise to speed up calculations 
