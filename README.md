# music-genre-classification
Deep learning project to classify music genres using CNN and Mel spectrograms

# 🎶 Music Genre Classification using CNN

This project implements a deep learning pipeline to classify music clips into genres using Mel Spectrograms and Convolutional Neural Networks (CNN). Developed and run on Google Colab.

---

## 📌 Overview

- 🔊 **Dataset**: [GTZAN 10-second clips](https://huggingface.co/datasets/Feanix/gtzan-10-sec)
- 🧠 **Model**: Custom CNN trained on Mel Spectrograms
- 🎯 **Test Accuracy**: 80.9%
- ⚙️ **Platform**: Google Colab

---

## 🚀 Quick Start

Click below to open the notebook in Colab:
https://colab.research.google.com/drive/16wB8il6JJbhWD0ybFU3NEJueG3H1qCQh?usp=sharing

---

## 🛠️ Tech Stack

- Python
- TensorFlow / Keras
- Librosa (audio preprocessing)
- HuggingFace Datasets
- NumPy, Matplotlib, Scikit-learn

---

## 🧪 Steps Performed

1. Loaded audio dataset from HuggingFace.
2. Converted audio into Mel Spectrograms.
3. Preprocessed and split data into training, validation, and test sets.
4. Built and trained a CNN model.
5. Evaluated performance on test data.

---

## 📊 Results

Test Accuracy: 80.94%

---

pip install -r requirements.txt
