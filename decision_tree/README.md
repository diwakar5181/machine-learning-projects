
# Project Name: Decision Tree

> Create decision tree classifier and regression model and experiment with hyperparameters

## Requirements
* Python 3.14
* Seaborn
* sklear
* matplotlib
* pandas

## 🎯 Why I Built This
I built this project to understand how to build Decision Tree Classifier and Regression models and finetuning through hyperparameters, post and pre pruning.

## ✨ Key Features
- Create datasets for classifier and regression problem
- Split data into train and test datasets
- Implement decision tree classifier and regression models
- Calculate metrics with default model params for classifier model
- Visualize decision tree with default params to understand purity/impurity for classifier model
- Post-prune tree and rerun the model for classifier and regression model
- Compare result with the original model for classifier model
- Pre-pruning or hyperparameter tuning with GridSearchCV for both classifier and regression models
- Find best params for both classifier and regression models

## 📁 Project Structure
```text
decision_tree/
├── notebooks/                            # Jupyter files directory
|   |── decision_tree_classifier.ipynb    # Executable Jupyter notebook            
│   └── decision_tree_regressor.ipynb     # Executable Jupyter notebook
├── requirements.txt                      # Project dependencies
└── README.md
```
## 🚀 Quick Start

Follow these steps to run the project locally:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/diwakar5181/machine-learning-projects.git
   cd decision_tree
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the program:**
   - upload decision_tree_classifier.ipynb to google colab
   - upload decision_tree_regressor.ipynb to google colab
   - or open project in an ide like Visual Studio

## 💡 What I Learned
- Decision Tree Classifier and Regression models implementation
- Loading dataset from Seaborn
- How decision tree calculates purity/impurities using Gini/Entropy
- How decision tree selects the best threshold tree through Information Gain
- post/pre pruning
- GridSearchCV Hyperparameter Tuning