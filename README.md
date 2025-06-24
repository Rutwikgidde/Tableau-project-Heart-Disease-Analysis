# ❤️ Heart Disease Analysis Dashboard - Tableau Project

This project presents an interactive Tableau dashboard analyzing heart disease risk factors using a real-world dataset. The goal is to identify patterns and predictors of heart disease based on demographics, medical indicators, and exercise-related factors.

---

## 📁 Dataset

- **Fields Included**:
  - `age`: Patient age
  - `sex`: Gender (1 = Male, 0 = Female)
  - `cp`: Chest pain type (1–4)
  - `trestbps`: Resting blood pressure
  - `chol`: Serum cholesterol
  - `fbs`: Fasting blood sugar (1 if > 120 mg/dL)
  - `restecg`: Resting ECG results (0–2)
  - `thalach`: Max heart rate achieved
  - `exang`: Exercise-induced angina
  - `oldpeak`: ST depression
  - `slope`: Slope of the ST segment (1–3)
  - `ca`, `thal`: Additional clinical info
  - `num`: Target variable (1 = Heart disease, 0 = No heart disease)

---

## 📊 Visualizations

The project consists of **12 visualizations** answering specific questions:

### 🟦 1. Demographic Analysis
- **Age and Sex Distribution**
- **Heart Disease by Age Group and Sex**

### 🟨 2. Risk Factor Analysis
- **Cholesterol Levels vs Heart Disease**
- **Fasting Blood Sugar vs Heart Disease**

### 🟥 3. Chest Pain Insights
- **Chest Pain Types in Heart Disease Patients**
- **Chest Pain Type by Age and Sex**

### 🟩 4. Exercise and Heart Rate Metrics
- **Max Heart Rate vs Heart Disease**
- **Exercise-Induced Angina vs Heart Disease**

### 🟧 5. ECG and ST Segment Analysis
- **Resting ECG vs Heart Disease**
- **ST Depression (Oldpeak) vs Heart Disease**
- **Slope of ST Segment vs Heart Disease**

### 🟪 6. Combined Risk Factor Insights
- **Risk Factor Combination: Cholesterol, Age, CP, etc.**

---

## 📈 Dashboards

The visualizations are grouped into **3 dashboards**:

### 🔹 Dashboard 1: Demographics
- Age and sex patterns in heart disease patients

### 🔸 Dashboard 2: Risk Factors
- Cholesterol, sugar levels, and chest pain types

### 🔻 Dashboard 3: ECG & Prediction Metrics
- Heart rate, ST segment, ECG, and exercise responses

---

## 🧠 Key Insights

- Heart disease is more common in **males over 50**.
- **Chest pain type 4** and **low max heart rate** are significant indicators.
- **High cholesterol and ST depression (Oldpeak)** are more frequent in patients with heart disease.
- A combination of features (high `chol`, specific `cp`, older `age`) can effectively indicate heart disease risk.

---

## 📌 Tools Used

- Tableau Public
- Data Preprocessing in Tableau
- Custom Calculated Fields (Age Group, etc.)

---

## ✅ Conclusion

This dashboard offers a comprehensive view of heart disease predictors based on patient health and lifestyle data. It can be used by healthcare professionals or analysts for better decision-making and preventive action.

---

