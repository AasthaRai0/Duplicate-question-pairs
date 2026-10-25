# Duplicate Question Pairs Detection 🔍

An end-to-end Machine Learning and Natural Language Processing (NLP) pipeline built to detect duplicate question pairs, inspired by the classic **Quora Question Pairs** dataset challenge.

---

## 📁 Project Structure

```text
Dup-ques-pairs/
│
├── train.csv                      # Dataset containing question pairs and target labels
├── initial_EDA.ipynb              # Exploratory Data Analysis (EDA) on text lengths and patterns
├── only-bow.ipynb                 # Baseline model using Bag of Words (BoW)
├── bow_features.ipynb             # Feature extraction using tokenizers and vectorizers
├── bow_advanced_features.ipynb    # Advanced feature engineering (FuzzyWuzzy ratios, token distances)
├── cv.pkl                         # Saved CountVectorizer model
├── model.pkl                      # Trained Machine Learning classifier
└── README.md                      # Project documentation