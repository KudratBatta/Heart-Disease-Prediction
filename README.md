# ❤️ Heart Disease Prediction using K-Nearest Neighbors (KNN)

This project uses machine learning to predict whether a person is likely to have heart disease based on clinical data. Among several algorithms tested, **K-Nearest Neighbors (KNN)** performed the best with an accuracy of **90%**.

---

## 🧠 Project Overview

Cardiovascular disease is a leading cause of death globally. Early diagnosis is essential. This project uses the [UCI Heart Disease Dataset](https://archive.ics.uci.edu/ml/datasets/heart+Disease) to build a predictive model using various classification algorithms, ultimately selecting the best-performing model.

---

## 📊 Dataset

- **Source:** UCI Machine Learning Repository
- **Records:** 303 samples
- **Features:** 13 input features + 1 target

### Selected Features:
- `age`: Age in years  
- `sex`: 1 = male; 0 = female  
- `cp`: Chest pain type (0–3)  
- `trestbps`: Resting blood pressure (mm Hg)  
- `chol`: Serum cholesterol (mg/dl)  
- `fbs`: Fasting blood sugar > 120 mg/dl (1 = true; 0 = false)  
- `restecg`: Resting electrocardiographic results (0–2)  
- `thalach`: Maximum heart rate achieved  
- `exang`: Exercise-induced angina (1 = yes; 0 = no)  
- `oldpeak`: ST depression induced by exercise  
- `slope`: Slope of the ST segment  
- `ca`: Number of major vessels (0–3)  
- `thal`: Thalassemia (1 = normal; 2 = fixed defect; 3 = reversible defect)  
- `target`: 0 = no disease, 1 = disease

---

## ⚙️ Project Workflow

1. **Data Preprocessing**
   - Handled missing values
   - Label encoding of categorical features
   - Feature scaling using `StandardScaler`

2. **Model Training**
   - Tried several classifiers:
     - Logistic Regression
     - Decision Tree
     - Random Forest
     - Support Vector Machine
     - **K-Nearest Neighbors (Best)**

3. **Evaluation**
   - Accuracy Score
   - Confusion Matrix
   - Model comparison

---

## ✅ Best Model: K-Nearest Neighbors (KNN)

- **Scaler Used:** StandardScaler
- **Train-Test Split:** 70% training / 30% testing
- **Test Accuracy:** **90%**
  



---


