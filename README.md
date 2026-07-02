#  Customer Churn Prediction using Machine Learning

##  Project Overview

This project predicts whether a telecom customer is likely to churn using Machine Learning techniques. The project includes data preprocessing, exploratory data analysis (EDA), statistical testing, feature engineering, class imbalance handling using SMOTE, model building, evaluation, and business recommendations.

The objective is to help telecom companies identify customers at risk of leaving and take proactive retention measures.

---

##  Features

- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Chi-Square Statistical Testing
- Feature Engineering
- One-Hot Encoding
- Handling Imbalanced Data using SMOTE
- Logistic Regression Model
- Random Forest Classifier
- Model Comparison
- Confusion Matrix
- ROC Curve & AUC Score
- Feature Importance Analysis
- Business Recommendations
- Future Scope

---

## 📂 Project Structure

```
Customer-Churn-Prediction/
│
├── data/
│   └── telecom_churn.csv
│
├── notebooks/
│   └── Customer_Churn_Prediction.ipynb
│
├── images/
│   ├── churn_distribution.png
│   ├── correlation_heatmap.png
│   ├── monthly_charges.png
│   ├── contract_vs_churn.png
│   ├── confusion_matrix.png
│   ├── roc_curve.png
│   └── feature_importance.png
│
├── report/
│   └── Customer_Churn_Report.pdf
│
├── requirements.txt
│
└── README.md
```

---

##  Dataset

The dataset contains customer information including:

- Demographic Details
- Contract Type
- Internet Services
- Payment Method
- Monthly Charges
- Total Charges
- Customer Tenure
- Churn Status

Target Variable:

**Churn**
- Yes
- No

---

##  Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- imbalanced-learn (SMOTE)
- SciPy

---

##  Exploratory Data Analysis

The project includes visualizations such as:

- Customer Churn Distribution
- Correlation Heatmap
- Monthly Charges Distribution
- Contract Type vs Churn
- Feature Importance
- Confusion Matrix
- ROC Curve

---

##  Machine Learning Models

| Model | Description |
|-------|-------------|
| Logistic Regression | Baseline classification model |
| Random Forest | Ensemble learning model |
| Logistic Regression + SMOTE | Handles class imbalance |
| Random Forest + SMOTE | Improved minority class prediction |

---

##  Model Evaluation

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix

The best-performing model was selected based on overall predictive performance.

---

##  Business Recommendations

- Improve customer retention strategies for month-to-month contract customers.
- Encourage long-term contracts through loyalty benefits.
- Promote technical support services.
- Monitor customers with high monthly charges.
- Develop personalized retention campaigns for high-risk customers.

---

##  Future Scope

- Hyperparameter tuning
- XGBoost implementation
- LightGBM implementation
- Real-time prediction dashboard
- Deployment using Flask or Streamlit
- Deep Learning models

---


GitHub: https://github.com/anjaliprasad831-droid

