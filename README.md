# 🩺 Diabetes Prediction using Support Vector Machine (SVM)

This project uses Machine Learning to predict diabetes risk based on patient health data.  
Using Support Vector Machine (SVM) 🧠, the model is trained to identify potential cases of diabetes for early detection and improved healthcare outcomes 💡.

---

## 🚀 Project Overview

The goal is to build a classifier that accurately predicts whether an individual has diabetes based on several medical attributes, helping in early diagnosis and treatment.

Key Steps:

- 📊 Data Exploration & Visualization  
- 🧹 Data Preprocessing  
- 🔍 Feature Selection & Scaling  
- 🤖 SVM Model Training  
- ✅ Model Evaluation  
- 💾 Save Trained Model  

---

## 📁 Dataset

**Features:**

- `Pregnancies`
- `Glucose Level` 🍬  
- `Blood Pressure` 💉  
- `Skin Thickness`
- `Insulin Level` 🧪  
- `BMI (Body Mass Index)` ⚖️  
- `Diabetes Pedigree Function` 🧬  
- `Age` 🎂  
- `Outcome` (0 = Non-Diabetic, 1 = Diabetic)

> 📌 Dataset Source: [PIMA Indians Diabetes Dataset - Kaggle](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)

---

## ⚙️ Tech Stack

- Python 🐍  
- NumPy & Pandas 📊  
- Scikit-learn 🤖  
- Matplotlib & Seaborn 📈  
- Jupyter Notebook 📒  

---

## 🧠 Model Used

**🧠 Support Vector Machine (SVM)**

SVM is used for classification based on maximizing the margin between diabetic and non-diabetic cases.

### ✅ Evaluation Metrics:

- **Accuracy Score**
- **Precision**
- **Recall**
- **F1 Score**
- **Confusion Matrix**

---

## 🔄 Project Workflow

```mermaid
graph TD
A[Load Dataset] --> B[Exploratory Data Analysis]
B --> C[Data Preprocessing]
C --> D[Feature Scaling]
D --> E[SVM Model Training]
E --> F[Model Evaluation]
F --> G[Save Model]
