
# Project 11: Spatial Data Clustering (Part 2)

## Overview

Continuing from Project 10, this week focuses on implementing and visualizing k-means clustering for high-risk counties in the USA based on cancer risk data. The project will involve creating visualizations to compare different clustering methods and analyzing their performance. This part of the project will also explore the efficiency of clustering algorithms by measuring their execution times and comparing the distortion (error) between hierarchical and k-means clustering.



## Functions to Implement

### K-means Clustering and Visualization
- **`kmeans_clustering(cluster_list, num_clusters, num_iterations)`**: Implements k-means clustering algorithm.
- **`plot_kmeans_clusterings()`**: Visualizes the k-means clustering results.
- **`plot_clusters_centers(cluster_list, risk_frame, title)`**: Visualizes clusters with markers at their centers, connected to the counties in each cluster.

### Performance Analysis
- **`plot_closest_pair_times(max_clusters, title)`**: Compares the execution times of two closest pairs methods.
- **`plot_distortion(risk_frame, min_clusters, max_clusters, title)`**: Plots a comparison of distortions for hierarchical vs. k-means clustering methods.


