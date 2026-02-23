# ❤️ Heart Disease Prediction using Decision Trees & Random Forest

## 📌 Project Overview
This project implements a complete machine learning workflow for **heart disease prediction** using **Decision Tree and Random Forest classifiers**. It focuses on model interpretability, overfitting control, ensemble learning, and cross-validation to build a robust and explainable classification system.

The project demonstrates **industry-grade ML practices**, including tree visualization, feature importance analysis, and model performance comparison.

---

## 🎯 Objectives
- Train and visualize a Decision Tree Classifier
- Analyze and control overfitting using tree depth tuning
- Build a high-performance Random Forest classifier
- Interpret feature importance for clinical insights
- Evaluate models using cross-validation

---

## 🛠️ Tools & Technologies
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Graphviz  

---

## 📊 Dataset
**Source:** Kaggle – Heart Disease Dataset  

**Target Variable:**
- `0` → No Heart Disease  
- `1` → Heart Disease  

**Features Include:**
- Age  
- Sex  
- Chest Pain Type  
- Resting Blood Pressure  
- Cholesterol  
- Fasting Blood Sugar  
- ECG Results  
- Maximum Heart Rate  
- Exercise Induced Angina  
- ST Depression (oldpeak)  
- Number of Major Vessels  
- Thalassemia  

---

## ⚙️ Project Workflow
1. Data Loading and Exploration  
2. Data Preprocessing  
3. Train-Test Split  
4. Decision Tree Training  
5. Decision Tree Visualization (Graphviz)  
6. Tree Depth Optimization  
7. Random Forest Training  
8. Feature Importance Analysis  
9. Cross Validation Evaluation  
10. Model Comparison  

---

## 🌳 Decision Tree Visualization (Graphviz)
Graphviz is used to visualize the internal structure of the Decision Tree model. This helps in:
- Understanding feature splits
- Interpreting predictions
- Analyzing overfitting
- Improving explainability

---

## 📈 Tree Depth Optimization
Tree depth is varied from 1 to 20 to analyze:
- Underfitting at low depth
- Overfitting at high depth
- Optimal depth selection for best generalization

---

## 🌲 Random Forest Classifier
Random Forest improves predictive performance by combining multiple decision trees. This results in:
- Higher accuracy  
- Reduced variance  
- Better generalization  

---

## 🔍 Feature Importance Analysis
Feature importance scores from Random Forest help identify the most influential clinical indicators contributing to heart disease prediction.

Top contributing features include:
- Chest Pain Type  
- Maximum Heart Rate  
- ST Depression (oldpeak)  
- Number of Major Vessels  

---

## 📊 Cross Validation
10-Fold Cross Validation is used to ensure:
- Robust performance evaluation  
- Reduced bias  
- Better generalization  

---

## 🏆 Results
- Decision Tree → High interpretability  
- Random Forest → Superior predictive accuracy  
- Optimized models show strong reliability and stability  

---

## 📁 Repository Structure

```
heart-disease-prediction-using-decisiontree-randomforest/
│
├── dataset/
│   └── heart disease dataset.csv
│
├── notebook/
│   └── Task5_Heart_Disease_Prediction.ipynb
│
├── report/
│   └── Task5_Heart_Disease_Prediction_Report.pdf
│
├── README.md

```

---

## 🚀 How to Run the Project

1. Clone this repository:
   ```bash
   git clone https://github.com/diyab6804-gh/heart-disease-prediction-using-decisiontree-randomforest.git
   
2. Install dependencies
   ```
   pip install pandas numpy matplotlib seaborn scikit-learn graphviz

3. Run the Jupyter Notebook
   ```
   jupyter notebook

---

## 🏁 Conclusion

This project demonstrates advanced machine learning practices, explainable AI concepts, and robust evaluation techniques, making it suitable for real-world healthcare prediction systems.

---

## 👩‍💻 Author

Patel Diya B

AI/ML Intern
