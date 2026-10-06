# Student Dropout Prediction - Academic Outcome Prediction

**AIML Project - Gupio**

## 📌 Project Overview
Predicts student academic outcome as Dropout / Graduate / Enrolled using machine learning.

## 📊 Dataset Source
UCI Machine Learning Repository - Predict Students' Dropout and Academic Success
https://archive.ics.uci.edu/dataset/697/predict-students-dropout-and-academic-success

## 🛠️ Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn (Random Forest, Train-Test Split)
- Jupyter Notebook

## 🔧 Workflow
1. Data Loading & Understanding
2. Data Cleaning - Leakage Removal (Permitted Features: 24)
3. EDA - Target Distribution Analysis (Imbalanced: Enrolled 18%)
4. Feature Encoding & Scaling
5. Model Training - Random Forest Classifier
6. Model Evaluation - Accuracy, Classification Report
7. Final Model Justification & Feature Importance

## 📈 Results
- **Final Model:** Random Forest Classifier
- **Features Used:** 24 (After leakage removal)
- **Target Classes:** Dropout, Graduate, Enrolled
- **Observation:** Dataset is imbalanced - Enrolled is minority (18%)

## 🚀 How to Run
```bash
pip install pandas numpy matplotlib scikit-learn
jupyter notebook gupio.ipynb
