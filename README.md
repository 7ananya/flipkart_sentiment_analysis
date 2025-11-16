# Flipkart Product Reviews Sentiment Analysis (NLP)

This project analyzes customer sentiments from Flipkart product reviews using Natural Language Processing (NLP) and Machine Learning.

## Project Overview
- Cleaned and preprocessed ~190K Flipkart product reviews
- Performed lemmatization, stopword removal, and text normalization
- Vectorized text using TF-IDF (1–2 grams)
- Built and compared Logistic Regression and SVM models
- Achieved **93% accuracy** and **macro F1-score of 0.86** on balanced data

## Tech Stack
- Python, Pandas, NumPy
- Scikit-learn, NLTK, Seaborn, WordCloud, imbalanced-learn

## Model Comparison
| Model | Accuracy | Macro F1 | Notes |
|--------|-----------|-----------|-------|
| Logistic Regression | 0.96 | 0.91 | High precision, imbalanced |
| SVM (Oversampled) | 0.93 | 0.86 | More balanced & realistic |

## Visualizations
- Sentiment distribution
- WordClouds for positive/negative reviews
- Review length and rating distribution
- Confusion matrix

## Future Improvements
- Fine-tune with BERT / Transformers
- Build a Streamlit-based web app
- Use topic modeling for deeper insights


