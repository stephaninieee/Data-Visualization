

# Project 9: Geographic Maps with Overlays (Part 2)

## Overview

This project builds on the work from Project 8 where we processed an SVG image of a county-level map of the USA. In this continuation, we will overlay county-level data from the Environmental Protection Agency concerning cancer risks from air toxics. The data, initially stored in a CSV file, will be merged with geographic data extracted previously to visualize how cancer risks distribute geographically across the USA.


## Functions to Implement

- **`csv_to_dataframe(file_name, col_idxs, col_names, col_types)`**: Converts a CSV file into a pandas DataFrame with specified columns and types.
- **`merge_by_column(df1, df2, col_name)`**: Merges two dataframes based on a common column.
- **`get_high_risk(county_df, num_counties)`**: Extracts counties with the highest or lowest cancer risks.
- **`plot_image(img_name, title)`**: Loads and displays an image of the USA counties.
- **`plot_risk_map(risk_df, map_name, title)`**: Overlays cancer risk data on an image of the USA counties.
