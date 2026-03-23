# 📊 Customer Churn Prediction (ANN)

## 🚀 Overview
This project predicts whether a customer will **churn (leave the bank)** using an Artificial Neural Network (ANN). It involves data preprocessing, feature engineering, and deep learning for binary classification.

---

## 🛠️ Tech Stack
- Python  
- Pandas, NumPy  
- Scikit-learn  
- TensorFlow / Keras  
- Matplotlib  

---

## ⚙️ Workflow
- Data Cleaning (removed irrelevant columns)  
- Encoding categorical variables (Geography, Gender)  
- Train-Test Split (80/20)  
- Feature Scaling (StandardScaler)  
- ANN Model Building & Training  
- Model Evaluation (Accuracy)  

---

## 🧠 Model
- Input Layer  
- 2 Hidden Layers (ReLU)  
- Output Layer (Sigmoid)  

```python
model = Sequential()
model.add(Dense(11, activation='relu', input_dim=11))
model.add(Dense(11, activation='relu'))
model.add(Dense(1, activation='sigmoid'))