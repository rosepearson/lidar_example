# lidar_example
An example of programaticaly downloading and processing LiDAR point clouds from OpenTopography using python.

## Contents
* `lidar_example.ipynb` - This shows an example of downloading the LiDAR files within a user specified rectangle. It then loads on of these LAS files and creates a digital elevation model (DEM) or elevation raster from this file.
* `environment.yml` - Will create a virtual environment containing all libraries required to run the notebook

Other resources:
* [OpenTopography](https://opentopography.org/) -  facilitates community access to high-resolution, Earth science-oriented, topography data, and related tools and resources. The OpenTopography Facility is based at the San Diego Supercomputer Center at the University of California, San Diego and is operated in collaboration with colleagues in the School of Earth and Space Exploration at Arizona State University and at UNAVCO.
* [PDAL](https://pdal.io/index.html) - PDAL is a C++ library with Python wrappers for translating and manipulating point cloud data
* [rioxarray](https://corteva.github.io/rioxarray/stable/index.html) - rioxarray extends xarray with the rio accessor that 'passes' the rasterio engine.
* [geoapis](https://github.com/niwa/geoapis) - A public NIWA library created to faciliate downloading LiDAR from OptenTopography (i.e the first half of the notebook). A good optionis you want to download data in a few lines without mucking about with URLs directly. 
* [QGIS](https://qgis.org/en/site/) - This is an OSS Geographic Information System (GIS) application. This can be handy for visualising spatial data.
