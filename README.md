# Regional Classification of Turkish Folk Songs (NLP Project)

## Problem Definition
This project builds a Natural Language Processing (NLP) model to predict the geographical origin of Turkish folk songs based on their lyrics.

Due to the agglutinative structure of Turkish and regional dialect variations, the project evaluates multiple linguistic levels:

- Lexical features (words)
- Syntactic features (bigrams)
- Semantic filtering (content vs stopwords)
- Morphological features (character n-grams)

Advanced methods such as TF-IDF and Byte-Pair Encoding (BPE) are also tested.

---

## Team Structure

### Cüneyt Küçük
- Data collection and preprocessing
- Text normalization (RegEx, Turkish case handling)
- Dataset balancing (macro-region mapping)
- Train/test splitting and evaluation reporting

### İbrahim Faruk Ceylan
- Model development and pipeline design
- TF-IDF and BPE implementation
- Naive Bayes and classification models
- Evaluation metrics (Precision, Recall, F1-score)

---

## Files

- `README.md` → Project documentation
- `Türkü_Region_Classifier_Final_Project.ipynb` → Main code notebook
- `turkish_folk_songs.csv` → Dataset

---

## How to Run

1. Place dataset in the same folder as notebook
2. Open Jupyter Notebook
3. Run all cells sequentially
4. Install dependencies if required (NLTK, tokenizers)

---

## Features

- Turkish NLP preprocessing
- TF-IDF vectorization
- Byte-Pair Encoding (BPE)
- Machine learning classification
- Interactive prediction system  
