# 📊 Employee Retention Dashboard – Proactive Attrition Analysis  
📌 Based on IBM HR Analytics Employee Attrition & Performance Dataset  

---

## 🔎 Project Overview  

This project focuses on predicting and analyzing employee attrition using Machine Learning and Power BI dashboards.  

### 🎯 Objectives:
- Identify employees who are most likely to leave  
- Understand key drivers influencing attrition  
- Support proactive HR retention strategies  
- Reduce operational and financial costs  

---

## 📁 Dataset Information  

- Source: IBM HR Analytics Dataset (Kaggle)  
- Total Records: 1,470 Employees  
- Features: 35 (Numerical & Categorical)  

### Feature Categories:
- **Demographics** – Age, MaritalStatus, DistanceFromHome  
- **Job Attributes** – JobRole, OverTime, BusinessTravel  
- **Compensation & Tenure** – MonthlyIncome, YearsAtCompany, YearsSinceLastPromotion  
- **Employee Sentiment** – JobSatisfaction, EnvironmentSatisfaction, WorkLifeBalance  

---

## 🤖 Machine Learning Approach  

- Model Used: Random Forest Classifier  
- Class Imbalance Handling: SMOTE (Synthetic Minority Oversampling Technique)  
- Target Variable: Attrition  
- Derived Metric: Flight_Risk_Score  

### 📈 Model Performance:
- Recall: 72% (for predicting employees who left)  
- Attrition Rate in Dataset: 16%  

---

## 📊 Power BI Dashboard Structure  

### 1️⃣ HR Overview  
- Attrition Rate  
- Department-wise Attrition  
- Workforce Distribution  

### 2️⃣ Career Growth & Engagement  
- Years at Company  
- Training Frequency  
- Satisfaction Levels  

### 3️⃣ Employee Risk Analysis  
- Flight_Risk_Score Visualization  
- Risk Categories (High Risk, Medium Risk, Safe)  
- Income vs Risk Analysis  

### 4️⃣ Root Cause & Strategy  
- Key Influencers of Attrition  
- Overtime Impact  
- Department-Level Risk Breakdown  
- Strategic Recommendations  

---

## 🚨 Key Findings  

- Higher attrition among employees aged ≤ 21  
- Highest attrition within 1–3 years at company  
- Overtime significantly increases attrition probability  
- Lower monthly income → Higher flight risk score  
- Sales-related roles show higher attrition  

---

## 💰 Business Impact  

- Enables proactive retention strategies  
- Reduces hiring and training costs  
- Supports data-driven HR decision making  
- Helps shift from exit interviews to stay interviews  

Projected Cost Impact (Simulation): ~3M  

---

## 🛠 Tools & Technologies  

- Power BI  
- Python  
- Pandas  
- Scikit-learn  
- Machine Learning  
- Data Visualization  

---

## 📌 Conclusion  

This project demonstrates how HR analytics combined with Machine Learning can help organizations identify high-risk employees early and implement targeted retention strategies to improve workforce stability.

---
