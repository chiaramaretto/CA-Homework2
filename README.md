# Spectral Clustering Homework

This repository contains a Jupyter Notebook that implements and explores spectral clustering techniques on various datasets. The notebook is structured as a homework assignment for computational linear algebra, focusing on clustering algorithms and their applications.

## Notebook Overview

The notebook is divided into the following sections:

1. **Load Datasets**: 
   - Load 2D datasets (`Circle.csv` and `Spiral.csv`) and create a synthetic 3D dataset.
   - Visualize the datasets.

2. **Define Useful Functions**:
   - Implement similarity and adjacency matrix construction.
   - Define methods for eigenvalue computation, including:
     - Inverse Power Method
     - Shifting Method
     - Deflation Method

3. **Spectral Clustering**:
   - Apply spectral clustering to the Circle, Spiral, and synthetic 3D datasets.
   - Compute Laplacian matrices, eigenvalues, and eigenvectors.
   - Use k-means clustering on eigenvectors to identify clusters.
   - Visualize clustering results.

4. **Alternative Clustering Algorithms**:
   - Compare spectral clustering with:
     - K-means clustering
     - DBSCAN clustering
   - Evaluate clustering performance using the Adjusted Rand Index (ARI).

## Requirements

The notebook requires the following Python libraries:

- `numpy`
- `pandas`
- `matplotlib`
- `scipy`
- `scikit-learn`

Install the dependencies using pip:

```bash
pip install numpy pandas matplotlib scipy scikit-learn
