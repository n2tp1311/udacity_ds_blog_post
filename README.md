Iris Dataset Exploration using CRISP-DM

Overview

This project explores the famous Iris dataset using the CRISP-DM methodology, covering data understanding, preparation,
modeling, and evaluation. The goal is to classify iris species based on sepal and petal measurements.

CRISP-DM Process

1. Business Understanding

The objective is to classify iris flowers into one of three species: Setosa, Versicolor, and Virginica.

Understanding which features contribute most to classification.

Selecting an appropriate model that balances accuracy and interpretability.

2. Data Understanding

Dataset contains 150 samples, each with 4 numerical features:

Sepal length

Sepal width

Petal length

Petal width

Target variable: species (3 classes).

Exploratory analysis includes feature distribution, correlation, and visualization (scatter plots, histograms, and pair
plots).

3. Data Preparation

Checking for missing values, duplicates, and outliers.

Feature scaling applied where necessary (especially for models like Logistic Regression and k-NN).

Splitting the dataset into training (80%) and testing (20%).

4. Modeling

Various classification models tested:

Dummy Classifier (Baseline model)

Logistic Regression

Decision Tree

Random Forest

Cross-validation performed to evaluate model performance.

5. Evaluation

Metrics used for model assessment:

Accuracy

Precision (macro)

Recall (macro)

F1-score (macro)

ROC-AUC (OvR for multi-class)

Model comparison and selection based on performance.

6. Deployment

The best-performing model is Logistic Regression, which showed the highest accuracy and balanced performance across
precision, recall, and F1-score.

The model can be exported and integrated into applications for automated classification.

Future improvements include hyperparameter tuning and additional feature engineering.