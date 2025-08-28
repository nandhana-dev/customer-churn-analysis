# Customer Churn Prediction Analysis

## Project Overview
This project explores predicting **customer churn** using machine learning techniques on multiple datasets. While the final model didn’t reach perfect accuracy, the project demonstrates **iterative experimentation, feature engineering, and real-world dataset handling**, making it a strong showcase of problem-solving and analytical skills.

---

## Motivation
Customer churn is one of the most critical metrics for any business. Predicting churn helps companies:  
- Retain high-value customers  
- Reduce unnecessary marketing costs  
- Improve long-term profitability  

This project simulates real-world challenges by handling multiple datasets, performing feature engineering, and evaluating models to attempt building an effective churn prediction system.

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
- **Iterative Approach:** Showcases the evolution from simple to complex models.  
- **Data Preprocessing Expertise:** Normalization, categorical encoding, and handling of missing values.  
- **Feature Engineering Skills:** Tested synthetic features, RFM concepts, and combination of numerical + categorical features.  
- **Modeling Skills:** Tried multiple ML approaches, emphasizing understanding of model limitations.  
- **Analytical Thinking:** Clear reasoning for why models succeeded or failed at each step.  

---

## Project Impact
Even though the final model’s predictive accuracy was limited:  
- Demonstrates ability to **analyze datasets critically**  
- Shows **problem-solving and data science workflow**  

---

## Future Work
- Apply **dimensionality reduction** techniques to handle complex datasets.  
- Experiment with **ensemble methods or deep learning models** for better churn prediction.  
- Collect more relevant customer behavior features to improve predictive relationships.  

---

## Tech Stack
- **Python 3.x**  
- **Pandas, NumPy** for data manipulation  
- **Scikit-learn** for machine learning  
- **Matplotlib, Seaborn** for visualization  
- **Google Colab** for development  

---

## Conclusion
This project demonstrates **real-world data science skills**: handling multiple datasets, preprocessing, feature engineering, and iterative modeling. While the final prediction model isn’t perfect, the **process, analytical thinking, and technical skills** provide a strong foundation for further ML projects.
