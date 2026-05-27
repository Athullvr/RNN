# 🎬 Movie Review Sentiment Analysis using RNN

This project uses a Recurrent Neural Network (RNN) to classify IMDb movie reviews as **positive** or **negative**.

The model is trained using the IMDb Movie Review Dataset and implemented using deep learning techniques for Natural Language Processing (NLP).

---

## 📌 Project Overview

Sentiment analysis is a Natural Language Processing (NLP) task used to determine whether a piece of text expresses a positive or negative opinion.

In this project:

- IMDb movie reviews are used as input
- Text data is preprocessed and tokenized
- Reviews are converted into numerical sequences
- An RNN model is trained for binary sentiment classification
- The model predicts whether a review is:
  - ✅ Positive
  - ❌ Negative

---

## 🧠 Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

---

## 📂 Dataset

Dataset Used: IMDb Movie Reviews Dataset

The dataset contains:
- 50,000 movie reviews
- Binary sentiment labels:
  - Positive
  - Negative

Dataset Source:
https://ai.stanford.edu/~amaas/data/sentiment/

---

## ⚙️ Model Architecture

The RNN model includes:

1. Embedding Layer
2. Simple RNN Layer
3. Dense Output Layer
4. Sigmoid Activation Function

---

## 🚀 How to Run

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Athullvr/RNN.git
cd RNN
