# Data-Science---Decision-Tree
Fraud Detection Model Using Decision Trees
This project demonstrates the use of decision trees for building a fraud detection model. The goal is to classify individuals with taxable incomes as "Risky" or "Good" based on a given threshold of $30,000. The code uses the Python programming language and the scikit-learn library to implement the decision tree classifier.

Table of Contents
Project Description
Getting Started
Dataset
Exploratory Data Analysis
Feature Engineering
Data Preprocessing
Splitting Data
Building Decision Tree Classifiers
Model Evaluation
Conclusion
Project Description
The project uses decision trees to classify individuals into two categories:

"Risky" if their taxable income is less than or equal to $30,000.
"Good" if their taxable income is greater than $30,000.
Two decision tree models are built using different criteria: "gini" and "entropy."

Getting Started
To run the code, you'll need to have Python and the following libraries installed:

pandas
numpy
scikit-learn
You can install these libraries using pip:

pip install pandas numpy scikit-learn

Clone the project repository and run the Jupyter Notebook or Python script to build and evaluate the decision tree models.

Dataset
The dataset used in this project is named "Fraud_check.csv." It contains information about individuals, including their marital status, taxable income, city population, work experience, and whether they are undergraduates. The dataset is used to train and test the decision tree models.

Exploratory Data Analysis
The EDA section includes basic data exploration, such as checking for missing values, duplicates, and visualizing the data.

Feature Engineering
A new column named "Fraud_Check" is created to classify individuals as "Risky" or "Good" based on their taxable income.

Data Preprocessing
Label encoding is applied to convert categorical features into numeric values for model training.

Splitting Data
The dataset is split into training and testing sets for model evaluation.

Building Decision Tree Classifiers
Two decision tree classifiers are built with different criteria: "gini" and "entropy."

Model Evaluation
Model performance is evaluated using accuracy, precision, recall, F1-score, and the confusion matrix.

Conclusion
Both "gini" and "entropy" criteria yield high accuracy, suggesting that the decision tree models are effective at classifying individuals as "Risky" or "Good." However, further validation is recommended to ensure that the accuracy is not due to data leakage or overfitting.
