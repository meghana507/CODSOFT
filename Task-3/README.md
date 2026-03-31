# Task 3: Customer Churn Prediction

## Task Description
Predict which customers are likely to leave (churn) a subscription-based service or business.  
The goal is to help companies take proactive steps to retain customers and reduce churn rates.

---

## Dataset
The dataset contains historical customer data including demographics, usage patterns, and subscription details.

- **Source:** [Insert dataset link or reference]  
- **Columns (examples):**  
  - `CustomerID`: Unique customer identifier  
  - `Gender`: Customer gender  
  - `Age`: Customer age  
  - `Tenure`: How long the customer has been with the service  
  - `Usage`: Usage patterns (calls, transactions, etc.)  
  - `SubscriptionType`: Type of subscription  
  - `Churn`: Target variable (0 = retained, 1 = churned)  
- **Size:** Number of rows and columns (e.g., 5,000 customers, 10 features)  
- **Location:** `dataset/` folder  

> ⚠️ Tip: If dataset is large, provide a download link instead of uploading directly.

---

## Approach / Techniques
1. **Data Preprocessing:** Handle missing values, encode categorical variables, scale numerical features.  
2. **Exploratory Data Analysis (EDA):** Analyze patterns and correlations affecting churn.  
3. **Model Selection:** Logistic Regression, Random Forest, Gradient Boosting, XGBoost.  
4. **Model Evaluation:** Accuracy, Precision, Recall, F1-score, ROC-AUC.  
5. **Optimization:** Hyperparameter tuning to improve predictive performance.

---

## Files
- `churn_prediction_model.ipynb` - Jupyter Notebook with code, training, and evaluation.  
- `dataset/` - Folder containing the dataset (or download link).  
- `README.md` - This file.

---

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/CODSOFT.git
