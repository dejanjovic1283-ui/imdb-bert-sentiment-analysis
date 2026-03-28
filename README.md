![Python](https://img.shields.io/badge/Python-3.10-blue)
![PyTorch](https://img.shields.io/badge/PyTorch-DeepLearning-red)
![HuggingFace](https://img.shields.io/badge/HuggingFace-Transformers-yellow)
![NLP](https://img.shields.io/badge/NLP-SentimentAnalysis-green)

# 🎬 IMDB BERT Sentiment Analysis

🚀 Transformer-based NLP project using a fine-tuned DistilBERT model for movie review classification.

---

## 📌 Overview

This project demonstrates how to build a **state-of-the-art sentiment analysis system** using a pretrained transformer model from Hugging Face.

The model is fine-tuned on the IMDB dataset to classify reviews as:

- ✅ Positive
- ❌ Negative

---

## 🧠 Model

- Base model: `distilbert-base-uncased`
- Architecture: Transformer (BERT family)
- Task: Binary sentiment classification
- Framework: Hugging Face Transformers + PyTorch
- Environment: Google Colab (GPU - T4)

---

## ⚙️ Pipeline

The full NLP workflow includes:

1. Loading IMDB dataset
2. Text tokenization using DistilBERT tokenizer
3. Fine-tuning pretrained transformer model
4. Model evaluation on test subset
5. Saving trained model
6. Running inference on new reviews

---

## 📊 Results

| Metric          | Value     |
|----------------|----------|
| Accuracy       | **88.8%** |
| Eval Loss      | 0.3876   |

---

## 🧪 Example Predictions

```text
Review: This movie was fantastic and very emotional.
Prediction: Positive
Confidence: 98.99%

Review: I hated every second of this film.
Prediction: Negative
Confidence: 94.09%
🛠️ Tech Stack
Python
PyTorch
Hugging Face Transformers
Datasets
Evaluate
Google Colab
📁 Project Structure
imdb-bert-sentiment-analysis/
│
├── imdb_bert_sentiment_analysis.ipynb   # full training notebook
├── imdb_bert_sentiment_analysis.py      # script version
├── README.md
🚀 Future Improvements
Deploy as REST API (FastAPI)
Integrate into Streamlit web app
Add model monitoring & logging
Optimize inference speed
👨‍💻 Author

Dejan Jović

NLP • Machine Learning • Deep Learning

---



