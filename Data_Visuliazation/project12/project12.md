
# Project 12: Digital Elevation Maps (Part 1)

## Overview

In this project, we focus on the visualization of digital elevation models (DEM), specifically the Grand Canyon DEM provided by the US Geological Survey. The project involves processing and visualizing this DEM data in both 2D and 3D formats. Initially, you will work on contour plotting and image processing to enhance visualization details, and then prepare for more advanced 3D visualizations.



## Functions to Implement

### Data Loading and 2D Visualization
- **`load_dem(dem_file)`**: Loads a DEM from a TIFF file and returns it as a 2D numpy array.
- **`plot_image(image_array, title, vmin, vmax, cmap)`**: Displays the DEM data as a raster image.
- **`plot_contours(dem_array, title, filled, vmin, vmax, cmap)`**: Plots contours of the DEM data.

### Image Processing
- **`compute_features(dem_array)`**: Enhances the DEM image by highlighting features such as edges.
- **`plot_features(dem_array, title, vmin, vmax, cmap)`**: Displays the original and enhanced DEM images side by side.

