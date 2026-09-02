# 🔮 Autocomplete and Autocorrect Data Analytics

## 📌 Project Overview

This project analyzes the efficiency and accuracy of Autocomplete and Autocorrect algorithms using Natural Language Processing (NLP) techniques.

The project implements multiple approaches for next-word prediction and spelling correction using a real-world text corpus. The performance of different algorithms is evaluated using metrics such as Accuracy, Precision, and Recall.

---

## 🎯 Objectives

- Analyze a large text corpus using NLP techniques.
- Perform text preprocessing including tokenization, lowercasing, punctuation removal, and stopword removal.
- Build frequency-based Bigram and Trigram models for autocomplete prediction.
- Test autocomplete predictions using multiple input prefixes.
- Implement autocorrect using PySpellChecker.
- Implement a custom autocorrect approach using Levenshtein Edit Distance.
- Test spelling correction on deliberately misspelled words.
- Evaluate algorithms using Accuracy, Precision, and Recall.
- Compare multiple autocomplete and autocorrect approaches.
- Visualize word frequency and algorithm performance.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NLTK
- PySpellChecker
- TextDistance
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## 📖 Dataset

The text corpus used in this project is:

**Alice's Adventures in Wonderland**

Source: Project Gutenberg

The corpus is used for:

- Text preprocessing
- Word frequency analysis
- Bigram generation
- Trigram generation
- Autocomplete prediction

---

## 🔄 NLP Preprocessing

The following preprocessing techniques were applied:

- Converting text to lowercase
- Removing punctuation and special characters
- Tokenization
- Stopword removal
- Vocabulary creation

---

# 🔮 Autocomplete Implementation

## 1. Bigram Model

A Bigram model uses one previous word to predict the next word.

Example:

```text
alice → was
was → beginning
beginning → to