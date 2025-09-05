# Customer Churn Prediction Analysis

## Project Overview
This project explores predicting **customer churn** using machine learning on multiple datasets. While the final model's predictive accuracy was limited, it demonstrates **iterative experimentation, meticulous feature engineering, and robust real-world dataset handling**.

---

## Problem Statement
Customer churn is a critical business metric. Predicting it helps companies **retain high-value customers, reduce costs, and improve long-term profitability**. This project simulates real-world data science challenges by handling diverse datasets and evaluating models through an iterative process.

---

## Project Workflow & Iterations

### 1️⃣ Flop1: Initial Experiment with Mall Customers Dataset
- **Dataset Used:** `Mall_Customers.csv`
- **Features:** Annual Income, Spending Score, and synthetic RFM features
- **Challenges:** RFM features were **synthetic and disconnected** from the original data, leading to **poor model efficiency**.
- **Learning:** Importance of **feature relevance** and avoiding meaningless synthetic variables.

### 2️⃣ Better1: Online Retail Customers Dataset
- **Dataset Used:** `Online_Retail_Customers.csv`
- **Features:** Selected relevant numerical features after normalization
- **Challenges:** Too many features caused **high dimensionality**, making the model less accurate and harder to interpret.
- **Learning:** Highlighted the need for **feature selection and dimensionality reduction** in complex datasets.

### 3️⃣ Final Model: Combined Feature Approach
- **Approach:** Combined all **numerical and categorical features** with proper preprocessing
- **Challenges:** The model struggled due to **weak relationships between features and churn outcome**.
- **Learning:** Demonstrated strong **data preprocessing, feature engineering, and handling of real-world challenges**, even when the dataset does not perfectly support prediction.

---

## Key Features of the Project
* **Iterative Approach:** Showcases a methodical evolution from simple to complex models.
* **Data Preprocessing Expertise:** Proficiency in normalization, categorical encoding, and handling of missing values.
* **Problem-Solving:** Demonstrates the ability to diagnose and debug complex technical issues.
* **Modeling Skills:** Expertise in implementing and evaluating multiple machine learning approaches.
* **Analytical Thinking:** Clear reasoning for model success or failure at each step of the process.

---

## Project Impact
While the final model’s predictive accuracy was limited, this project showcases a strong **data science workflow**. It highlights the ability to analyze datasets critically, diagnose specific technical issues (such as the model’s over-reliance on encoded features from **`LabelEncoder`** and the challenges posed by a dataset with minimal feature correlation), and apply a robust problem-solving mindset to real-world challenges.

---

## Future Work
* Apply **dimensionality reduction** techniques to handle complex datasets more effectively.
* Experiment with **ensemble methods or deep learning models** for better predictive power.
* Collect more relevant customer behavior features to strengthen predictive relationships.

---

## Tech Stack
* **Python 3.x**
* **Pandas, NumPy**
* **Scikit-learn**
* **Matplotlib, Seaborn**
* **Google Colab**

---

## Conclusion
This project demonstrates **real-world data science skills**: handling multiple datasets, preprocessing, feature engineering, and iterative modeling. While the final prediction model isn’t perfect, the **process, analytical thinking, and technical skills** provide a strong foundation for further ML projects.
