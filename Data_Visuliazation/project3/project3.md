

# Project 3: Stock Market Indices from CSV files

## Overview

This project involves reading, cleaning, and plotting historical stock market data from CSV files provided by the Federal Reserve Economic Data (FRED) repository. The project is structured into two main parts:

1. **Data Reading and Initial Plotting:** Implementation of Python functions to read and clean CSV data and create initial line plots of stock indices.
2. **Date Conversion and Enhanced Plotting:** Enhancing plots by converting ISO date formats into a format suitable for plotting and adding features like dual y-axes for comparing two indices.


## Data Files

The project uses several CSV files for major stock indices, which are located in the `data` directory:
- `DJIA.csv` - Dow Jones Industrial Average
- `NASDAQ.csv` - NASDAQ Composite Index
- `SP500.csv` - S&P 500

## Functions to Implement

- `read_series(index_file)`: Reads the CSV file and returns a list of tuples containing the dates and index prices.
- `clean_series(raw_series)`: Cleans the data by removing entries for non-trading days and converting index prices to floats.
- `plot_prices(index_file)`: Generates a line plot of the index prices.
- `isodate_to_day(isodate)`: Converts ISO date strings to Matplotlib's date format.
- `plot_dates_prices(index_file)`: Creates a plot using date conversions for clearer x-axis labels.
- `plot_two_indices(index_file1, index_file2)`: Plots two indices on a single graph with dual y-axes.

