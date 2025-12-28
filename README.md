# Customer Churn Prediction Project

## Project Overview
Telecom companies lose millions of dollars every year due to customer churn (customers leaving the service). Acquiring new customers is five times more expensive than retaining existing ones.

**Goal:** Predict which customers are likely to churn so that the company can proactively offer discounts, promotions, or better services to retain them.

**Problem Statement:**
- **Input:** Customer data including demographic and usage information  
- **Output:** Prediction of churn (`YES` for churned, `NO` for retained)

---

## Dataset Details
| Feature | Description |
|---------|-------------|
| Dataset Name | Telco Customer Churn Prediction |
| Source | Kaggle |
| Size | 7043 customer records (rows) & 21 features (columns) |
| Target Variable | Churn: YES (customer left) / NO (customer retained) |

---

## Group Member Roles
| Member ID | Role |
|-----------|------|
| IT24102374 | Data Cleaning (handle missing/duplicate values, correct data types) |
| IT24101376 | Encoding categorical variables |
| **IT24101551** | **Outlier Removal (my contribution)** |
| IT24101536 | Normalization/Scaling |
| IT24101325 | Feature Selection |
| IT24101520 | Dimensionality Reduction |

---

## My Contribution (IT24101551)
- Implemented **outlier detection and removal** to improve dataset quality  
- Verified dataset integrity after outlier removal  
- Assisted in preprocessing for ML model training  

> This section highlights my individual contribution for portfolio and academic purposes.

---

## Key Features
- Data cleaning, preprocessing, and feature engineering  
- Implemented multiple ML models:  
  - Logistic Regression  
  - K-Nearest Neighbors (KNN)  
  - Support Vector Machine (SVM)  
  - Random Forest  
  - Gradient Boosting (best model, F1 Score = 0.62)  
  - Neural Network  
- PCA for dimensionality reduction  
- Evaluated model performance using F1-Score, Recall, and AUC-ROC  
- Addressed class imbalance and ensured fairness in evaluation  

---


pip install pandas numpy scikit-learn matplotlib seaborn

