# IMDB Sentiment Analysis using Recurrent Neural Network (RNN)

## 📌 Project Overview
This project focuses on **Sentiment Analysis** of movie reviews using a **Recurrent Neural Network (RNN)** model.

The goal is to classify IMDB reviews as **positive** or **negative** by applying deep learning techniques along with comprehensive **Natural Language Processing (NLP)** preprocessing steps.

---

## 📊 Dataset
The dataset used is the **IMDB Movie Reviews Dataset**, which contains:

- 50,000 movie reviews
- Binary sentiment labels:
  - Positive
  - Negative

 This dataset available on Kaggle:

👉 https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews


---

## 🧹 Text Preprocessing

To improve model performance, several NLP preprocessing techniques were applied:

- Lowercasing text
- Tokenization
- Stopword removal
- Punctuation removal
- Stemming
- TF-IDF Vectorization

These steps help in converting raw text into meaningful numerical features.

---

## ⚙️ Technologies Used

- Python
- NumPy
- Pandas
- Scikit-learn
- Pytorch
- NLTK
- Matplotlib

---

## 🧠 Model Architecture

The RNN model includes:

- Input Layer (TF-IDF feature vectors)
- Recurrent Layer (SimpleRNN / LSTM)
- Dense Layers
- Sigmoid Output Layer (Binary Classification)

---

## 🔄 Project Workflow

1. Data Loading
2. Text Cleaning & Preprocessing
3. Feature Extraction using TF-IDF
4. Train/Test Split
5. RNN Model Building
6. Model Training
7. Model Evaluation

---

## 📈 Model Performance

The model is evaluated using:

- Accuracy Score
- Confusion Matrix

The RNN model achieves strong performance in classifying sentiments of movie reviews.

---

## 🚀 Future Improvements

- Use Word Embeddings (Word2Vec / GloVe)
- Replace RNN with LSTM / GRU
- Hyperparameter tuning
- Deploy using Flask / FastAPI
- Build a web app for real-time sentiment prediction

---


