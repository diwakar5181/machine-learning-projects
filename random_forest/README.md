# Project Name: Random Forest

> Train Random Forest classifier and regression model and fine tune them with hyperparameters

## Requirements
* Python 3.14
* Seaborn
* sklear
* matplotlib
* pandas
* numpy

## 🎯 Why I Built This
I built this project to understand how to build Random Forest Classifier and Regression models and finetuning through hyperparameters

## ✨ Key Features
- Create datasets for classifier and regression problem
- Analyze data, clean data, perform feature engineering and encoding
- Split data into train and test datasets
- Implement Random Forest classifier and regression models
- Print and review performance metrics for test and training data for both the models
- Fine tune model by passing hyperparameters using RandomizedSearchCV
- Find best params
- Rerun models with the best parameters
- Print and review performance metrics (accuracy_score, precision_score, recall_score, f1_score, roc_auc_score) for both test and training data

## 📁 Project Structure
```text
random_forest/
├── data/
│   └── raw/
│       ├── cardekho_imputated.csv
│       └── Travel.csv
├── notebooks/                                # Jupyter files directory
|   |── random_forest_classification.ipynb    # Executable Jupyter notebook            
│   └── random_forest_regression.ipynb        # Executable Jupyter notebook
├── requirements.txt                          # Project dependencies
└── README.md
```
## 🚀 Quick Start

Follow these steps to run the project locally:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/diwakar5181/machine-learning-projects.git
   cd random_forest
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the program:**
   - upload random_forest_classification.ipynb to google colab
   - upload random_forest_regression.ipynb to google colab
   - or open project in an ide like Visual Studio

## 💡 What I Learned
- Random Forest Classifier and Regression models implementation
- Data cleaning, feature encoding and engineering
- How to run multiple models and find compare metrics
- Classification metrics accuracy_score, precision_score, recall_score, f1_score, roc_auc_score
- Regression metrics r2_score, mean_absolute_error, mean_squared_error
- Hyperparameter Tuning with GridSearchCV