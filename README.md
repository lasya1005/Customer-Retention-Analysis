# Customer Churn Prediction

## Overview
Customer churn is a major challenge for businesses, especially in the telecom sector. This project applies machine learning techniques to predict customer churn based on demographic details, account information, and service subscriptions. The goal is to help businesses identify at-risk customers and take proactive measures to improve retention.

## Dataset
The dataset used in this project contains:
- **Demographics**: Age, Gender, etc.
- **Account Information**: Tenure, Monthly Charges, Total Charges
- **Services Subscribed**: Internet Service, Contract Type, Payment Method
- **Target Variable**: `Churn` (Yes/No)

## Features & Implementation
### **1️⃣ Data Preprocessing**
- Converted `TotalCharges` to numeric and handled missing values
- Encoded categorical variables using `LabelEncoder`
- Standardized numerical variables using `StandardScaler`

### **2️⃣ Model Training & Evaluation**
Trained six machine learning models:
- **Logistic Regression**
- **Decision Tree**
- **Random Forest**
- **Support Vector Classifier (SVC)**
- **K-Nearest Neighbors (KNN)**
- **AdaBoost Classifier**

**Evaluation Metrics Used:**
- Accuracy
- Precision
- Recall
- F1-Score
- AUC-ROC Curve

### **3️⃣ Results & Insights**
- **Best Model**: Random Forest (85% Accuracy)
- **Key Findings**:
  - Customers with long tenure have lower churn rates.
  - Month-to-month contracts and high monthly charges contribute significantly to churn.

### **4️⃣ Visualization**
- Bar chart comparison of model performances
- ROC curves for top models
- Sample customer prediction result

## Predicting New Customer Churn
The model can predict whether a new customer is likely to churn. Example output:
```
Prediction: Churn
Probability of Churn: 0.65
```

## How to Run
1. **Clone the repository**:
   ```bash
   git clone https://github.com/lasya1005/Customer-Retention-Analysis.git
   ```
2. **Navigate to the directory**:
   ```bash
   cd Customer-Retention-Analysis
   ```
3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```
4. **Run the Jupyter Notebook**:
   ```bash
   jupyter notebook
   ```

## Files in Repository
- `Cust_Churn_Pred.ipynb` → Jupyter Notebook with code
- `Customer-Churn.csv` → Dataset used for training
- `README.md` → Project documentation (this file)

## Future Improvements
- Hyperparameter tuning for better model performance
- Exploring deep learning approaches
- Deploying the model as a web application

---
📌 **Author:** Lasya G
🔗 **GitHub:** [lasya1005](https://github.com/lasya1005)

