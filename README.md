# 📉 Customer Churn Prediction Analysis

> **Iterative Modeling. Feature Engineering. Data Science Workflow.**
> A deep-dive exploration into predictive modeling using multiple consumer datasets, focusing on the challenges of feature relevance and model interpretability in real-world scenarios.

---

## 🎯 Project Overview
This project documents the end-to-end journey of building a churn prediction engine. Rather than focusing solely on a high accuracy score, this repository highlights the **iterative experimentation** and **rigorous feature engineering** required when dealing with datasets where feature-to-target correlation is weak.



---

## 🏗️ Evolution of the Model

### 🔹 Phase 1: Mall Customers (RFM Focus)
* **Dataset:** `Mall_Customers.csv`
* **Analysis:** Implemented synthetic Recency, Frequency, and Monetary (RFM) features.
* **Key Learning:** Identified that synthetic features disconnected from the core data distributions lead to "noise" rather than predictive signal.

### 🔹 Phase 2: Online Retail (Dimensionality Challenge)
* **Dataset:** `Online_Retail_Customers.csv`
* **Analysis:** Scaled up to a more complex feature set with normalization.
* **Key Learning:** Encountered high dimensionality issues. This phase emphasized the critical need for **Feature Selection** and **Dimensionality Reduction** (like PCA) to prevent model degradation.

### 🔹 Phase 3: Final Integrated Approach
* **Analysis:** A consolidated pipeline handling both categorical and numerical features through robust preprocessing.
* **Observation:** While predictive accuracy was limited by weak feature-target relationships in the source data, the project successfully demonstrated a production-grade preprocessing and evaluation pipeline.

---

## ✨ Core Competencies Showcased

* 🛠️ **Data Preprocessing** — Advanced handling of missing values, normalization, and categorical encoding.
* 🧪 **Experimental Design** — A methodical approach to diagnosing model performance through multiple iterations.
* 📈 **Analytical Debugging** — Ability to identify technical bottlenecks like `LabelEncoder` bias and feature-target disconnects.
* 🐍 **Tech Stack** — Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn).

---

## 🛡️ License
**Copyright © 2025 Nandhana.** All rights reserved.  
Proprietary work. Unauthorized copying or distribution is prohibited. Inquiries: nandhanaprabhar231@gmail.com

---

<p align="center">
  <i>"In data science, the process is as valuable as the prediction."</i>
</p>
