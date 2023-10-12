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

COMPANY DATASET
Decision Tree Analysis for Sales Segmentation
This project involves the analysis of a cloth manufacturing company's sales data to identify the attributes that contribute to high sales. The approach used in this analysis employs a decision tree classifier with the target variable "Sale," which is first converted into a categorical variable. All other variables are considered independent in the analysis.

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
The project aims to uncover the key attributes or factors that lead to high sales in a cloth manufacturing company. A decision tree classifier is utilized, with the target variable "Sale" converted into three categories: Low, Medium, and High. The analysis focuses on understanding how different attributes or variables impact sales levels and provides insights for the company.

Problem Statement
The company seeks to identify and understand the segments or attributes that are associated with higher sales. This information can be crucial in making data-driven decisions to improve sales performance and product strategies.

Key Steps and Components
Data Collection: The project begins with the import of a dataset, "Company_Data.csv," which contains various attributes related to the company's operations, including price, income, advertising, population, and more.

Exploratory Data Analysis (EDA): EDA is conducted to understand the data, including checking for missing values, examining data distributions, and identifying patterns and trends.

Feature Engineering: The dataset's target variable, "Sales," is categorized into Low, Medium, and High, making it a categorical variable suitable for decision tree analysis.

Data Preprocessing: Categorical features, including "ShelveLoc," "Urban," and "US," are encoded using label encoding, ensuring that they can be used as input to the machine learning model.

Data Splitting: The dataset is divided into training and testing sets to facilitate model training and evaluation.

Model Building: Two decision tree classifiers are constructed, using different criteria, namely "gini" and "entropy." These classifiers are trained on the labeled dataset to learn how various attributes affect sales.

Model Evaluation: The performance of each model is assessed using metrics such as accuracy, precision, recall, F1-score, and confusion matrices. These metrics provide insights into the model's ability to predict sales segments.

Getting Started
To use or replicate this project:

Ensure you have Python installed on your system.

Install the required libraries using pip install pandas numpy scikit-learn matplotlib.

Clone the project repository.

Run the provided Jupyter Notebook or Python script to explore the dataset, build decision tree models, and evaluate their performance.

Dataset
The dataset used in this project is named "Company_Data.csv." It contains various attributes related to the cloth manufacturing company, including price, income, advertising, and more.

Conclusion
The project aims to provide insights into the attributes that impact sales for the cloth manufacturing company. The decision tree analysis, using both "gini" and "entropy" criteria, reveals how different variables contribute to sales segmentation.

The provided code and analysis can be a valuable reference for similar projects and serve as a foundation for understanding the relationship between attributes and sales in the retail industry.
