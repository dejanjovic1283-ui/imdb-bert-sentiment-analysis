# 🎬 IMDB BERT Sentiment Analysis

This project demonstrates transformer-based sentiment analysis using a fine-tuned DistilBERT model on the IMDB dataset.

It was developed in Google Colab using Hugging Face Transformers and PyTorch.

---

## 🚀 Project Overview

The goal of this project is to classify movie reviews as **positive** or **negative** using a transformer-based deep learning model.

This workflow includes:
- loading the IMDB dataset
- tokenization with DistilBERT tokenizer
- fine-tuning a pretrained transformer model
- evaluation on a test subset
- saving the trained model
- inference on new custom reviews

---

## 🧠 Model

- Base model: `distilbert-base-uncased`
- Task: Binary sentiment classification
- Framework: Hugging Face Transformers
- Environment: Google Colab (T4 GPU)

---

## 📊 Results

Evaluation result on the test subset:

- Accuracy: **0.888**
- Evaluation loss: **0.3876**

---

## 🛠️ Technologies Used

- Python
- PyTorch
- Hugging Face Transformers
- Datasets
- Evaluate
- Google Colab

---

## 📁 Files

- `imdb_bert_sentiment_analysis.ipynb`

---

## 👨‍💻 Author

**Dejan Jović**
