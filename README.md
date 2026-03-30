# 🚦 US Accident Severity Prediction

---

## 📌 Project Overview

This project focuses on predicting accident severity using machine learning techniques on a large-scale US accidents dataset.

The goal is to analyze patterns in accident data and build models that can classify accident severity effectively.

The project demonstrates a complete machine learning workflow, including:

- Data preprocessing  
- Feature engineering  
- Handling imbalanced data  
- Model training  
- Model evaluation  

---

## 📂 Dataset

Since the dataset size is greater than 100 MB, GitHub does not allow direct upload.

👉 **Dataset Link (Kaggle):**  
[https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents]

---

## 🛠️ Tools & Libraries Used

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## 🧹 Data Preprocessing

The dataset was cleaned and prepared using the following steps:

- Removed irrelevant columns  
- Handled missing values  
- Converted data types  
- Extracted features (year, month, hour)  
- Encoded categorical variables  
- Selected important features  

---

## ⚖️ Handling Imbalanced Data

Accident severity data is highly imbalanced, which affects model performance.

Techniques used:

- Applied `class_weight`  
- Evaluated models on imbalanced data  
- Focused on improving recall for minority classes  

---

## 🌳 Models Implemented

### 1️⃣ Decision Tree Classifier

- Simple and interpretable  
- Shows feature importance  
- Can overfit  

---

### 2️⃣ Random Forest Classifier

- Ensemble method  
- Reduces overfitting  
- Better generalization  

---

## 📊 Model Evaluation

Models were evaluated using:

- Accuracy  
- Precision  
- Recall  
- F1 Score  

### 🔍 Key Insight

- Accuracy was **high**  
- Recall was **low**  

➡️ Indicates poor detection of minority classes.

---

## 📉 Problem Observed

- High accuracy is misleading  
- Low recall means important cases are missed  
- Imbalanced data impacts performance  

---

## 🚀 Improvements Applied

- Used class weighting  
- Compared multiple models  
- Focused on recall and F1-score  

---

## 🔬 Model Analysis

- Overfitting vs Underfitting  
- Decision Tree vs Random Forest  
- Impact of imbalance  
- Accuracy vs Recall trade-off  

---

## ▶️ How to Run

1. Clone the repository  
2. Download dataset from Kaggle  
3. Place dataset in project folder  
4. Open `US_Accidents.ipynb`  
5. Run all cells  

---

## 🔮 Future Scope

- XGBoost / LightGBM  
- SMOTE for balancing  
- Hyperparameter tuning  
- Time-series analysis  
- Deployment (Flask / Streamlit)  

---

## 📌 License

This project is for educational purposes only.
