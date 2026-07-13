# Machine Learning Based Credit Card Fraud Detection Using Support Vector Machines

A comprehensive machine learning project that detects fraudulent credit card transactions using multiple **Support Vector Machine (SVM)** kernels. The project evaluates **Linear**, **Radial Basis Function (RBF)**, and **Polynomial** SVM classifiers through extensive experimentation, **Stratified Cross-Validation**, and **Hyperparameter Tuning** to identify the most effective fraud detection model.

---

## Project Overview

Credit card fraud is one of the most significant challenges in modern digital payment systems. Detecting fraudulent transactions accurately while minimizing false alarms is essential for financial institutions and payment service providers.

This project develops a complete machine learning pipeline for fraud detection using the **Credit Card Fraud Detection** dataset. The workflow includes data preprocessing, exploratory data analysis, model training, cross-validation, hyperparameter tuning, and comparative performance evaluation of multiple SVM kernels.

The primary objective is to investigate how different Support Vector Machine kernels perform on an extremely imbalanced fraud detection dataset and determine the most effective model based on multiple evaluation metrics.

---

## Features

- Complete end-to-end machine learning workflow
- Data preprocessing and feature scaling
- Exploratory Data Analysis (EDA)
- Class imbalance analysis
- Linear Support Vector Machine
- Radial Basis Function (RBF) Support Vector Machine
- Polynomial Support Vector Machine
- 5-Fold Stratified Cross-Validation
- Hyperparameter Tuning using GridSearchCV
- Model comparison using multiple evaluation metrics
- Confusion Matrix visualization
- Reproducible Jupyter Notebook implementation

---

## Dataset

**Dataset Name**

Credit Card Fraud Detection Dataset

**Source**

https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

### Dataset Characteristics

- 284,807 transactions
- 30 input features
- Binary classification problem
- Highly imbalanced dataset
- Fraud transactions represent approximately **0.17%** of all transactions

---

## Project Workflow

```

Dataset Loading

↓

Data Understanding

↓

Exploratory Data Analysis

↓

Data Preprocessing

↓

Feature Scaling

↓

Linear SVM

↓

RBF SVM

↓

Polynomial SVM

↓

Model Evaluation

↓

5-Fold Stratified Cross-Validation

↓

Hyperparameter Tuning

↓

Final Model Comparison

```

---

## Machine Learning Models

The following Support Vector Machine classifiers were implemented and evaluated:

- Linear Support Vector Machine
- Radial Basis Function (RBF) Support Vector Machine
- Polynomial Support Vector Machine

---

## Evaluation Metrics

Model performance was evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Precision-Recall AUC (PR-AUC)

---

## Experimental Results

The experimental analysis compares all SVM kernels using:

- Test set evaluation
- Stratified Cross-Validation
- Hyperparameter Tuning
- Confusion Matrix analysis

The comparison demonstrates the strengths and limitations of different SVM kernels when applied to highly imbalanced fraud detection data.

---

## Repository Structure

```

Machine-Learning-Based-Credit-Card-Fraud-Detection-Using-Support-Vector-Machines/

├── notebooks/
│   └── Credit_Card_Fraud_Detection.ipynb
│
├── images/
│
├── data/
│   └── dataset_link.txt
│
├── requirements.txt
├── LICENSE
├── README.md
└── .gitignore

```

---

## Installation

Clone the repository.

```bash
git clone https://github.com/<your-username>/Machine-Learning-Based-Credit-Card-Fraud-Detection-Using-Support-Vector-Machines.git
```

Install the required packages.

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook.

```bash
jupyter notebook
```

---

## Usage

1. Download the dataset from Kaggle.
2. Place the dataset in the appropriate directory.
3. Open the notebook.
4. Execute the notebook from top to bottom.
5. Review the generated evaluation metrics and visualizations.

---

## Future Improvements

Possible extensions of this project include:

- XGBoost and LightGBM implementation
- Deep Learning models
- AutoML-based model selection
- Real-time fraud detection pipeline
- REST API deployment using FastAPI
- Docker containerization
- Cloud deployment

---

## License

This project is licensed under the MIT License.

---

## Author

**Samiul Haque Azmi**

Computer Science and Engineering Student

---

## Acknowledgements

- Kaggle for providing the Credit Card Fraud Detection dataset.
- Scikit-learn for machine learning algorithms and evaluation tools.
- The open-source Python community for the libraries used in this project.
