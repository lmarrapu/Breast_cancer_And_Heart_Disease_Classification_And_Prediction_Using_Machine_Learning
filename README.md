# Breast Cancer & Heart Disease Prediction Using Machine Learning

## Overview
This repository showcases two impactful projects leveraging machine learning techniques to enhance medical diagnostics:
- **Breast Cancer Prediction**: Classification of malignant and benign tumors.
- **Heart Disease Prediction**: Identifying cardiovascular risks using comprehensive datasets.

Both projects utilize advanced data preprocessing, dimensionality reduction, and machine learning algorithms to deliver predictive insights that could aid clinicians in decision-making.

---

## Key Features
1. **Breast Cancer Prediction**:
   - **Dataset**: UCI Machine Learning Repository.
   - **Algorithms Used**: Logistic Regression, Support Vector Machines (SVM), Perceptron, Random Forest, Decision Tree, and Gradient Boosting.
   - **Dimensionality Reduction**: Principal Component Analysis (PCA) improved accuracy and efficiency.
   - **Best Results**:
     - Accuracy: 97.8%
     - Precision: Perfect classification of benign cases.
     - Specificity: 100%

2. **Heart Disease Prediction**:
   - **Dataset**: Aggregated from Cleveland, Hungarian, Switzerland, and VA datasets (14 features, 920 samples).
   - **Algorithms Used**: Random Forest, Gradient Boosting, SVM, K-Nearest Neighbors (KNN), and Decision Tree.
   - **Dimensionality Reduction**: PCA increased model accuracy and efficiency.
   - **Best Results**:
     - Accuracy: 61% (SVM after PCA).
     - Balanced metrics for sensitivity and specificity.

---

## Methodology
### 1. Data Preprocessing
- **Handling Missing Values**: Median for numeric variables and mode for categorical data.
- **Outlier Mitigation**: Winsorization.
- **Feature Scaling**: Standardization to ensure equal feature contribution.
- **Class Balancing**: Stratified sampling to maintain proportional representation.

### 2. Dimensionality Reduction
- PCA was used to retain 95% of the variance while reducing noise, leading to better model performance.

### 3. Model Training & Evaluation
- Algorithms were evaluated on:
  - **Accuracy**: Overall prediction correctness.
  - **Precision**: Accuracy in positive predictions.
  - **Sensitivity (Recall)**: True positive rate.
  - **Specificity**: True negative rate.
- Visualized using confusion matrices, ensuring detailed insight into each model's performance.

---

## Tools & Libraries
- **Python**: NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn, SciPy.
- **Key Techniques**: PCA, Classification Models, EDA.

---

## Results
### Breast Cancer Prediction
- **Logistic Regression** and **Perceptron** with PCA achieved the best results:
  - Accuracy: 97.8%
  - Specificity: 100%
  - Ideal for distinguishing between benign and malignant tumors.

### Heart Disease Prediction
- **SVM** emerged as the best model post-PCA:
  - Accuracy: 61%
  - Balanced metrics for identifying healthy and at-risk individuals.
  - 
### ⭐️ **If you find this repository useful, give it a star!**
