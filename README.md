# Breast Cancer Classification Using SVM, Logistic Regression, and Random Forest

This project applies Support Vector Machines (SVM), Logistic Regression, and Random Forest classifiers to classify breast cancer tumors as benign or malignant using the **Breast Cancer Wisconsin dataset**. The dataset is included in the `scikit-learn` library. Additionally, this project visualizes the decision boundary for the SVM classifier.

## Project Overview
- **Visualization**: Decision boundary of the SVM classifier is visualized using two selected features.
- **Model Comparison**: The performance of SVM is compared with Logistic Regression and Random Forest classifiers.

### Dataset
- The dataset used is the **Breast Cancer Wisconsin dataset** available in `scikit-learn`.
- The dataset consists of 569 samples with 30 features.
- The target variable is a binary classification (0 = malignant, 1 = benign).

### Libraries
- `pandas`
- `scikit-learn`
- `matplotlib`
- `seaborn`

### Instructions
1. Install the required dependencies:
    ```
    pip install -r requirements.txt
    ```
2. Run the classification script:
    ```
    python svm_breast_cancer.py
    ```

### Results
- Confusion matrix and accuracy scores are printed for SVM, Logistic Regression, and Random Forest classifiers.
- A plot of the decision boundary for the SVM classifier is visualized.

