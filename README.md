# Fraud-Risk-Prediction-and-Prevention-using-LightGBM-From-Model-to-Actionable-Strategy

### 📘 Overview
This project demonstrates a complete end-to-end **Fraud Detection and Prevention** pipeline — from data preprocessing and feature engineering to model building and generating actionable insights. Using the **LightGBM (Light Gradient Boosting Machine)** framework, the project focuses on achieving high precision in detecting fraudulent transactions while minimizing false positives.

---

### 🎯 Objective
The primary goal of this project is to:
- Build a scalable and efficient **machine learning model** to predict fraudulent activities.
- Optimize the **precision-recall trade-off** for real-world fraud detection.
- Translate predictive insights into **actionable prevention strategies** for risk management teams.

---

### ⚙️ Project Workflow

#### 1. **Data Collection & Exploration**
- Imported and cleaned transaction datasets containing both legitimate and fraudulent entries.  
- Conducted **exploratory data analysis (EDA)** to uncover key fraud indicators and correlations.  
- Handled **imbalanced data** using advanced resampling and weighting techniques.

#### 2. **Feature Engineering**
- Derived domain-specific features to capture behavioral and transactional patterns.  
- Normalized continuous variables and encoded categorical features for LightGBM compatibility.  
- Implemented feature selection using **mutual information gain** and **LightGBM feature importance**.

#### 3. **Model Development with LightGBM**
- Built a GPU-accelerated **LightGBM classifier** for high-speed training and inference.  
- Tuned hyperparameters (learning rate, max depth, feature fraction, etc.) using **GridSearchCV**.  
- Evaluated model performance using:
  - **Precision-Recall Curve**
  - **AUC-ROC**
  - **F1-Score**
  - **Confusion Matrix Visualization**

#### 4. **Model Explainability**
- Applied **SHAP (SHapley Additive exPlanations)** for feature importance visualization.  
- Identified top risk drivers influencing model predictions to enhance transparency.  

#### 5. **From Model to Actionable Strategy**
- Designed a **risk scoring framework** to assign fraud probability scores to each transaction.  
- Proposed a **tier-based alert system** for proactive prevention:
  - High-risk → Immediate manual review  
  - Medium-risk → Rule-based secondary check  
  - Low-risk → Automated approval  
- Highlighted interpretability-driven insights for business and compliance teams
