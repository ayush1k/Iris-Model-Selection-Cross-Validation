🌸 Iris Model Selection & Hyperparameter Tuning

This repository demonstrates the process of selecting the best machine learning model and optimizing its hyperparameters using the classic Iris dataset. The project focuses on rigorous validation techniques to ensure model robustness and prevent overfitting.

🌟 Key Features

-Model Comparison: Evaluates and compares multiple algorithms including Support Vector Machines (SVM), Random Forest, and Logistic Regression.

-Manual Cross Validation: Demonstrates the logic of cross_val_score for transparent model assessment.

-Hyperparameter Optimization:

  GridSearchCV: Exhaustive search over specified parameter values for SVM (C and kernel).

  RandomizedSearchCV: Efficiently samples parameter distributions to find optimal settings with less computational cost.

-Data Visualization: Visualizing decision boundaries or parameter performance.



🛠 Project Structure and Files

<img width="888" height="227" alt="image" src="https://github.com/user-attachments/assets/89823e21-9013-47d4-acd1-b0855cfcf225" />


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

-Python (3.x)

-Scikit-learn (Model selection and GridSearchCV)

-Pandas (Results analysis in DataFrames)

-NumPy



📊 Tuning Results Summary

The project explored various configurations for the SVM model. Below are the top-performing parameters found during the GridSearchCV process:

<img width="884" height="299" alt="image" src="https://github.com/user-attachments/assets/39b48e0c-9eb7-463b-b14e-bd3d5e9a783a" />



🔗 Connect with Me

💼 LinkedIn

🐦 Twitter

📧 ayushkumar47834@gmail.com
