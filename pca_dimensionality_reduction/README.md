
# Project Name: pca_dimensionality_reduction

> Load dataset, Standardize dataset, and apply PCA to reduce number of features to 2

## Requirements
* Python 3.14
* pandas
* matplotlib
* scikit-learn

## 🎯 Why I Built This
I built this project to understand PCA and how it can be used to reduce number of features/dimensions in a dataset

## ✨ Key Features
- Load dataset from sklearn
- Create data frame
- Perform standardization using StandardScaler()
- Apply PCA and reduce number of features to 2 and the ones which captures the maximum variance in data
- Plot 2 features with the dependent feature as hue (color) to understand if it did a good job of clustering and separating
    the predictable values

## 📁 Project Structure
```text
pca_dimensionality_reduction/
├── notebooks/                              # Jupyter files directory
│   └── pca_dimensionality_reduction.ipynb     # Executable Jupyter notebook
├── requirements.txt                        # Project dependencies
└── README.md
```
## 🚀 Quick Start

Follow these steps to run the project locally:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/diwakar5181/machine-learning-projects.git
   cd pca_dimensionality_reduction
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the program:**
   - upload pca_dimensionality_reduction.ipynb to google colab
   - or open project in an ide like Visual Studio

## 💡 What I Learned
- Principal Component Analysis and how it reduces features by capturing the features with the highest variance in a dataset
- Loading dataset from Sklearn
- Standard Scaling