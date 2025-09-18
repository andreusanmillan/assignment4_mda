# assignment4_mda

## Overview

This assignment explores **Multidimensional Scaling (MDS)** techniques using the classic [Iris flower dataset](https://en.wikipedia.org/wiki/Iris_flower_data_set). The goal is to apply classical and non-metric MDS methods to visualize the relative positioning of flower samples in a reduced-dimensional space based on their physical attributes.

The species of each flower (Setosa, Versicolor, Virginica) are used as **supplementary information** to evaluate the interpretability of the MDS projections. Finally, a **Principal Component Analysis (PCA)** is performed for comparison with MDS results.

## Tasks

1. Center the data using a centering matrix.
2. Compute Euclidean and Scaled Euclidean distances.
3. Perform **Classical MDS** using the scaled distances.
4. Choose the number of dimensions based on eigenvalues.
5. Plot the MDS results and add species information.
6. Perform **Sammon scaling** and **Non-metric MDS**.
7. Compare the results across methods.
8. **Bonus**: Compare with PCA projection.

## Files

- `Assignment4.Rmd` – Full analysis and code
- `README.md` – This file
- `plots/` – Output figures (MDS, PCA)
