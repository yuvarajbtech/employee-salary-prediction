# 🧠 Employee Salary Prediction

This project is a machine learning web app that predicts whether an employee earns **more than 50K** or **less than or equal to $50K** per year based on personal and professional attributes such as age, education, occupation, and working hours.

## 🔍 Problem Statement

Predict income classes (<=50K or >50K) using the **Adult Census Income Dataset**. This is a binary classification problem widely used in predictive modeling.

---

## 📊 Features Used

- Age  
- Education Level  
- Job Role (Occupation)  
- Hours Worked Per Week  
- Years of Experience  
- Other features from dataset (for batch prediction):  
  - Marital Status  
  - Relationship  
  - Race  
  - Gender  
  - Capital Gain / Loss  
  - Workclass  
  - Native Country  

---

## 🛠️ Tech Stack

- **Python**
- **Pandas & NumPy**
- **Scikit-learn**
- **Matplotlib / Seaborn**
- **Jupyter Notebook**
- **Streamlit** (for Web App)
- **Joblib** (for saving model)
- **GitHub** (for version control)

---

## 📂 Project Structure

. ├── app.py                    # Streamlit web app ├── model_training.ipynb     # Jupyter Notebook for model building ├── best_model.pkl           # Trained ML model ├── cleaned_adult.csv        # Cleaned dataset for batch prediction ├── requirements.txt         # Python dependencies └── README.md                # Project overview

---

## 🧪 Model Used

- **Random Forest Classifier**  
- Accuracy: ~85%  
- Feature Encoding: LabelEncoder / OneHotEncoder  
- Scaling: StandardScaler (if needed)

---

## 🖥️ Web App Features

- ✅ Predict salary class for a single input (via sliders and dropdowns)
- 📁 Batch prediction using CSV upload
- 📥 Download predictions as CSV

---

📚 Dataset

Adult Income Dataset from UCI Machine Learning Repository



---
👤 Author

Yuvaraj M

BTech CSE (AI & ML)
