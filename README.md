# 📰 Fake News Classifier using Simple RNN vs Bidirectional RNN

This project implements a **Fake News Detection** system using Deep Learning. It compares the performance of a **Simple RNN** and a **Bidirectional RNN** on classifying news articles as either **real** or **fake**.

---

## 🧠 Project Overview

Fake news spreads rapidly on the internet, making automatic detection essential. In this project, we:

- Built a text classification pipeline.
- Preprocessed and vectorized the dataset.
- Trained and evaluated two models:
  - Simple RNN
  - Bidirectional RNN
- Compared their performance using accuracy, precision, recall, and F1-score.

---

## 🗃️ Dataset

- **Source**: [Kaggle – Fake and Real News Dataset](https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset)
- **Columns Used**:
  - `text` – Full text of the article
  - `label` – Target label (1 = Fake, 0 = Real)

---

## 🔧 Technologies Used

- **Programming Language**: Python
- **Libraries**:
  - `pandas`, `numpy` – Data processing
  - `matplotlib`, `seaborn` – Visualization
  - `nltk`, `re` – Text preprocessing
  - `tensorflow`, `keras` – Model building and training

---

## ⚙️ Project Workflow

### 1. Data Cleaning & Preprocessing
- Lowercased the text
- Removed punctuation, numbers, and stopwords
- Tokenized and padded sequences with word2vec Embedding technique.

### 2. Text Vectorization
Used Word2vec Embedding techiniqe `to convert words to sequences with a fixed length`.

### 3. Model Architectures


