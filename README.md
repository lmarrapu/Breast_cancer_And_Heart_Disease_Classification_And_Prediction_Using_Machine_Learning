# 🩺 **Breast Cancer & Heart Disease Prediction Using Machine Learning**

## 🔍 **Overview**
This repository showcases two impactful machine learning projects aimed at enhancing medical diagnostics:

- **Breast Cancer Prediction**: Classifying malignant and benign tumors for early detection.
- **Heart Disease Prediction**: Identifying individuals at risk of cardiovascular diseases.

Both projects employ advanced data preprocessing, dimensionality reduction, and machine learning algorithms to provide predictive insights that can aid clinicians in making informed decisions.

## 🌟 **Key Features**
### 🦸‍♀️ **Breast Cancer Prediction**
- **Dataset**: UCI Machine Learning Repository.
- **Algorithms Used**: Logistic Regression, Support Vector Machines (SVM), Perceptron, Random Forest, Decision Tree, Gradient Boosting.
- **Dimensionality Reduction**: PCA (Principal Component Analysis) for enhanced accuracy and efficiency.
- **Best Results**:
  - Accuracy: **97.8%**
  - Precision: Perfect classification of benign cases.
  - Specificity: **100%**

### ❤️ **Heart Disease Prediction**
- **Dataset**: Aggregated from Cleveland, Hungarian, Switzerland, and VA datasets (14 features, 920 samples).
- **Algorithms Used**: Random Forest, Gradient Boosting, SVM, K-Nearest Neighbors (KNN), Decision Tree.
- **Dimensionality Reduction**: PCA to boost model accuracy.
- **Best Results**:
  - Accuracy: **61%** (SVM after PCA)
  - Balanced metrics for sensitivity and specificity.

## 🛠️ **Methodology**
### 1. **Data Preprocessing**
- **Handling Missing Values**: Median for numeric and mode for categorical.
- **Outlier Mitigation**: Winsorization to control extreme values.
- **Feature Scaling**: Standardization for uniform feature contribution.
- **Class Balancing**: Stratified sampling for balanced data distribution.

### 2. **Dimensionality Reduction**
- **PCA**: Retained 95% variance while reducing noise, improving model performance.

### 3. **Model Training & Evaluation**
- Evaluated models based on:
  - **Accuracy**: Overall prediction correctness.
  - **Precision**: Accuracy in positive predictions.
  - **Sensitivity (Recall)**: True positive rate.
  - **Specificity**: True negative rate.
- Visualized using **confusion matrices** for detailed model evaluation.

## 🧰 **Tools & Libraries**
- **Python**: NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn, SciPy.
- **Key Techniques**: PCA, Classification Models, Exploratory Data Analysis (EDA).

## 📊 **Results**
### 🦸‍♀️ **Breast Cancer Prediction**
- Best models: Logistic Regression and Perceptron with PCA.
  - Accuracy: **97.8%**
  - Specificity: **100%**
  - Ideal for distinguishing between benign and malignant tumors.

### ❤️ **Heart Disease Prediction**
- Best model: **SVM** post-PCA.
  - Accuracy: **61%**
  - Balanced metrics for identifying healthy and at-risk individuals.

⭐️ **If you find this repository useful, give it a star!**

---

For more details on the implementation, check the code and notebooks in the repository.
