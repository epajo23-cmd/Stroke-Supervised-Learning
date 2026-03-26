# Stroke Prediction with Supervised Learning

This project is a supervised learning assignment focused on predicting stroke risk from healthcare data. It uses the Healthcare Stroke Prediction Dataset and compares the performance of three classification models: Random Forest, Support Vector Machine (SVM), and Multi-Layer Perceptron (MLP).

---

## Project Overview

The notebook loads patient health data, preprocesses it, and trains multiple supervised learning models to predict whether a patient has experienced a stroke.

The project includes:
- data loading and inspection
- missing value handling
- categorical feature encoding
- feature scaling
- train/test split
- model training and evaluation

---

## Models Used

- Random Forest
- Support Vector Machine (SVM)
- Multi-Layer Perceptron (MLP)

---

## Evaluation Metrics

The models are compared using:
- Accuracy
- F1-score
- Confusion Matrix
- Classification Report

Because the dataset is imbalanced, the project does not rely only on accuracy and also considers class-sensitive evaluation.

---

## Files

- `stroke_supervised_learning.ipynb` — main notebook with preprocessing, training, and evaluation
- `healthcare-dataset-stroke-data.csv` — dataset used for training and testing
- `Eden_Pajo_Report.pdf` — short written report explaining dataset choice, model comparison, and ethical considerations

---

## Technologies Used

- Python
- pandas
- NumPy
- scikit-learn
- matplotlib
- seaborn
- Jupyter Notebook

---

## How to Run

1. Open the project in Jupyter Notebook or VS Code
2. Make sure the required Python libraries are installed
3. Keep the dataset file in the correct path
4. Run the notebook cells in order

---

## Notes

- Missing BMI values are filled using the median
- Categorical variables are encoded using one-hot encoding
- Numerical features are scaled before training SVM and MLP
- The project highlights the challenges of healthcare classification, especially class imbalance and ethical risks from misclassification

---

## Purpose

This project was developed for educational purposes to demonstrate how supervised learning models can be applied to a real-world healthcare classification problem.
