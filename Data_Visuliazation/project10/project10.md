

# Project 10: Spatial Data Clustering (Part 1)

## Overview

Project 10 focuses on methods for clustering sets of points in the plane, specifically applying these methods to cluster USA counties based on cancer risk due to air toxics. The project involves implementing algorithms for computing the closest pairs of clusters and using these computations to perform hierarchical clustering of high-risk counties. This clustering will help visualize and analyze the distribution and proximity of high-risk areas.


## Functions to Implement

### Clustering Algorithms
- **`slow_closest_pair(cluster_list)`**: Computes the closest pair of clusters using a brute-force method.
- **`fast_closest_pair(cluster_list)`**: Implements a divide-and-conquer strategy to find the closest pair of clusters more efficiently.
- **`closest_pair_strip(cluster_list, horiz_center, half_width)`**: Assists the divide-and-conquer method by finding the closest pair of clusters within a given strip.

### Hierarchical Clustering
- **`hierarchical_clustering(cluster_list, num_clusters)`**: Mutates a list of clusters by merging the closest pairs until a specified number of clusters remain.

### Visualization
- **`plot_hierarchical_clustering()`**: Function to visualize the results of hierarchical clustering overlaid on the USA county map.

