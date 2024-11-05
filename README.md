# Clustering Analysis for Data Mining Course

This repository contains a Jupyter Notebook that performs an extensive clustering analysis as part of the **Data Mining Course**. The notebook explores various clustering algorithms from the `scikit-learn` library and evaluates their performance on a given dataset.

## Overview

The notebook demonstrates the application of the following clustering techniques:
- **KMeans Clustering**
- **DBSCAN (Density-Based Spatial Clustering)**
- **Agglomerative Hierarchical Clustering**
- **MeanShift Clustering**
- **Affinity Propagation Clustering**
- **Birch Clustering**
- **Spectral Clustering**
- **OPTICS Clustering**

Each method is assessed using visual plots and evaluated with the **Silhouette Coefficient** to determine the quality of the clustering.

## Key Features

- **Data Preprocessing**: The dataset is preprocessed, normalized, and dimensionality reduction is performed using PCA.
- **Algorithm Application**: Each clustering algorithm is applied with appropriate parameters, and their results are compared.
- **Visualization**: Clustering results are visualized to show the distribution of clusters in the reduced feature space.
- **Evaluation Metrics**: The **Silhouette Coefficient** is used to evaluate and compare the quality of clusters formed by each algorithm.

## Homework Details

This notebook is part of a homework assignment given by **Fadoua Ouamani** as a training exercise for the **Data Mining Course**. It is designed to help students apply and compare different clustering techniques and understand their effectiveness.

## Results Summary

| Algorithm                | Silhouette Coefficient | Observations |
|--------------------------|------------------------|--------------|
| KMeans                   | 0.336                  | Moderate cluster cohesion |
| DBSCAN                   | 0.600                  | Best performer with distinct clusters |
| Agglomerative Clustering | 0.367                  | Second-best performer with clear groups |
| MeanShift                | 0.363                  | Moderate clustering performance |
| Affinity Propagation     | 0.361                  | Multiple clusters with moderate quality |
| Birch                    | 0.374                  | Best performer among alternative methods |
| Spectral Clustering      | 0.324                  | Lower cluster cohesion and overlap |
| OPTICS                   | -0.043                 | Poor performance, many noise points |

## Dependencies

To run this notebook, ensure you have the following Python libraries installed:
- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib`
- `seaborn` (optional for enhanced visualizations)
- `kneed`

Install missing libraries using:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn kneed
