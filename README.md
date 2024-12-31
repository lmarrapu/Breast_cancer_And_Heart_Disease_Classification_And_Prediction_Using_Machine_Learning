# 🩺 **Breast Cancer & Heart Disease Prediction Using Machine Learning**  

## 📖 **Overview**  
This repository presents two impactful projects that harness machine learning to revolutionize medical diagnostics:  

- **Breast Cancer Prediction:** Classifying tumors as malignant or benign.  
- **Heart Disease Prediction:** Identifying cardiovascular risks using comprehensive datasets.  

Both projects employ **advanced preprocessing**, **dimensionality reduction**, and **machine learning algorithms** to deliver actionable insights, empowering clinicians in decision-making.  

---

## 🌟 **Key Features**  

### **Breast Cancer Prediction**  
- **Dataset:** UCI Machine Learning Repository.  
- **Algorithms Used:** Logistic Regression, SVM, Perceptron, Random Forest, Decision Tree, Gradient Boosting.  
- **Dimensionality Reduction:** PCA improved accuracy and efficiency.  
- **Best Results:**  
  - **Accuracy:** 97.8%  
  - **Precision:** Perfect classification of benign cases.  
  - **Specificity:** 100%  

### **Heart Disease Prediction**  
- **Dataset:** Aggregated from Cleveland, Hungarian, Switzerland, and VA datasets (14 features, 920 samples).  
- **Algorithms Used:** Random Forest, Gradient Boosting, SVM, KNN, Decision Tree.  
- **Dimensionality Reduction:** PCA increased model accuracy and efficiency.  
- **Best Results:**  
  - **Accuracy:** 61% (SVM after PCA).  
  - Balanced metrics for sensitivity and specificity.  

---

## 🛠️ **Methodology**  

### **1. Data Preprocessing**  
- **Handling Missing Values:** Median for numeric variables, mode for categorical data.  
- **Outlier Mitigation:** Winsorization.  
- **Feature Scaling:** Standardization ensured equal feature contribution.  
- **Class Balancing:** Stratified sampling maintained proportional representation.  

### **2. Dimensionality Reduction**  
- **PCA** retained 95% variance while reducing noise, boosting model performance.  

### **3. Model Training & Evaluation**  
- Algorithms were evaluated based on:  
  - **Accuracy:** Overall correctness.  
  - **Precision:** Accuracy in positive predictions.  
  - **Sensitivity (Recall):** True positive rate.  
  - **Specificity:** True negative rate.  
- Results visualized using **confusion matrices** for detailed performance insights.  

---

## 🛠️ **Tools & Libraries**  
- **Python:** NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn, SciPy.  
- **Key Techniques:** PCA, Classification Models, EDA.  

---

## 📊 **Results**  

### **Breast Cancer Prediction**  
- **Top Models:** Logistic Regression and Perceptron with PCA.  
- **Accuracy:** 97.8%  
- **Specificity:** 100%  
- Ideal for distinguishing between **benign** and **malignant** tumors.  

### **Heart Disease Prediction**  
- **Top Model:** SVM post-PCA.  
- **Accuracy:** 61%  
- Balanced metrics for identifying **healthy** and **at-risk** individuals.  

---

### ⭐️ **If you find this repository useful, give it a star!**

---
