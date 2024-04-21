
# Project 13: Digital Elevation Maps (Part 2)

## Overview

Project 13 continues the exploration of digital elevation models (DEM) by focusing on more advanced methods of visualizing 3D surfaces from the DEM of the Grand Canyon. Specifically, this project involves representing 3D surfaces as meshes of polygons, generating these meshes from the elevation data, and visualizing them using Plotly.


## Functions to Implement

### Mesh Generation
- **`make_quads(grid_shape)`**: Generates a quad mesh from a specified grid shape.
- **`make_trimesh_fixed(z_grid, diagonal)`**: Converts a quad mesh to a triangle mesh using a fixed diagonal splitting.
- **`make_trimesh_features(z_grid)`**: Generates a triangle mesh based on elevation features to better represent surface variations.

### Visualization
- **`plot_mesh3d(verts, tris, title, camera)`**: Visualizes the triangle mesh using Plotly with 3D camera control.
- **`plot_trisurf(verts, tris, title, camera)`**: Another method to visualize triangle meshes with emphasis on flat shading and edges.

