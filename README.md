# Academic_Performance_Analysis
This repository contains two projects analyzing factors affecting students' exam performance.

---

## 1. Academic Performance Prediction

**File:** `Academic_Performance_Prediction.ipynb`  

**Objective:**  
Predict students' exam scores based on features such as attendance rate, study methods, sleep hours, and other academic-related factors.  

**Key Features (examples):**
- Attendance rate
- Study method
- Sleep hours
- Other academic behaviors

**Methods:**
- Exploratory data analysis (EDA)
- Data Pre-processing Pipelines (Encoding, Scaling)
- Machine learning models (LinearRegression, RandomForestRegressor, XGBRegressor)
- Evaluation of model performance using RMSE, R², etc.
- Feature Importance Checking

**Goal:**  
Understand the relationship between academic behaviors and exam performance.

---

## 2. Study Method Causal Analysis

**File:** `Study_Method_Causal_Analysis.ipynb`  

**Objective:**  
Investigate the causal effect of study method on exam scores, comparing self-study versus external help (e.g., coaching).  

**Key Features:**
- Treatment column: Study method (Self-study vs External help)
- Outcome: Exam score
- Common causes: Academic behaviors such as sleep hours, study hours, etc.
- Effect modifiers: Variables that might change how effective the treatment is for different students (course, exam_difficulty).

**Methods:**
- Define the treatment, Outcome, Common causes, and Effect modifiers
- Data Pre-processing Pipelines (Encoding, Scaling)
- Causal inference modeling (DoWhy)
- Estimate causal effect (XGBTRegressor, LRSRegressor)
- Comparison of exam outcomes between study methods
- Feature Importance Checking

**Goal:**  
Provide insights into the effectiveness of different study approaches on students' performance.

---
