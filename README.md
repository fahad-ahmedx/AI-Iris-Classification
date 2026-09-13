# Iris Data Classification Using AI 🌸

A supervised machine learning project developed in Python using the **Iris dataset** and the **K-Nearest Neighbors (KNN)** classification algorithm.

## 📌 Project Overview

The goal of this project is to train a machine learning model that can classify Iris flowers into different species based on their measurements.

## 🎯 Objectives

* Load and understand the Iris dataset
* Split the dataset into training and testing sets
* Standardize the feature values
* Train a K-Nearest Neighbors (KNN) classification model
* Make predictions on unseen test data
* Evaluate the model using accuracy
* Analyze results using a confusion matrix
* Calculate the F1 score
* Generate a classification report

## 🛠️ Technologies Used

* **Python**
* **Scikit-learn**
* **Matplotlib**
* **Jupyter Notebook**
* **K-Nearest Neighbors (KNN)**

## 📊 Dataset

This project uses the built-in **Iris dataset** provided by Scikit-learn.

The dataset contains measurements of Iris flowers and three different species:

* Setosa
* Versicolor
* Virginica

The features used for classification are:

* Sepal length
* Sepal width
* Petal length
* Petal width

## 🤖 Machine Learning Workflow

```text
Iris Dataset
     ↓
Data Exploration
     ↓
Train/Test Split
     ↓
Feature Scaling
     ↓
KNN Model
     ↓
Model Training
     ↓
Predictions
     ↓
Model Evaluation
     ↓
Accuracy + Confusion Matrix + F1 Score
```

## ⚙️ Train/Test Split

The dataset is divided into:

* **80% Training Data**
* **20% Testing Data**

The training data is used to train the KNN model, while the testing data is used to evaluate its performance on unseen data.

## 📏 Feature Scaling

Feature scaling is performed using `StandardScaler` from Scikit-learn.

This standardizes the feature values before they are given to the KNN model.

## 🧠 Machine Learning Model

The classification algorithm used in this project is:

**K-Nearest Neighbors (KNN)**

The model uses **K = 5 neighbors** to make predictions.

## 📈 Model Evaluation

The model is evaluated using:

* Accuracy
* Confusion Matrix
* Weighted F1 Score
* Classification Report

These evaluation methods help measure how well the model classifies the three Iris species.

## ⚙️ How to Run the Project

### 1. Install Python

Install Python 3 on your computer.

### 2. Install Required Libraries

Open the VS Code terminal and run:

```bash
pip install scikit-learn matplotlib
```

### 3. Open the Notebook

Open:

```text
iris_classification.ipynb
```

in **VS Code** or **Jupyter Notebook**.

### 4. Run the Notebook

Run all cells from top to bottom.

The notebook will:

1. Load the Iris dataset
2. Display dataset information
3. Split the data
4. Scale the features
5. Create the KNN model
6. Train the model
7. Make predictions
8. Calculate accuracy
9. Display the confusion matrix
10. Calculate the F1 score
11. Display the classification report

## 📁 Project Structure

```text
AI-Iris-Classification/
│
├── iris_classification.ipynb
├── README.md
├── LICENSE
└── .gitignore
```

## 📚 Learning Outcome

This project demonstrates the basic supervised machine learning workflow, including:

* Dataset loading
* Data exploration
* Train/test splitting
* Feature scaling
* KNN model training
* Making predictions
* Model evaluation
* Confusion matrix analysis
* F1 score calculation

## 👨‍💻 Project

**Project:** Data Classification Using AI
**Algorithm:** K-Nearest Neighbors (KNN)
**Dataset:** Iris Dataset
**Language:** Python
