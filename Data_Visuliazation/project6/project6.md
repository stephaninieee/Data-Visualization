

# Project 6: Arrangements for Word Clouds

## Overview

This project focuses on the creation of word clouds from text data, exploring different methods for arranging text in a visually appealing, non-overlapping layout. Using Python, the project involves the implementation of various algorithms for positioning words with different sizes and frequencies, displayed in a tightly packed manner without overlaps.


## Functions to Implement

### Random Arrangement
- **`random_arrangement(word_boxes, seed)`**: Generates a random arrangement of words.
- **`plot_wordcloud(word_arrangement, title)`**: Visualizes the word cloud from the random arrangement.

### Monte-Carlo Arrangement
- **`intersect_intervals(interval1, interval2)`**: Checks if two intervals overlap.
- **`intersect_boxes(box1, box2)`**: Determines if two boxes overlap based on their positions and sizes.
- **`intersect_box_arrangement(test_box, word_arrangement)`**: Checks if a given box overlaps with any in a current arrangement.
- **`montecarlo_arrangement(word_boxes, max_tries, seed)`**: Attempts to place each word in a non-overlapping manner using a Monte-Carlo approach.

### Spiral Arrangement
- **`spiral_arrangement(word_boxes, seed)`**: Places words along a logarithmic spiral, attempting to maintain non-overlapping positions.

