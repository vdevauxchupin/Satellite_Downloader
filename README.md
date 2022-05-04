# Satellite_Downloader
Jupyter Notebooks that automatically download Landsat/Sentinel images for a given time-window and area, along with code to automatically find the ELA of the Malaspina glacier.

To run the clipper, you need .shp and .shx files of a glacier outline (or any polygon shapefile would do) in your Google Drive, located in your main folder. 
The folder I created is organized as follows:

MyDrive/Project_Remote_Sensing/

In which there are 3 subfolders:
/Optical
/SAR
/Outlines

The /Outlines folder should hold the .shp, .shx files.

The /Optical and /SAR folders will each hold two subfolders: /Original and /Clipped

Make sure that the ROI and AOI (Area Of Interest) coordinates are in degrees (CRS: 4326, WGS 84). 
Make sure the shapefiles and images have the same projection.
