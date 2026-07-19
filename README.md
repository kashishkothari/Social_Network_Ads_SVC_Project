- Project Overview:
This project implements the Naive Bayes Classification algorithm to predict whether a customer will purchase a product based on their Age and Estimated Salary. The dataset is a binary classification problem where the target variable indicates whether the customer made a purchase.

Naive Bayes is a probabilistic machine learning algorithm based on Bayes' Theorem. It is known for its simplicity, computational efficiency, and effectiveness in solving classification problems.

- Project Objectives:
Explore and understand the customer purchase dataset.
Perform data preprocessing and feature scaling.
Train a Naive Bayes classification model.
Evaluate model performance using standard classification metrics.
Visualize the decision boundary and classification results.

- Technologies Used:
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Jupyter Notebook

- Project Workflow:
1. Data Preprocessing:
Load the dataset
Check for missing values
Select input and target variables
Split data into training and testing sets
Apply Feature Scaling using StandardScaler
2. Exploratory Data Analysis (EDA):
Purchase distribution
Age distribution
Salary distribution
Correlation analysis
Scatter plots for customer segmentation
3. Model Development:
🧠 Naive Bayes Classifier
The Gaussian Naive Bayes algorithm was used because the input features are continuous numerical variables.
Key Characteristics:

Fast and computationally efficient
Works well for binary classification
Suitable for continuous data using Gaussian distribution
Easy to interpret and implement

- Model Evaluation:
The model is evaluated using:

Accuracy Score
Precision
Recall
F1-Score
Confusion Matrix
Classification Report
