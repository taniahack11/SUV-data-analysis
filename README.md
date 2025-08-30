# 🚙 SUV Purchase Prediction

This project is a **Machine Learning classification model** that predicts whether a customer will purchase an SUV based on their **Age** and **Estimated Salary**.  
It is a beginner-level project to practice supervised learning techniques.

---

## 📂 Project Overview
- **Goal:** Predict SUV purchase (Yes/No) using customer data.  
- **Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Scikit-learn  

---

## 🔑 Key Steps
1. **Data Preprocessing**
   - Imported dataset with customer Age and Estimated Salary.  
   - Split data into training and test sets.  
   - Applied **feature scaling** for better performance.  

2. **Model Building**
   - Trained **Logistic Regression** and **K-Nearest Neighbors (KNN)** classifiers.  
   - Visualized decision boundaries to understand model predictions.  

3. **Results**
   - Logistic Regression: ~82% accuracy  
   - KNN Classifier: ~85% accuracy (better performance)  

---

## 📊 Visualizations
- Scatter plots showing purchase patterns by Age & Salary.  
- Decision boundary plots comparing Logistic Regression vs KNN.  

---

## 🚀 How to Run
1. Clone this repository  
   ```bash
   git clone https://github.com/your-username/suv-prediction.git
   cd suv-prediction
Install dependencies

bash
Copy code
pip install -r requirements.txt
Run the Jupyter Notebook

bash
Copy code
jupyter notebook SUV_Predictions.ipynb
