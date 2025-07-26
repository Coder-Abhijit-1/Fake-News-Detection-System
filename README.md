# 📰 Fake News Detection System using NLP & Machine Learning

This project is a **Fake News Detection System** that uses **Natural Language Processing (NLP)** and **Machine Learning** techniques to classify whether a given news article is **REAL** or **FAKE**.

---

## 🚀 Project Overview

With the rise of misinformation on the internet, the need for an automated system to detect fake news has become critical. This project demonstrates how we can train a machine learning model using a labeled dataset to distinguish between real and fake news headlines and articles.

---

## 🛠️ Tech Stack

- **Programming Language:** Python  
- **Libraries Used:**
  - `pandas`, `numpy`
  - `sklearn` (CountVectorizer, PassiveAggressiveClassifier, train_test_split)
  - `nltk` for text preprocessing
  - `re`, `string` for text cleaning  
- **Dataset:** `news.csv` (from Kaggle or any reliable fake/real news dataset)

---

## ⚙️ How It Works

1. **Data Loading:**  
   Reads the dataset containing labeled fake and real news.

2. **Data Cleaning:**  
   Preprocesses the text – lowercasing, punctuation removal, stopword filtering, etc.

3. **Feature Extraction:**  
   Converts text into numerical vectors using `CountVectorizer`.

4. **Model Training:**  
   Trains a `PassiveAggressiveClassifier` on the cleaned and vectorized data.

5. **Prediction:**  
   Takes new news input and predicts whether it is real or fake.

---

## 📈 Accuracy

The current model achieves around **95%+ accuracy** on the test dataset.  
Performance may vary depending on the size and quality of the dataset used.

---

## 🧠 Future Improvements

- Replace `CountVectorizer` with `TfidfVectorizer` for better text weighting.
- Build a web interface using **Flask** or **Streamlit**.
- Integrate advanced NLP models like **BERT** or **RoBERTa**.
- Add support for **multilingual fake news detection**.

---

## 👩‍💻 Author

**Abhijit Mondal**  
Final Year B.Tech Student, MAKAUT  
Aspiring Data Scientist | Machine Learning Enthusiast

---

> ⭐️ If you like this project, feel free to fork it, improve it, and ⭐️ star it!
