Project Title: NLP Text Classification - Social Media Sentiment Analysis
Dataset: Social media posts with text and sentiment labels (Positive, Negative, Neutral, some 'Happy').
Objective: Classify text into sentiment categories using NLP techniques.
Key Steps & Insights:

Cleaning: Removed noise (URLs, mentions, special chars), standardized 'Happy' as 'Positive'.
Preprocessing: Stop words removal, lemmatization (using NLTK).
EDA: Sentiment distribution and word clouds (Positive dominant, themes like gratitude, activities).
Feature Extraction:
TF-IDF (term importance)
Word2Vec (semantic embeddings)

Modeling: Naive Bayes (fast for text), Logistic Regression (strong baseline), Random Forest (on embeddings).
Evaluation: Precision, Recall, F1-score (weighted) — high performance (~0.90+).
Best Model: Usually Logistic Regression on TF-IDF.

Conclusion: The model accurately classifies sentiment with robust preprocessing. TF-IDF + Logistic Regression is efficient and effective for this task.
