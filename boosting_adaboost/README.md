# Project Name: Boosting AdaBoost

> Train Adaboost classifier and regression model and fine tune them with hyperparameters

## Requirements
* Python 3.14
* Seaborn
* sklear
* matplotlib
* pandas
* numpy

## 🎯 Why I Built This
I built this project to understand how to build AdaBoostRegressor Classifier and Regression models and finetuning through hyperparameters

## ✨ Key Features
- Create datasets for classifier and regression problem
- Analyze data, clean data, perform feature engineering and encoding
- Split data into train and test datasets
- Implement AdaBoostRegressor classifier, regression along with the other models
- Print and review performance metrics for test and training data for both the models
- Fine tune model by passing hyperparameters using RandomizedSearchCV
- Find best params
- Rerun models with the best parameters
- Print and review performance metrics for both test and training data

## 📁 Project Structure
```text
boosting_adaboost/
├── data/
│   └── raw/
│       ├── cardekho_imputated.csv
│       └── Travel.csv
├── notebooks/                           # Jupyter files directory
|   |── adaboost_classification.ipynb    # Executable Jupyter notebook            
│   └── adaboost_regression.ipynb        # Executable Jupyter notebook
├── requirements.txt                     # Project dependencies
└── README.md
```
## 🚀 Quick Start

Follow these steps to run the project locally:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/diwakar5181/machine-learning-projects.git
   cd boosting_adaboost
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the program:**
   - upload adaboost_classification.ipynb to google colab
   - upload adaboost_regression.ipynb to google colab
   - or open project in an ide like Visual Studio

## 💡 What I Learned
- Ada Boost Classifier and Regression models implementation
- Data cleaning, feature encoding and engineering
- How to run multiple models and compare metrics
- Classification metrics accuracy_score, precision_score, recall_score, f1_score, roc_auc_score
- Regression metrics r2_score, mean_absolute_error, mean_squared_error
- Hyperparameter Tuning with GridSearchCV