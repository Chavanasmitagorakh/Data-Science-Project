# Data-Science-Project
# 📉 Customer Churn Prediction Using Machine Learning & Flask

Welcome to the **Customer Churn Prediction** repository!  
This project demonstrates an end-to-end **machine learning workflow** integrated with a **Flask web application** to predict whether a customer is likely to churn based on historical data.

The project is suitable for beginners in machine learning and intermediate learners who want hands-on experience with **model deployment using Flask**.

---

## 📌 What’s Included?

| Module/Stage              | Type                     | Status | Notebook | Web App |
| ------------------------- | ------------------------ | ------ | -------- | ------- |
| Data Collection           | Dataset Preparation      | ✅ | ✅ | ❌ |
| Data Preprocessing        | Cleaning & Encoding      | ✅ | ✅ | ❌ |
| Feature Scaling           | Data Transformation      | ✅ | ✅ | ❌ |
| Model Training            | Machine Learning Model   | ✅ | ✅ | ❌ |
| Model Evaluation          | Metrics & Validation     | ✅ | ✅ | ❌ |
| Model Deployment          | Flask API                | ✅ | ❌ | ✅ |
| Prediction Interface      | REST API                 | ✅ | ❌ | ✅ |

> The notebook covers data analysis and model building, while Flask handles real-time predictions.

---

## 🎯 Goals of This Repository

- Understand customer churn prediction using ML  
- Perform complete data preprocessing and feature engineering  
- Train and evaluate a supervised learning model  
- Deploy the trained model using Flask  
- Build a reusable and real-world ML deployment project  

---

## 🛠 Project Workflow Explained

### 1. 📥 Data Collection
**Concept:** Load customer data containing demographic and service-related features.  
**Includes:**  
- CSV dataset loading  
- Initial data inspection  
**Libraries Used:** `pandas`

---

### 2. 🧹 Data Preprocessing
**Concept:** Clean and prepare data for model training.  
**Features:**
- Handling missing values  
- Encoding categorical variables  
- Removing unnecessary columns  
- Data consistency checks  

---

### 3. 🔄 Feature Scaling
**Concept:** Normalize numerical features to improve model performance.  
**Includes:**
- StandardScaler / MinMaxScaler  
- Saving scaler for deployment  

---

### 4. 🤖 Model Training
**Concept:** Train a machine learning classifier to predict churn.  
**Includes:**
- Train-test split  
- Model fitting  
- Hyperparameter tuning (if applied)  
**Algorithms Used:** Logistic Regression / Random Forest / Decision Tree  

---

### 5. 📊 Model Evaluation
**Concept:** Measure model performance using evaluation metrics.  
**Metrics Used:**
- Accuracy Score  
- Confusion Matrix  
- Precision, Recall, F1-Score  

---

### 6. 🚀 Model Deployment Using Flask
**Concept:** Serve the trained model as a REST API.  
**Includes:**
- Loading saved model (`model.pkl`)  
- Loading scaler (`scaler.pkl`)  
- `/predict` endpoint for predictions  
- JSON-based input and output  

---

## 📊 Evaluation Metrics

- ✅ Accuracy  
- 🔁 Confusion Matrix  
- 📐 Precision, Recall, F1-Score  
- 📉 Model performance comparison  

---

## 🧰 Technologies Used

| Component | Technology |
|---------|------------|
| Language | Python |
| ML Libraries | scikit-learn, pandas, numpy |
| Visualization | matplotlib, seaborn |
| Deployment | Flask |
| Notebook | Jupyter Notebook |

