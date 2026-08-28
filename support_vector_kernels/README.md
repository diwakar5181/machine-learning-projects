
# Project Name: Support Vector Kernels

> Implement Support Vector Machine Kernels and how they can be used to engineer features for a non-linear dataset  

## Requirements
* Python 3.14

## 🎯 Why I Built This
I built this project to understand Support Vector Machines, Kernels, how polynomial kernel does feature engineering

## ✨ Key Features
- Generate your own non-linear dataset
- Plot non-linear dataset to show the problem of not being able to draw a best-fit-line/hyperplane
- Split data into train and test datasets
- Polynomial transformation - Create additional features manually to demonstrate how polynomial kernel does feature engineering
- Split transformed dataset into train and test datasets
- Plot actual data points (non-linear data) in 3D to show that there's clearly no easy way of drawing a best-fit-line/plane for solving classification/regression problems
- Plot engineered features to clearly show that after applying Polynomial kernel and engineering the existing features, we can now easily separate the data by dependent feature for a machine learning algorithm.
- Create SVM model with kernel linear to show the accuracy with engineered features dataset
- Create SVM model with kernel linear to show the accuracy with original non engineered features dataset
- Create SVM model with inbuilt poly kernel and degree=2 which is the same as the manual feature engineering we performed on the dataset
- Finally, Create SVM model with original non engineered features dataset and RBF kernel

## 📁 Project Structure
```text
support_vector_kernels/
├── notebooks/                        # Jupyter files directory
│   └── svm_kernels.ipynb             # Executable Jupyter notebook
├── requirements.txt                  # Project dependencies
└── README.md
```
## 🚀 Quick Start

Follow these steps to run the project locally:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/diwakar5181/machine-learning-projects.git
   cd support_vector_kernels
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the program:**
   - upload svm_kernels.ipynb to google colab
   - or open project in an ide like Visual Studio

## 💡 What I Learned
- Support Vector Machines
- Generating non-linear dataset
- Manual Feature engineering
- SVM Kernels Polynomial, RBF, Linear
- How to feature engineer non-linear model
- Plotly 3D