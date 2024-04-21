
# Project 7: Networks for Social Data

## Overview

This project involves the application of network/graph theories to model and analyze social data. Specifically, it explores graph layout techniques and community detection within social networks. The project is divided into two parts: the first focuses on comparing different graph layout algorithms, and the second on detecting communities within networks using the python-louvain module.

## Functions to Implement

### Part 1: Graph Layout
- **`get_node_indices(grph)`**: Assigns indices to graph nodes.
- **`distance_error(flat_node_pos, path_lengths)`**: Computes the layout error based on node positions and path lengths.
- **`distance_layout(grph, seed)`**: Optimizes node positions to minimize layout error.
- **`plot_spring_vs_distance(grph, with_labels, node_colors, seed)`**: Creates side-by-side plots comparing spring and distance-based layouts.

### Part 2: Community Detection
- **`get_communities(grph, seed)`**: Detects communities within a graph.
- **`plot_caveman_communities(num_cliques, clique_size, prob, seed)`**: Visualizes communities in a caveman graph.
- **`plot_facebook_communities(seed)`**: Plots communities within a Facebook ego network.
