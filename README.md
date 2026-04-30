# 📊 Customer Conversion Prediction

## 🔍 Project Overview
This project aims to develop a machine learning model that predicts whether a customer will subscribe to an insurance policy based on demographic and marketing data.

The goal is to help insurance companies:
- Identify high-potential customers  
- Optimize telemarketing campaigns  
- Reduce operational costs  
- Improve conversion rates  

Model performance is evaluated using the **AUROC (Area Under the ROC Curve)** metric.

---

## 🎯 Objectives
- Predict customer conversion behavior  
- Identify key influencing factors  
- Improve marketing efficiency  
- Enable data-driven decision-making  

---

## ⚙️ Tech Stack
- Python  
- Google Colab  
- Pandas, NumPy  
- Scikit-learn  
- XGBoost  
- Matplotlib, Seaborn  

---

## 🚀 Project Workflow

### 1. Data Loading
- Imported required libraries  
- Loaded dataset  

### 2. Data Cleaning
- Removed duplicates  
- Handled missing values  
- Corrected data types  
- Removed outliers  

---

### 3. Exploratory Data Analysis (EDA)

#### 📌 Univariate Analysis
- Identified class imbalance (~89:11)

#### 📌 Bivariate Analysis
- Analyzed feature relationships with target  
- Found job roles influencing conversions  

#### 📌 Correlation Analysis
- Identified **call duration** as highly correlated feature  

---

### 4. Feature Engineering
- Applied Label Encoding  
- Applied One-Hot Encoding  

Features encoded:

---

### 5. Data Splitting & Balancing
- Train-test split  
- Applied **SMOTE** for class imbalance  

---

### 6. Feature Scaling
- Used **StandardScaler**  

---

### 7. Model Building
Implemented:
- Logistic Regression  
- Random Forest  
- XGBoost  

---

### 8. Model Evaluation
- Compared models using **AUROC Curve**  

---



---

## 🧠 Key Insights
- Call duration strongly impacts conversion  
- Class imbalance required SMOTE handling  
- Ensemble models performed better than linear models  

---

## 🏁 Conclusion
The XGBoost model demonstrated superior performance in predicting customer conversions. Deploying this model can help businesses:
- Target the right audience  
- Reduce marketing costs  
- Improve campaign effectiveness  

---

## 🔮 Future Scope

- Feature Engineering (add new variables)  
- Hyperparameter Tuning  
- Model Deployment (API/Web App)  
- Advanced EDA  
- Testing additional ML models  
- Continuous Monitoring & Retraining  

