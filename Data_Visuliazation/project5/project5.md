
# Project 5: Images from Dynamical Systems

## Overview

This project involves the creation and visualization of fractals using dynamical systems in Python. We focus on generating raster images of popular fractals such as Julia sets, the Mandelbrot set, and Newton basins. The fractals are visualized using `matplotlib` methods `scatter()` for Julia sets and `imshow()` for the Mandelbrot set and Newton basins. This project is designed to be completed in Vocareum, utilizing specific provided templates and testing tools.



## Functions to Implement

### Julia Sets
- **`invert_fun(complex_fun, complex_val)`**: Determine the pre-images of a complex value under a polynomial function.
- **`julia_set(lmbd, z_0, num_returned, num_dropped, seed)`**: Generate a sequence of complex numbers forming the Julia set.
- **`plot_julia(julia_points, lmbd)`**: Visualize the Julia set points in a scatter plot.

### Mandelbrot Set
- **`iterate_mandel(z_0)`**: Compute the Mandelbrot iteration count before divergence.
- **`mandel_table(real_values, imag_values)`**: Create a table of Mandelbrot set divergence rates.
- **`plot_mandel(real_values, imag_values)`**: Plot the Mandelbrot set as an image.

### Newton Basins
- **`newton_index(roots, z_0)`**: Determine the convergence of Newton's iteration for a given point.
- **`newton_table(roots, real_values, imag_values)`**: Generate a table indicating regions of convergence.
- **`plot_newton(roots, real_values, imag_values)`**: Visualize Newton basins and overlay roots.

