# Task 1 – Movie Genre Classification 🎬

## 📌 Problem Statement
Build a machine learning model to classify movie genres based on their plot summaries.

## 📂 Dataset
- Source: Provided by CodSoft
- Format: `train_data.txt` with movie title, genre, and plot

## ⚙️ Approach
- TF-IDF for text vectorization
- Logistic Regression (with class_weight='balanced')
- Evaluated using accuracy and classification report

## 📊 Results
- Accuracy: 57.9%
- Best performance on: `documentary`, `drama`, `comedy`, `western`

## 🚀 How to Run
1. Upload `train_data.txt` in the notebook directory.
2. Run `movie_genre_classification.ipynb`

## 🙌 Output
> Sample prediction:  
> **Input:** A story about love, heartbreak, and healing.  
> **Predicted Genre:** Drama

## 🧠 Learnings
- Hands-on with NLP and multi-class classification
- Explored TF-IDF and model evaluation techniques
