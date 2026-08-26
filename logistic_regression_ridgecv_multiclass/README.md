markdown

# Project Name: Logistic Regression Model Fine Tuning

> Implementation of Logistic Regression for binary and multiclass classifications by exploring some of the tools and techniques that can be used to fine tune the model for higher accuracy

## 🎯 Why I Built This
I built this project to understand Logistic Regression and to explore different parameters and techniques that can be used to fine tune the model 

## ✨ Key Features
- Generate your own datasets for binary and multiclass classifications using 'make_classifications'
- Split data into train and test datasets
- Used simple Logistic Regression, GridSearch with Logistic Regression, cv (cross Validation) and hyperparameters to fine tune models accuracy
- Visualize and comparted results of different models using performance metrics such as confusion metrics, presicion, recall and f1 score etc
- Addressed the problem of imbalanced dataset by running GridSearch with class_weights as a parameter

## 📁 Project Structure
logistic_regression/
│
├── notebooks/
│  ├── logisticregression.ipynb       # Jupyter notebook
├── requirements.txt # Project dependencies
└── README.md

## 🚀 Quick Start

Follow these steps to run the project locally:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/diwakar5181/machine-learning-projects.git
   cd logistic_regression
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the program:**
   - upload logistic_regression.ipynb to google colab
   - or open project in an ide like Visual Studio

## 💡 What I Learned
- Logistic Regression, sigmoid function and model creation
- Generating data for binary and multiclass classifications
- GridSearch for finding best fit params and incresing models accuracy by fine tuning hyperparameters
- Logistic Regression performance metrics such as confusion metrics, presicion, recall and f1 score etc
- How to address the problem of imbalanced datasets by using class_weights as one of the parameters