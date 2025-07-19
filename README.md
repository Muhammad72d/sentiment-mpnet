
#  Sentiment Classification Using MPNet Embeddings

This project builds a binary sentiment classifier for English tweets using **pre-trained sentence embeddings (MPNet)and a custom feedforward neural network.

> Final validation accuracy: **~79%**

---

## 📌 Overview

- 💬 **Data**: English tweets (cleaned and preprocessed).
- 🔤 **Text Representation**: Sentence embeddings from [`all-mpnet-base-v2`](https://huggingface.co/sentence-transformers/all-mpnet-base-v2).
- 🧠 **Model**: Deep Neural Network (Dense layers with Dropout and BatchNormalization).
- 🎯 **Task**: Binary classification (positive or negative sentiment).

---

## 🧪 Results

| Metric         | Value     |
|----------------|-----------|
| Train Accuracy | ~78%      |
| Val Accuracy   | ~79%      |
| Loss Function  | Binary Crossentropy |
| Optimizer      | Adam (lr=2e-5)      |

The model shows stable training with no major overfitting observed.

---


