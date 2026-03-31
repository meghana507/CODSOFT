# Task 1: Movie Genre Classification
## Task Description
Predict the genre(s) of a movie based on its plot summary or other textual information. 
The goal is to build a machine learning model that can classify movies into genres such as Action, Comedy, Drama, etc.
## Dataset
The dataset contains movie titles, plot summaries, and their corresponding genres.  
- **Source:** [Dataset Link or reference]  
- **Columns:** 
  - `Title`: Movie title
  - `Plot`: Summary of the movie plot
  - `Genre`: Target label(s)
- **Size:** Number of rows, examples of entries
- **Location:** `dataset/` folder
- ## Approach
1. Preprocessing text data (cleaning, removing stopwords, tokenization)
2. Feature extraction using TF-IDF / Word Embeddings
3. Model selection: Naive Bayes, Logistic Regression, or SVM
4. Model training and evaluation using accuracy, precision, recall
5. ### **7. Results / Observations** 
```markdown
## Results
- Accuracy: 85%
- Precision, Recall, F1-score: [values]
- Observations: The model performs better for genres with more examples; multi-genre prediction may require advanced techniques.
