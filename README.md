# Iris Classification using Logistic Regression and KNN

This project is a practice implementation of machine learning classification algorithms using the famous Iris dataset.

The goal is to classify iris flowers into different species using their physical measurements.

---

## Dataset

The Iris dataset contains measurements of iris flowers belonging to three species:

- Setosa
- Versicolor
- Virginica

Features used:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

Target variable:
Species

---

## Project Workflow

### 1. Exploratory Data Analysis

Visualizations used:

- Pairplot
- Correlation heatmap

These helped understand relationships between features and how different species are distributed.

---

### 2. Data Preprocessing

Steps performed:

- Label encoding of species
- Feature selection
- Train-test split with stratification
- Feature scaling (for KNN)

---

### 3. Model Training

Two classification models were implemented:

1. Logistic Regression
2. K-Nearest Neighbors (KNN)

---

## Model Performance

| Model | Accuracy |
|------|------|
| Logistic Regression | **96%** |
| KNN | **93%** |

Logistic Regression performed slightly better on this dataset.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-learn
- Google Colab

---

## Learning Outcomes

Through this project I practiced:

- Exploratory Data Analysis
- Multi-class classification
- Feature preprocessing
- Model evaluation using accuracy, precision, and F1-score

---

## Author

Mitesh Bhoir  
Computer Engineering Student  
Learning Machine Learning and Data Science
