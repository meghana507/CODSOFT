# Task 4: Spam SMS Detection

## Task Description
Classify SMS messages as **spam** or **legitimate** using machine learning.  
The goal is to build a model that can automatically filter out spam messages to improve communication efficiency.

---

## Dataset
The dataset contains SMS messages labeled as spam or ham (legitimate).

- **Source:** [Insert dataset link or reference]  
- **Columns:**  
  - `Label` – Target variable (spam or ham)  
  - `Message` – Text content of the SMS  
- **Size:** Number of rows (e.g., 5,574 messages)  
- **Location:** `dataset/` folder  

> ⚠️ Tip: For large datasets, provide a download link instead of uploading the full CSV to GitHub.

---

## Approach / Techniques
1. **Data Preprocessing:** Clean text, remove punctuation, lowercase, remove stopwords, tokenization.  
2. **Feature Extraction:** TF-IDF or word embeddings to convert text into numerical features.  
3. **Model Selection:** Naive Bayes, Logistic Regression, or Support Vector Machines (SVM).  
4. **Model Evaluation:** Accuracy, Precision, Recall, F1-score.  
5. **Optimization:** Experiment with hyperparameters or text preprocessing methods for better performance.

---

## Files
- `spam_detection_model.ipynb` – Notebook with code, training, and evaluation.  
- `dataset/` – Folder containing dataset or download link.  
- `README.md` – This file.

---

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/CODSOFT.git
