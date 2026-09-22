# Hierarchical Clustering

This project demonstrates agglomerative hierarchical clustering on scikit-learn's Iris dataset. The notebook standardizes the measurements, reduces them to two principal components, uses a dendrogram to examine the hierarchy, and visualizes the final cluster assignments.

## Objectives

- Load and explore the Iris dataset.
- Standardize the feature data before clustering.
- Apply principal component analysis (PCA) to create a two-dimensional representation for visualization.
- Build and interpret a Ward-linkage dendrogram to guide the choice of cluster count.
- Train an agglomerative clustering model and visualize its assignments.

## Requirements

- Python 3
- pandas
- matplotlib
- scikit-learn
- SciPy

Install the project dependencies:

```bash
pip install -r requirements.txt
```

## Run the Notebook

From this directory, start Jupyter Notebook or JupyterLab and open the notebook:

```bash
jupyter notebook notebooks/hierarchical_clustering.ipynb
```

Alternatively, upload the notebook to Google Colab and run the cells in order.

## Workflow

1. Load the Iris measurements into a pandas DataFrame.
2. Standardize all numeric features with `StandardScaler`.
3. Reduce the standardized features to two components with PCA.
4. Plot a Ward-linkage dendrogram of the PCA representation to inspect cluster separations.
5. Fit `AgglomerativeClustering` with Ward linkage and two clusters.
6. Plot the PCA representation, colored by the assigned cluster labels.

## Project Structure

```text
hierarchical_clustering/
├── notebooks/
│   └── hierarchical_clustering.ipynb
├── requirements.txt
└── README.md
```
