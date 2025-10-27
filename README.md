# DistilBERT Emotion Classifier

This project fine-tunes **DistilBERT**, a lightweight transformer model by HuggingFace, to classify emotions from text using the **dair-ai/emotion** dataset. It can detect emotions such as **joy, sadness, anger, fear, love, and surprise** from a given sentence.

---

## 📌 Features

- Uses **DistilBERT (Transformer-based model)**
- Trained on **Emotion Dataset (HuggingFace)**
- **Multi-class Emotion Classification**
- Fine-tuning using **HuggingFace Trainer API**
- High accuracy with minimal training time
- Supports custom text emotion prediction

---

## 📂 Dataset

- **Name:** `dair-ai/emotion`
- **Source:** HuggingFace Datasets
- **Labels:** `anger, disgust, fear, joy, neutral, sadness, surprise`

---

## 🧠 Model Architecture

- **Base Model:** `distilbert-base-uncased`
- **Tokenizer:** DistilBERT Tokenizer
- **Frameworks & Libraries:**  
  `transformers`, `datasets`, `torch`, `numpy`, `pandas`

---

## 🛠️ Installation

```bash
pip install transformers datasets torch umap-learn bertviz

---

**🚀 Training the Model**

The notebook contains all steps:

Load dataset
Preprocess labels
Tokenize data
Fine-tune DistilBERT
Evaluate model
Run predictions

---

**Prediction Example**
text = "I am so happy today!"
predict(text)

Output:
joy
