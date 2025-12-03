Iris Flower Classification — CodeAlpha Internship Task 1

This project is part of the CodeAlpha Data Science Internship program.

Project Overview

The objective is to classify Iris flowers into three species:
Setosa
Versicolor
Virginica

based on flower measurements:
Sepal length
Sepal width
Petal length
Petal width
A Random Forest Classifier model is trained to perform the classification task.

Dataset
The dataset used is the Iris Dataset from Scikit-learn.
It contains 150 samples, each with 1 features and 1 species label.
It was provided by CodeAlpha and can also be found on kaggle

Feature	Description
Sepal Length	Length of sepal in cm
Sepal Width	Width of sepal in cm
Petal Length	Length of petal in cm
Petal Width	Width of petal in cm
Target	Species type (0,1,2) — mapped to Setosa, Versicolor, Virginica

Workflow
1. Load dataset from Scikit-learn
2. Split data into training (80%) & testing (20%)
3. Scale features using StandardScaler
4. Train a Random Forest Classifier
5. Evaluate model performance

Results
Model achieved high accuracy on the test set
Classification report includes precision, recall & F1-score
Model successfully differentiates among the three Iris species

Libraries Used

Python 3
Scikit-learn
Numpy
Pandas 

How to Run
1. Clone this repository
2. Open the Python file:
iris_classification.py
(or Jupyter notebook if included)
3. Run all cells / execute script
4. Check terminal output for accuracy & classification report

Conclusion:
This project demonstrates a basic machine learning workflow for classification problems — from preprocessing to evaluation — fulfilling the Task 1 requirement of the CodeAlpha internship.

Developed by: [Abinaya]
Internship Domain: Data Science
Organization: CodeAlpha
