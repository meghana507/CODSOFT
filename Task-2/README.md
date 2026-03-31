# Task 2: Credit Card Fraud Detection

## Task Description
Detect fraudulent credit card transactions using machine learning. 
The goal is to build a model that can classify transactions as **legitimate** or **fraudulent**, helping businesses reduce financial losses.

---

## Dataset
The dataset contains credit card transaction details and labels indicating whether a transaction is fraudulent.

- **Source:** [Insert dataset link or reference]  
- **Columns:**  
  - `Time`: Seconds elapsed between this transaction and the first transaction in the dataset  
  - `V1` to `V28`: PCA-transformed anonymized features  
  - `Amount`: Transaction amount  
  - `Class`: Target variable (0 = legitimate, 1 = fraud)  
- **Size:** Number of rows (e.g., 284,807 transactions)  
- **Location:** `dataset/` folder  

> ⚠️ Tip: For large datasets, include a download link instead of uploading the full CSV to GitHub.

---

## Approach / Techniques
1. **Data Preprocessing**: Handle class imbalance, normalize the `Amount` column, split into train/test sets.  
2. **Model Selection**: Logistic Regression, Decision Trees, Random Forests, or Gradient Boosting.  
3. **Model Evaluation**: Accuracy is not enough due to imbalance; use Precision, Recall, F1-score, and ROC-AUC.  
4. **Optimization**: Use techniques like SMOTE or class weighting for better fraud detection performance.

---

## Files
- `fraud_detection_model.ipynb` - Jupyter Notebook containing code, model training, and evaluation.  
- `dataset/` - Folder containing the dataset (or download link).  
- `README.md` - This file.

---

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/CODSOFT.git
