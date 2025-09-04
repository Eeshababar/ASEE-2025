# 🎓 Student Outcomes Prediction with Explainable AI (XAI)

![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-XAI-success.svg)
![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)

This project applies **Machine Learning (ML)** and **Explainable AI (XAI)** to predict and analyze various aspects of student outcomes, with a focus on **transparency** and **interpretability**.  

The project is divided into three main tasks:  

1. **Dropout Prediction** – identifying students at risk of leaving early  
2. **Performance Prediction** – predicting academic achievement  
3. **Mental Health Prediction** – analyzing mental health factors in students  

By combining predictive modeling with **XAI (SHAP, LIME, feature importance)**, the project provides **actionable insights** for educators, policymakers, and researchers.  

---

## 📂 Repository Structure
├── Drop_out_prediction_final_version.ipynb # Dropout prediction workflow with XAI
├── Student_performance_and_XAI.ipynb # Academic performance prediction workflow with XAI
├── Student_mental_health_and_XAI_.ipynb # Mental health prediction workflow with XAI
├── requirements.txt # Dependencies
└── README.md # Project documentation


---

## 🧠 Methodology

### 🔹 Data Preprocessing
- Handling missing values & outliers  
- Encoding categorical variables  
- Train-test split with stratification  
- Feature scaling (MinMax / StandardScaler)  

### 🔹 Models
- Logistic Regression  
- Decision Trees & Random Forests  
- Gradient Boosting / XGBoost  
- Neural Networks (optional extensions)  

### 🔹 Explainable AI (XAI)
- **SHAP** – global + local explanations  
- **LIME** – local instance interpretability  
- **Feature Importance** – model transparency  

---

## 📊 Results (Expected)

| Task                  | Best Model       | Accuracy / F1 | Key Insights |
|-----------------------|-----------------|---------------|--------------|
| Dropout Prediction    | XGBoost / RF    | ~85–90%       | Attendance, grades, financial factors drive dropout |
| Performance Prediction| Random Forest   | ~80–88%       | Study time, parental support, prior grades are key |
| Mental Health Risk    | RF / XGBoost    | ~78–85%       | Sleep quality, stress, workload most influential |

---

## ⚙️ Installation

Clone this repo and install dependencies:

```bash
git clone https://github.com/your-username/student-outcomes-xai.git
cd student-outcomes-xai
pip install -r requirements.txt

