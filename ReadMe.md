# ❤️ Heart Disease Prediction using Machine Learning

## 📌 Project Overview

This project focuses on predicting the presence of heart disease using various Machine Learning classification algorithms. The goal is to compare the performance of different models and identify the most suitable algorithm for predicting heart disease.

The dataset contains medical attributes such as age, cholesterol level, blood pressure, chest pain type, maximum heart rate, and other health-related features.

Dataset Used: heart.csv

---

## 🎯 Project Objectives

- Perform data preprocessing and feature preparation.
- Train multiple Machine Learning classification models.
- Compare model performance using evaluation metrics.
- Identify the best-performing model for heart disease prediction.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📂 Dataset Features

The dataset includes the following features:

- age
- sex
- cp (Chest Pain Type)
- trestbps (Resting Blood Pressure)
- chol (Cholesterol)
- fbs (Fasting Blood Sugar)
- restecg (Resting ECG)
- thalach (Maximum Heart Rate Achieved)
- exang (Exercise Induced Angina)
- oldpeak
- slope
- ca
- thal

### Target Variable

- 0 → No Heart Disease
- 1 → Heart Disease Present

Based on the uploaded dataset columns.

---

## 🔄 Data Preprocessing

The following preprocessing steps were performed:

- Handled categorical and numerical features
- Feature scaling using StandardScaler
- Train-Test Split
- Prepared data for model training

```python
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import StandardScaler
```

---

## 🤖 Machine Learning Models Used

### 1️⃣ Logistic Regression

```python
from sklearn.linear_model import LogisticRegression
```

### 2️⃣ Decision Tree Classifier

```python
from sklearn.tree import DecisionTreeClassifier
```

### 3️⃣ Random Forest Classifier

```python
from sklearn.ensemble import RandomForestClassifier
```

### 4️⃣ Support Vector Classifier (SVC)

```python
from sklearn.svm import SVC
```

---

## 🚀 Model Training

```python
lr = LogisticRegression()
dt = DecisionTreeClassifier()
rf = RandomForestClassifier()
svc = SVC()
```

Each model was trained using the training dataset and evaluated on unseen test data.

---

## 📊 Evaluation Metrics

The models were evaluated using:

- Accuracy Score
- Classification Report
- Confusion Matrix

```python
from sklearn.metrics import accuracy_score
from sklearn.metrics import classification_report
from sklearn.metrics import confusion_matrix
```

---

## 📈 Model Comparison

The performance of all classification algorithms was compared to determine:

✅ Highest Accuracy

✅ Best Generalization Performance

✅ Most Reliable Predictions

---

## 🔍 Key Learnings

- Understood the complete Machine Learning workflow.
- Applied feature scaling using StandardScaler.
- Trained multiple classification models.
- Compared linear and non-linear algorithms.
- Evaluated model performance using various metrics.
- Improved understanding of supervised learning techniques.

---

## 📁 Project Structure

```
Heart-Disease-Prediction/
│
├── Heart_Disease_Prediction.ipynb
├── heart.csv
├── README.md
└── requirements.txt
```

---

## 📷 Sample Workflow

1. Load Dataset
2. Data Cleaning
3. Feature Engineering
4. Train-Test Split
5. Feature Scaling
6. Model Training
7. Prediction
8. Model Evaluation
9. Performance Comparison

---

## ✅ Conclusion

This project demonstrates how different Machine Learning classification algorithms can be applied to predict heart disease. By comparing Logistic Regression, Decision Tree, Random Forest, and Support Vector Classifier models, we gain valuable insights into model performance and suitability for healthcare prediction tasks.

---

## 👨‍💻 Author

**Syed**

Data Analyst | Power BI Developer | Microsoft Fabric Enthusiast

### Skills

- Python
- SQL
- Power BI
- Microsoft Fabric
- Machine Learning
- Data Analysis
- Data Visualization

---

⭐ If you found this project useful, don't forget to star the repository!
