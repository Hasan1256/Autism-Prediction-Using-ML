# 📌 Autism Detection Using Machine Learning  
A machine learning project to predict **Autism Spectrum Disorder (ASD)** based on screening test responses.

---

## 📖 Project Overview  
This project applies **machine learning** to classify individuals as **ASD-positive or ASD-negative** using screening data. The **Random Forest model** achieved the best accuracy (**92.14%** cross-validation).  

### 🔹 Key Features  
- ✅ **Data Cleaning & Preprocessing** (Handling missing values, encoding, outlier removal)  
- ✅ **Exploratory Data Analysis (EDA)** (Visualizations, correlations, feature analysis)  
- ✅ **Model Training & Hyperparameter Tuning** (Decision Tree, Random Forest, XGBoost)  
- ✅ **Model Evaluation** (Confusion Matrix, ROC Curve, Classification Report)  
- ✅ **Feature Importance Analysis** (SHAP & Feature Selection)  

---

## 📂 Dataset Description  
The dataset includes demographic details, screening test results, and medical history.  

| Feature Type       | Example Columns                          |
|-------------------|----------------------------------|
| **Screening Scores** | `A1_Score` - `A10_Score` |
| **Demographics**    | `age`, `gender`, `ethnicity`, `contry_of_res` |
| **Medical History** | `jaundice`, `autism (family history)` |
| **Test Information** | `used_app_before`, `result` |
| **Target Variable** | `Class/ASD` (0 = No ASD, 1 = ASD) |

---

## ⚙ Installation & Setup  

### 🔹 1️⃣ Clone the Repository  
```bash
git clone https://github.com/your-username/autism-detection-ml.git
cd autism-detection-ml
