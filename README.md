# Machine Learning-Based Credit Card Fraud Detection Using Support Vector Machines

<p align="center">

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Latest-orange?logo=scikitlearn)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-success)
![SVM](https://img.shields.io/badge/Algorithm-Support%20Vector%20Machine-blueviolet)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

</p>

---

## Project Overview

Credit card fraud has become one of the most significant challenges in modern digital payment systems. Since fraudulent transactions account for only a very small fraction of all transactions, fraud detection is a highly **imbalanced binary classification problem** where traditional accuracy alone is insufficient for evaluating model performance.

This project develops a complete **end-to-end Machine Learning pipeline** for credit card fraud detection using **Support Vector Machines (SVMs)**. Three different SVM kernels—**Linear**, **Radial Basis Function (RBF)**, and **Polynomial**—are implemented and systematically compared using multiple evaluation metrics.

The project also incorporates **Stratified Cross-Validation** and **GridSearchCV Hyperparameter Tuning** to improve model performance and ensure robust evaluation.

---

# Why This Project?

This repository demonstrates the complete lifecycle of a supervised machine learning project, including:

- Data Understanding
- Exploratory Data Analysis (EDA)
- Data Preprocessing
- Feature Scaling
- Model Development
- Model Evaluation
- Stratified Cross-Validation
- Hyperparameter Tuning
- Comparative Performance Analysis

Rather than focusing solely on prediction accuracy, the project emphasizes proper evaluation techniques for highly imbalanced datasets by considering **Precision**, **Recall**, **F1-score**, and **Precision–Recall AUC (PR-AUC)**.

---

# Key Features

- End-to-End Machine Learning Pipeline
- Exploratory Data Analysis (EDA)
- StandardScaler Feature Scaling
- Linear Support Vector Machine
- Radial Basis Function (RBF) Support Vector Machine
- Polynomial Support Vector Machine
- 5-Fold Stratified Cross-Validation
- GridSearchCV Hyperparameter Tuning
- Confusion Matrix Visualization
- Performance Comparison of Multiple SVM Kernels

---

# Dataset

### Dataset

**Credit Card Fraud Detection Dataset**

**Source**

https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

### Dataset Characteristics

| Property | Value |
|-----------|-------|
| Total Transactions | 284,807 |
| Fraudulent Transactions | 492 |
| Legitimate Transactions | 284,315 |
| Features | 30 |
| Target Variable | Class |
| Problem Type | Binary Classification |
| Dataset Nature | Highly Imbalanced |

---

# Project Workflow

```text
Dataset Loading
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Data Preprocessing
        │
        ▼
Feature Scaling
        │
        ▼
Linear SVM
        │
        ▼
RBF SVM
        │
        ▼
Polynomial SVM
        │
        ▼
Model Evaluation
        │
        ▼
5-Fold Stratified Cross-Validation
        │
        ▼
GridSearchCV Hyperparameter Tuning
        │
        ▼
Final Model Comparison
```

---

# Repository Structure

```
Machine-Learning-Based-Credit-Card-Fraud-Detection-Using-Support-Vector-Machines/

├── notebooks/
│   └── Credit_Card_Fraud_Detection.ipynb
│
├── images/
│   ├── confusion_matrix_linear.png
│   ├── confusion_matrix_rbf.png
│   ├── confusion_matrix_polynomial.png
│   ├── confusion_matrix_tuned_rbf.png
│   └── model_comparison.png
│
├── data/
│   └── dataset_link.txt
│
├── requirements.txt
├── .gitignore
├── LICENSE
└── README.md
```

---

# Machine Learning Models

The following Support Vector Machine classifiers were implemented:

| Model |
|--------|
| Linear Support Vector Machine |
| Radial Basis Function (RBF) Support Vector Machine |
| Polynomial Support Vector Machine |

---

# Evaluation Metrics

Model performance was evaluated using the following metrics:

- Accuracy
- Precision
- Recall
- F1-score
- Precision–Recall Area Under Curve (PR-AUC)

---

# Experimental Results

## Baseline Model Performance

| Model | Accuracy | Precision | Recall | F1-score | PR-AUC |
|------|---------:|----------:|--------:|----------:|--------:|
| Linear SVM | **0.9994** | 0.8659 | 0.7474 | **0.8023** | 0.6475 |
| RBF SVM | 0.9993 | **0.9821** | 0.5789 | 0.7285 | 0.5693 |
| Polynomial SVM | 0.9993 | 0.9265 | 0.6632 | 0.7730 | 0.6150 |

---

## Cross-Validation

All three SVM kernels were further evaluated using **5-Fold Stratified Cross-Validation** to obtain more reliable performance estimates while preserving the class distribution within each fold.

---

## Hyperparameter Tuning

The **RBF Support Vector Machine** was optimized using **GridSearchCV** with **2-Fold Stratified Cross-Validation**.

### Best Hyperparameters

| Parameter | Value |
|----------|------:|
| C | 10 |
| Gamma | 0.001 |

### Tuned Model Performance

| Accuracy | Precision | Recall | F1-score | PR-AUC |
|----------:|----------:|--------:|----------:|--------:|
| **0.9995** | 0.9231 | **0.7579** | **0.8324** | **0.7000** |

The tuned RBF model improved **Recall**, **F1-score**, and **PR-AUC** compared to the baseline RBF model while maintaining excellent overall classification performance.

---

# Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

# Installation

Clone the repository.

```bash
git clone https://github.com/Sami0137/Machine-Learning-Based-Credit-Card-Fraud-Detection-Using-Support-Vector-Machines.git
```

Install the required dependencies.

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook.

```bash
jupyter notebook
```

---

# Usage

1. Download the dataset from Kaggle.
2. Place the dataset in the project directory.
3. Open the notebook.
4. Execute all notebook cells sequentially.
5. Review the generated metrics and visualizations.

---

# Future Improvements

Potential future extensions include:

- XGBoost
- LightGBM
- Explainable AI (SHAP/LIME)
- FastAPI REST API
- Docker Containerization
- Real-Time Fraud Detection Pipeline
- Cloud Deployment (AWS/Azure/GCP)

---

# License

This project is licensed under the **MIT License**.

---

# Author

**Samiul Haque Azmi**

Computer Science and Engineering Student

---

# Acknowledgements

- Kaggle for providing the Credit Card Fraud Detection Dataset.
- Scikit-learn for the machine learning framework.
- The open-source Python community for the excellent libraries used throughout this project.

---

## ⭐ If you found this project useful, consider giving it a Star!
