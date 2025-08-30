# 🚙 SUV Purchase Prediction  

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg) 
![ML](https://img.shields.io/badge/Machine%20Learning-Scikit--learn-orange.svg) 
![Status](https://img.shields.io/badge/Status-Completed-brightgreen.svg)  

A beginner-friendly **Machine Learning project** that predicts whether a customer will purchase an SUV based on their **Age** and **Estimated Salary**.  
This project explores data preprocessing, classification models, and decision boundary visualization.  

---

## 📌 Overview
- **Problem:** Predict SUV purchase (Yes/No).  
- **Dataset Features:** Age, Estimated Salary.  
- **Target:** Purchased (1 = Yes, 0 = No).  
- **Tech Stack:** Python, Pandas, NumPy, Matplotlib, Scikit-learn  

---

## 🔎 Steps & Workflow
1. **Data Preprocessing**
   - Handled inputs and scaled features.  
   - Split dataset into training and testing sets.  

2. **Modeling**
   - Implemented **Logistic Regression**.  
   - Implemented **K-Nearest Neighbors (KNN)**.  

3. **Evaluation**
   - Logistic Regression → **~82% accuracy**  
   - KNN → **~85% accuracy**  
   - Plotted **decision boundaries** for visual comparison.  

---

## 📊 Visualizations
| Logistic Regression | KNN Classifier |
|---------------------|----------------|
| ![Logistic](https://via.placeholder.com/300x200?text=Logistic+Regression+Boundary) | ![KNN](https://via.placeholder.com/300x200?text=KNN+Boundary) |

*(Replace placeholders with actual screenshots from your notebook if possible)*  

---

## 🚀 Run the Project
Clone the repo and open in Jupyter Notebook:  
```bash
git clone https://github.com/your-username/suv-prediction.git
cd suv-prediction
jupyter notebook SUV_Predictions.ipynb
