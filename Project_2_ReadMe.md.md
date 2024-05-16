# Spatial Clustering of Mineral Resource Mines

## Overview

This project aims to perform spatial clustering of mineral resource mines based on their geographical coordinates. By clustering the mines, one can gain insights into their spatial distribution and identify regions with high concentrations of mining activities.

## Dataset

The dataset used in this project contains information about operational mineral resource mines, including features such as geographical coordinates (longitude and latitude), mine types, and operational details.

## Model Building

I used the K-Means clustering algorithm to cluster the mines based on their longitude and latitude coordinates. The optimal number of clusters was determined using the Elbow method.

## Evaluation

- Silhouette Score: 0.549
- Davies-Bouldin Index: 0.730

The silhouette score and Davies-Bouldin index indicate moderate to good clustering performance, suggesting that the clusters are reasonably well-separated and distinct.

## Next Steps

- Further analysis of the clusters to understand regional patterns of mining activities.
- Exploration of other clustering algorithms and techniques to improve clustering quality.
- Integration of additional data sources to enrich the analysis and gain deeper insights into mineral resource management.

## Source

Operational Mineral Resource Mines Dataset [Link](https://www.kaggle.com/datasets/thedevastator/operational-mineral-resource-mines)  
License: Creative Commons Attribution 4.0 International License
