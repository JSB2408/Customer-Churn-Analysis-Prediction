# 📊 Customer Churn Analysis & Prediction

> An end-to-end Data Analytics and Machine Learning project that analyzes customer behavior, identifies churn patterns, predicts customers likely to leave, and visualizes business insights using Power BI.

---

## 📌 Project Overview

Customer churn is one of the biggest challenges faced by subscription-based businesses such as telecom companies. Retaining existing customers is significantly more cost-effective than acquiring new ones.

This project aims to:

- Analyze customer behavior
- Identify the major reasons behind customer churn
- Build a Machine Learning model to predict churn
- Predict churn for new customers
- Create an interactive Power BI dashboard for business decision-making

---

# 📊 Dashboard Preview










# 🚀 Tech Stack

| Technology | Purpose |
|------------|---------|
| Python | Data Cleaning & Machine Learning |
| Pandas | Data Manipulation |
| NumPy | Numerical Computing |
| Scikit-Learn | Machine Learning |
| Random Forest | Churn Prediction |
| SQL | Data Extraction & Views |
| Excel | Data Storage |
| Power BI | Dashboard & Visualization |
| Matplotlib | Data Visualization |
| Seaborn | Exploratory Data Analysis |

---

# 📂 Project Workflow

```text
Customer Dataset
        │
        ▼
Data Cleaning & Preprocessing
        │
        ▼
Exploratory Data Analysis (EDA)
        │
        ▼
Feature Engineering
        │
        ▼
Label Encoding
        │
        ▼
Train-Test Split
        │
        ▼
Random Forest Classifier
        │
        ▼
Model Evaluation
        │
        ▼
Prediction on New Customers
        │
        ▼
Interactive Power BI Dashboard
```

---

# 📁 Dataset Features

The dataset contains customer demographic information, subscription details, and service usage.

Some important features include:

- Customer ID
- Age
- Gender
- State
- Tenure
- Internet Service
- Internet Type
- Contract Type
- Monthly Charges
- Total Charges
- Payment Method
- Premium Support
- Online Security
- Value Deal
- Customer Status (Target Variable)

---

# 🧹 Data Preprocessing

The following preprocessing steps were performed before model training:

- Removed unnecessary columns
- Removed data leakage columns
- Handled missing values
- Label Encoding for categorical variables
- Target Variable Encoding
- Feature Selection
- Train-Test Split (80:20)

---

# 🤖 Machine Learning Model

### Algorithm Used

**Random Forest Classifier**

### Why Random Forest?

- Handles mixed feature types efficiently
- Robust against overfitting
- High prediction accuracy
- Captures complex relationships
- Provides feature importance

---

# 📊 Model Evaluation

The model was evaluated using:

- Accuracy Score
- Precision
- Recall
- F1 Score
- Confusion Matrix
- Classification Report

---

# 🔮 Customer Churn Prediction Pipeline

The trained model predicts churn for newly joined customers.

### Prediction Workflow

```text
New Customer Data
        │
        ▼
Data Cleaning
        │
        ▼
Feature Encoding
        │
        ▼
Random Forest Model
        │
        ▼
Churn Prediction
        │
        ▼
Predictions.csv
```

---

# 📈 Power BI Dashboard

The Power BI dashboard provides interactive insights into customer behavior and churn.

### Dashboard Highlights

- Total Customers
- Churn Rate
- Revenue Analysis
- Customer Segmentation
- Contract Analysis
- Internet Service Analysis
- Payment Method Analysis
- State-wise Customer Distribution
- Customer Demographics
- Monthly Revenue Trends

---

# 📊 Business Insights

Some key insights discovered during the analysis:

- Customers with shorter tenure are more likely to churn.
- Month-to-Month contracts have higher churn rates than long-term contracts.
- Customers with higher monthly charges tend to churn more frequently.
- Internet service type influences customer retention.
- Premium support and value deals improve customer retention.
- Customer demographics and payment methods also impact churn behavior.

---

# 🎯 Business Value

This project helps businesses to:

- Identify customers at risk of churn
- Improve customer retention strategies
- Reduce revenue loss
- Improve marketing effectiveness
- Increase customer lifetime value

---

# 📌 Future Improvements

Future enhancements may include:

- XGBoost & LightGBM comparison
- Hyperparameter Tuning
- SHAP Explainability
- Streamlit Web Application
- Real-Time Prediction API
- Automated ETL Pipeline
- Cloud Deployment

---

# 📦 Requirements

```
pandas
numpy
matplotlib
seaborn
scikit-learn
openpyxl
joblib
jupyter
powerbi
```

---

# 🛠 Skills Demonstrated

- Data Cleaning
- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Feature Selection
- Machine Learning
- Random Forest Classification
- Model Evaluation
- SQL
- Excel
- Power BI
- Business Intelligence
- Predictive Analytics
- Data Visualization

---


# 📌 Repository Contents

| File | Description |
|------|-------------|
| Churn_analysis.ipynb | Complete Python notebook |
| Churn_Analysis.pbix | Power BI Dashboard |
| Predictions.csv | Predicted churn customers |
| README.md | Project Documentation |
| requirements.txt | Python Dependencies |

---

# ⭐ If you found this project useful, consider giving it a Star!
