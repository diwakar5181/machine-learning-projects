
# Project Name: Logistic Regression ROC Curve

> Create a Logistic Regression model to understand probabilities, threshold, ROC Score, ROC Curve and how to determine the best possible threshold 

## Requirements
* Python 3.14

## 🎯 Why I Built This
I built this project to understand Logistic Regression probabilities, threshold, ROC Score, ROC Curve and how to determine the best possible threshold for optimizing TPR and FPR

## ✨ Key Features
- Generate your own dataset for binary classifications using 'make_classifications'
- Split data into train and test datasets
- Create a dummy probability array with values 0 and retrieve the positive classification probabilities of the actual model
- Calculate roc_auc_score with dummy 0 values and with positive probabilities
- Calculate FPR, TPR and threshold using roc_curve for both dummy 0 values and with positive probabilities
- Plotted both to visualize and conclude that model with higher area under curve performs better
- Finally, plotted threshold for the Logistic Model on the same figure and visualized on how to determine the best possible threshold. For example as you get closer to a 1 threshold you will get higher TPR but your FPR will increase as well.

## 📁 Project Structure
```text
logistic_regression_roc_auc/
├── notebooks/                        # Jupyter files directory
│   └── logistic_regression_roc_auc.ipynb    # Executable Jupyter notebook
├── requirements.txt                 # Project dependencies
└── README.md
```
## 🚀 Quick Start

Follow these steps to run the project locally:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/diwakar5181/machine-learning-projects.git
   cd logistic_regression_roc_auc
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the program:**
   - upload logistic_regression_roc_auc.ipynb to google colab
   - or open project in an ide like Visual Studio

## 💡 What I Learned
- Logistic Regression
- Generating data for binary classifications
- classification probabilities
- Thresholds
- ROC AUC Score
- ROC Curve
- Visualizing thresholds and how it can affect classifications and TPR/FPR 
- Matplotlib - plotting multiple data points and annotations on a single graphs