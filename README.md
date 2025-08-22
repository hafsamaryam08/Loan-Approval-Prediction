# Loan Approval Prediction (ML Internship Task)

This project is part of my **Elevvo Machine Learning Internship**.  
The objective is to build a **classification model** that predicts whether a loan application will be **approved or not** based on customer details.

---

## 📌 Task Details
- **Objective:** Build a machine learning model to predict loan approval status.
- **Dataset Features:**
  - Applicant information (dependents, education, self_employment)
  - Financial details (income, loan amount, loan term, asset values)
  - Credit score (CIBIL)
- **Target Variable:** `loan_status` (Approved / Rejected)

---

## ⚙️ Technologies Used
- **Python** (Data handling & ML)
- **Pandas** (Data analysis & preprocessing)
- **NumPy** (Numerical operations)
- **Matplotlib & Seaborn** (Data visualization)
- **Scikit-learn** (Machine Learning - Logistic Regression, Model Evaluation)

---

## 📊 Results
- **Model Used:** Logistic Regression  
- **Accuracy Achieved:** ~84% (varies depending on train-test split)  
- **Key Finding:**  
  - CIBIL score and annual income were strong predictors of loan approval.  
  - Logistic Regression performed well for binary classification.  
