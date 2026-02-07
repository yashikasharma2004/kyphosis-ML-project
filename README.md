# Kyphosis Prediction Project

This project focuses on predicting whether a kyphosis condition (a spinal disorder) is present after corrective spinal surgery. The dataset contains information on children who have undergone the surgery.

## Table of Contents
* [Dataset](#dataset)
* [Project Objective](#project-objective)
* [Libraries Used](#libraries-used)
* [Models Implemented](#models-implemented)
* [Evaluation Metrics](#evaluation-metrics)
* [Installation](#installation)

## Dataset
The dataset includes the following columns:
* **Kyphosis**: Presence or absence of kyphosis after surgery.
* **Age**: Age of the patient in months.
* **Number**: The number of vertebrae involved in the operation.
* **Start**: The number of the first (topmost) vertebra operated on.

## Project Objective
To build and evaluate machine learning models to predict the presence of Kyphosis based on patient data.

## Libraries Used
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

## Models Implemented
1. **Decision Tree Classifier**: A tree-structured model used for classification.
2. **Random Forest Classifier**: An ensemble method using multiple decision trees to improve prediction accuracy.

## Evaluation Metrics
The models were evaluated using:
* Confusion Matrix
* Classification Report (Precision, Recall, F1-score)
