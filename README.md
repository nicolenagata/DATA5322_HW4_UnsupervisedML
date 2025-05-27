# Unsupervised Learning on Energy Data: Slovenia & Croatia

## Overview

This project explores energy consumption data for Slovenia and Croatia using a variety of unsupervised learning techniques.
The goal is to perform exploratory data analysis and gain insights into the inherent structure of the data without any predefined labels.

We focus on the following key objectives:

- Apply multiple unsupervised learning methods to the datasets.
- Generate informative visualizations to interpret the results.
- Discuss the implications of findings in the context of energy usage.

---

## Methods

### 1. Principal Component Analysis (PCA) / Singular Value Decomposition (SVD)

- We compute the principal components to reduce dimensionality.
- Scree plots and cumulative variance plots are used to evaluate the number of components that explain most variance.
- Interpretation focuses on understanding dominant energy consumption patterns and variability.

### 2. Clustering

#### K-Means Clustering

- Performed on principal components.
- The elbow method and silhouette scores guide optimal cluster selection.
- Clusters interpreted with respect to similarities in energy usage profiles.

#### Hierarchical Clustering

- Conducted with various linkage criteria: complete, single, average, and ward.
- Dendrograms visualize cluster structure and relationships.
- Cluster membership analyzed to interpret groupings.

---

## Code Organization

- PracticalHW4.html: see all code and outputs for quick access and readability.
- PracticalHW4.ipynd: download to edit code.

All code is well-commented and organized for clarity and reproducibility.

---

## Authors

- Savannah Truluck
- Stefan Indic
- Nicole Nagata

