
# Project 8: Geographic Maps with Overlays (Part 1)

## Overview

This project focuses on overlaying data onto a 2D image, specifically a geographic map of the USA. The primary task involves processing an SVG file to extract county boundaries and related data, which will be used in subsequent projects to overlay additional information. We will extract path attributes from the SVG, calculate county centers, and prepare the data for further analysis and visualization.


## Functions to Implement

### Part 1: Data Extraction and Visualization
- **`get_path_attributes(xml_file)`**: Extracts path attributes from an SVG file.
- **`get_d_verts(path_d, commands)`**: Converts path data into lists of vertices.
- **`plot_paths(path_attributes, title)`**: Visualizes county boundaries using the extracted data.

### Part 2: Data Preparation for Overlay (Upcoming)
- **`make_centers_df(path_attributes)`**: Computes a dataframe with county centers.
- **`write_centers_df(centers_df, file_name)`**: Writes the dataframe to a CSV file.
- **`plot_centers_df(centers_df, title)`**: Plots county centers from the dataframe.

