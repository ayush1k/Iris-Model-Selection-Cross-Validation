🌸 Iris Model Selection & Hyperparameter Tuning

This repository demonstrates the process of selecting the best machine learning model and optimizing its hyperparameters using the classic Iris dataset. The project focuses on rigorous validation techniques to ensure model robustness and prevent overfitting.

🌟 Key Features

Model Comparison: Evaluates and compares multiple algorithms including Support Vector Machines (SVM), Random Forest, and Logistic Regression.

Manual Cross Validation: Demonstrates the logic of cross_val_score for transparent model assessment.

Hyperparameter Optimization:

GridSearchCV: Exhaustive search over specified parameter values for SVM (C and kernel).

RandomizedSearchCV: Efficiently samples parameter distributions to find optimal settings with less computational cost.

Data Visualization: (If applicable in notebook) Visualizing decision boundaries or parameter performance.

🛠 Project Structure and Files

File

Description

iris-cross-validation.ipynb

The primary Jupyter Notebook containing the implementation of cross-validation and hyperparameter tuning techniques.

requirements.txt

(Recommended) Lists dependencies like scikit-learn, pandas, and numpy.

🚀 How to Use the Project

1. Setup

# Clone the repository
git clone [https://github.com/ayush1k/Iris-Model-Selection-Cross-Validation.git](https://github.com/ayush1k/Iris-Model-Selection-Cross-Validation.git)
cd Iris-Model-Selection-Cross-Validation

# Install dependencies
pip install scikit-learn pandas numpy


2. Run the Analysis

Open the notebook to explore the different cross-validation strategies:

jupyter notebook iris-cross-validation.ipynb


💡 Technologies Used

Python (3.x)

Scikit-learn (Model selection and GridSearchCV)

Pandas (Results analysis in DataFrames)

NumPy

📊 Tuning Results Summary

The project explored various configurations for the SVM model. Below are the top-performing parameters found during the GridSearchCV process:

Parameter (C)

Kernel

Mean Test Score

1

linear

0.980

10

linear

0.973

20

linear

0.966

20

rbf

0.966

Using the linear kernel with C=1 yielded the highest average accuracy across all folds.

🔗 Connect with Me

💼 LinkedIn

🐦 Twitter

📧 ayushkumar47834@gmail.com
