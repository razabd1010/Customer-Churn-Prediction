# 📉 Customer Churn Prediction and Business Decision Support System

## 📌 Project Overview

Customer churn is one of the most significant challenges faced by telecommunication companies, directly affecting profitability and long-term customer relationships.

This project develops an end-to-end Machine Learning-based Customer Churn Prediction and Business Decision Support System capable of identifying customers at risk of leaving a telecom provider before churn occurs.

Rather than focusing solely on prediction accuracy, the project emphasizes business value by transforming churn probabilities into actionable customer risk categories and retention strategies.

---

# 🎯 Business Problem

Customer acquisition is considerably more expensive than customer retention.

The objective of this project is to enable telecom companies to:

- Identify customers likely to churn.
- Prioritize retention efforts.
- Allocate marketing resources efficiently.
- Reduce customer loss.
- Improve long-term customer lifetime value.

---

# 📂 Dataset

**Source**

IBM Telco Customer Churn Dataset

The dataset contains customer demographic information, subscribed services, billing information, contract details, and churn status.

Target Variable:

- **Churn**
  - Yes
  - No

---

# ⚙️ Project Workflow

The project follows a complete end-to-end machine learning pipeline.

## 1. Data Understanding

- Dataset exploration
- Missing value analysis
- Data cleaning
- Data validation

---

## 2. Exploratory Data Analysis

Performed extensive EDA including:

- Churn distribution
- Numerical variable analysis
- Categorical feature analysis
- Correlation analysis
- Business insights

---

## 3. Feature Engineering

Several business-oriented features were engineered, including:

- Customer Protection Score
- Household Commitment
- Long-Term Contract Indicator
- Automatic Payment Indicator

These engineered features improved the model's ability to capture customer retention behavior.

---

## 4. Feature Selection

Feature importance analysis was performed using Logistic Regression coefficients.

Multicollinearity was evaluated using Variance Inflation Factor (VIF).

Highly redundant variables were identified and experimentally evaluated.

---

## 5. Machine Learning Models

The following models were developed and compared:

- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost

Each model was evaluated using identical preprocessing pipelines.

---

## 6. Class Imbalance Handling

To improve minority-class detection:

- Stratified Train-Test Split
- Balanced Logistic Regression (`class_weight='balanced'`)
- Threshold Optimization
- Precision-Recall Trade-off Analysis

No synthetic oversampling techniques were used because the dataset exhibited only moderate class imbalance.

---

## 7. Model Evaluation

Evaluation metrics included:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC
- Confusion Matrix
- ROC Curve
- Precision-Recall Curve

---

# 🏆 Final Model

**Balanced Logistic Regression**

Final Performance

| Metric | Score |
|---------|-------|
| Accuracy | **73.88%** |
| Precision | **50.52%** |
| Recall | **78.61%** |
| F1 Score | **61.51%** |
| ROC-AUC | **84.19%** |

The final model was selected based on its balance between predictive performance, interpretability, and business applicability.

---

# 💼 Business Decision Support System

The predictive model was transformed into a decision support framework by assigning customers to risk categories based on predicted churn probability.

| Risk Level | Business Action |
|------------|----------------|
| 🟢 Low | Routine Monitoring |
| 🟡 Medium | Promotional Campaign |
| 🟠 High | Personalized Retention Offer |
| 🔴 Very High | Immediate Retention Intervention |

This enables telecom companies to prioritize customer retention activities and allocate resources efficiently.

---

# 📊 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Matplotlib
- Seaborn
- Google Colab

---

# 📈 Project Highlights

✔ End-to-end machine learning pipeline

✔ Business-oriented feature engineering

✔ Feature selection and multicollinearity analysis

✔ Class imbalance treatment

✔ Threshold optimization

✔ Business decision support system

✔ Executive risk segmentation dashboard

---

# 🚀 Future Improvements

Potential extensions include:

- Explainable AI (SHAP)
- Deep Learning models
- Survival Analysis for churn prediction
- Real-time deployment using Streamlit or FastAPI
- Integration with CRM systems

---

# 👤 Author

**Razan Abdallah**

Bachelor of Computer Science with a Minor in Statistics

Aspiring Machine Learning Engineer and Data Scientist

Areas of Interest

Data Science
Machine Learning
Artificial Intelligence
Predictive Analytics
Research Engineering


---

# ⭐ Repository

If you found this project interesting, feel free to star the repository and connect with me.
