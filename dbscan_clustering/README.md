# DBSCAN Clustering

This project demonstrates density-based clustering with DBSCAN on a non-linear two-moons dataset. The notebook standardizes the feature data, fits a DBSCAN model, and visualizes the resulting cluster assignments.

## Objectives

- Generate and visualize a non-linear two-moons dataset.
- Standardize the feature data before density-based clustering.
- Train a DBSCAN model to identify clusters and potential noise points.
- Visualize and interpret the resulting cluster assignments.

## Requirements

- Python 3
- matplotlib
- scikit-learn

Install the project dependencies:

```bash
pip install -r requirements.txt
```

## Run the Notebook

From this directory, start Jupyter Notebook or JupyterLab and open the notebook:

```bash
jupyter notebook notebooks/dbscan_clustering.ipynb
```

Alternatively, upload the notebook to Google Colab and run the cells in order.

## Workflow

1. Generate a two-moons dataset with `make_moons` and visualize its underlying labels.
2. Standardize the features with `StandardScaler`.
3. Fit a `DBSCAN` model with an epsilon value of `0.3`.
4. Review the predicted labels, including any points labeled as noise.
5. Plot the original feature space, colored by the DBSCAN cluster assignments.

## Project Structure

```text
dbscan_clustering/
├── notebooks/
│   └── dbscan_clustering.ipynb
├── requirements.txt
└── README.md
```
