# Lab 5: Clustering Techniques with DBSCAN and Hierarchical Clustering

**Name:** Rutu Ketankumar Shah  
**Course:** Advanced Big Data and Data Mining  
**Lab Title:** Lab 5: Clustering Techniques Using DBSCAN and Hierarchical Clustering  

---

## Overview

This lab applies **Hierarchical (Agglomerative) Clustering** and **DBSCAN** to the Wine dataset using Python.  

---

## Steps

### 🔷 Data Preparation
- Load Wine dataset (`sklearn.datasets.load_wine`)
- Convert to `DataFrame` and explore with `.head()`, `.describe()`, `.info()`
- Standardize features (`StandardScaler`)

### 🔷 Hierarchical Clustering
- Apply `AgglomerativeClustering` with `n_clusters = 2, 3, 4`
- Visualize clusters and dendrogram (`scipy.linkage`, `dendrogram`)

### 🔷 DBSCAN
- Apply `DBSCAN(eps=0.3, min_samples=10)`
- Evaluate with:
  - Homogeneity, Completeness, V-measure
  - Adjusted Rand Index, Mutual Information
  - Silhouette Score (if ≥ 2 clusters)
- Visualize DBSCAN clusters

---

## Key Results
✅ Clusters formed and visualized for both techniques  
✅ Dendrogram generated for hierarchical clustering  
✅ DBSCAN metrics computed, including noise points  

---

## Requirements
- Python 3.x
- pandas, numpy, matplotlib
- scikit-learn, scipy

---

## References
- GeeksforGeeks. (2024, May 10). *Wine Dataset in Sklearn*. [Link](https://www.geeksforgeeks.org/machine-learning/wine-dataset/)
- Wu, D. (2024). *Data mining with Python: Theory, application, and case studies* (1st ed.). Chapman & Hall/CRC. https://doi.org/10.1201/9781003462781

---
