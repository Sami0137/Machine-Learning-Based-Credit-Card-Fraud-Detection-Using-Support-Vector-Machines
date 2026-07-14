# Project Images

This directory contains the figures and visual assets generated during model training and evaluation.

## Available Images

| Image | Description |
|--------|-------------|
| `confusion_matrix_linear_svm.png` | Confusion Matrix of the Baseline Linear Support Vector Machine (SVM) |
| `confusion_matrix_rbf_svm.png` | Confusion Matrix of the Baseline Radial Basis Function (RBF) Support Vector Machine (SVM) |
| `confusion_matrix_polynomial_svm.png` | Confusion Matrix of the Baseline Polynomial Support Vector Machine (SVM) |
| `confusion_matrix_tuned_rbf_svm.png` | Confusion Matrix of the Tuned RBF Support Vector Machine after Hyperparameter Optimization |
| `confusion_matrix_rbf_feature_selection_model.png` | Confusion Matrix of the RBF SVM Model after Feature Selection |
| `baseline_model_comparison.png` | Performance comparison of the baseline Linear, RBF, and Polynomial SVM models |
| `cross_validation_comparison.png` | Performance comparison of the SVM models using 5-Fold Stratified Cross-Validation |
| `rbf_hyperparameter_tuning_comparison.png` | Comparison of the Baseline RBF SVM and Tuned RBF SVM after GridSearchCV Hyperparameter Optimization |
| `all_model_comparison.png` | Overall performance comparison of all implemented SVM models |
| `all_model_comparison_f1_score_graph.png` | F1-Score comparison across all implemented SVM models |

## Purpose

These figures are automatically generated from the Jupyter Notebook during model training and evaluation. They are used throughout the project documentation, including the main `README.md`, to visualize model performance and compare the effectiveness of different SVM approaches.

The visualizations include:

- Confusion matrices for each trained model.
- Baseline model performance comparisons.
- Cross-validation performance comparison.
- Hyperparameter tuning comparison for the RBF SVM.
- Overall comparison of all implemented models.
- F1-Score comparison across all models.

All figures are exported in PNG format to ensure high-quality rendering and compatibility with GitHub Markdown.
