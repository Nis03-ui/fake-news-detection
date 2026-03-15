
# Fake News Detection using NLP and Machine Learning

## 📌 Project Overview

This project builds a **Fake News Detection System** using **Natural Language Processing (NLP)** and **Machine Learning** techniques.
The model analyzes news articles and predicts whether the news is **real or fake**.

The system processes raw news text, performs text preprocessing, converts text into numerical features, and then trains a classification model to detect fake news.

---

## 🚀 Features

* Text preprocessing pipeline
* Stopword removal, tokenization, and lemmatization
* TF-IDF feature extraction
* Machine learning classification model
* Performance evaluation using accuracy, precision, recall, and F1-score

---

## 📊 Dataset
Dataset from kaggle=https://www.kaggle.com/datasets/abaghyangor/fake-news-dataset

The dataset contains two CSV files:

* **Fake.csv** – Fake news articles
* **True.csv** – Real news articles

Each dataset contains the following columns:

* `title` – Title of the news article
* `text` – Full article content
* `subject` – Category of the article
* `date` – Publication date

---

## ⚙️ Technologies Used

* Python
* Pandas
* NLTK
* Scikit-learn
* Jupyter Notebook

---

## 🧠 NLP Pipeline

The following preprocessing steps were applied:

1. Combine `title` and `text`
2. Convert text to lowercase
3. Remove punctuation and special characters
4. Tokenization
5. Stopword removal
6. Lemmatization
7. TF-IDF vectorization

Pipeline:

Raw Text → Cleaning → Tokenization → Stopword Removal → Lemmatization → TF-IDF → Machine Learning Model

---

## 📈 Model Performance

Confusion Matrix:

[[4636   78]
[  62 4204]]

Classification Report:

Precision | Recall | F1 Score

Fake News (0)
Precision: 0.99
Recall: 0.98
F1-score: 0.99

Real News (1)
Precision: 0.98
Recall: 0.99
F1-score: 0.98

Overall Accuracy: **98.44%**

---

## 🏗 Project Structure

```
fake-news-detection/
│
├── Fake.csv
├── True.csv
├── news_detector.ipynb
├── main.py
└── README.md
```

---

## ▶️ How to Run the Project

1. Clone the repository

```
git clone https://github.com/your-username/fake-news-detection.git
```

2. Install dependencies

```
pip install pandas nltk scikit-learn
```

3. Run the notebook

```
jupyter notebook news_detector.ipynb
```

---

## 🎯 Future Improvements

* Deploy the model as a web app
* Add real-time news prediction
* Compare multiple machine learning models
* Visualize important features and word clouds

---

## 👨‍💻 Author
Nishan Bhandari
---

## ⭐ If you like this project

Give it a star on GitHub!
