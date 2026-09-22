# K-Means Clustering

This project demonstrates how to use K-means clustering to group unlabeled data. The notebook creates a two-dimensional synthetic dataset, scales its features, selects a suitable number of clusters, and evaluates the resulting model.

## Objectives

- Create and visualize a clustered dataset with scikit-learn's `make_blobs`.
- Standardize features before training the K-means model.
- Use the elbow method and within-cluster sum of squares (WCSS) to identify a suitable value for `k`.
- Train a K-means model and predict cluster assignments for test data.
- Validate the cluster count with `KneeLocator` and silhouette scores.
- Visualize the predicted clusters.

## Requirements

- Python 3
- pandas
- matplotlib
- scikit-learn
- kneed

Install the project dependencies:

```bash
pip install -r requirements.txt
```

## Run the Notebook

From this directory, start Jupyter Notebook or JupyterLab and open the notebook:

```bash
jupyter notebook notebooks/k_means_clustering.ipynb
```

Alternatively, upload the notebook to Google Colab and run the cells in order.

## Workflow

1. Generate a dataset with three clusters using `make_blobs`.
2. Split the data into training and test sets, then scale both sets with `StandardScaler`.
3. Fit K-means models for several values of `k` and record their WCSS values.
4. Inspect the elbow plot and use `KneeLocator` to estimate the optimal cluster count.
5. Fit a final model with `k = 3`, predict test-set clusters, and visualize them.
6. Compare silhouette scores across candidate values of `k`.

## Project Structure

```text
k_means_clustering/
├── notebooks/
│   └── k_means_clustering.ipynb
├── requirements.txt
└── README.md
```
