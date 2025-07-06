# 📰 Detecting Political Bias in Indian News Media using MiniLM

This project demonstrates how to detect political bias in Indian news articles using natural language processing and a fine-tuned transformer model (MiniLM). The goal is to analyze how different media outlets may exhibit ideological leaning — left, center, or right — based on the language used in headlines and descriptions.

[👉 View Full Colab Notebook](https://colab.research.google.com/drive/1Ms4h9XcNMvgWfW9fiB7LaNgC-BANWNG6?usp=sharing)

---

## 📌 Project Highlights

- ✅ Cleaned and analyzed real-world news data with labeled bias
- ✅ Visualized bias distribution and text characteristics
- ✅ Fine-tuned `MiniLM-L12-H384-uncased` for multi-class classification
- ✅ Evaluated with confusion matrix, classification report, and training loss curve
- ✅ Project designed to showcase skills in **data analytics + applied NLP**

---

## 📊 Dataset Overview

The dataset consists of Indian news articles with the following fields:

- `title`: News headline
- `description`: Short article summary
- `published_date`: Date of publication
- `source`: News outlet
- `bias_text`: Human-annotated political bias (`left`, `center`, `right`)

---

## 🧠 Model Training

- Model used: `microsoft/MiniLM-L12-H384-uncased`
- Tokenization: Hugging Face `AutoTokenizer`
- Trainer API: For training, evaluation, and logging
- Label Encoding: `left = 0`, `center = 1`, `right = 2`

---

## 📈 Visualizations

- 📊 Bias distribution bar chart
- 📉 Training loss curve (shows learning progress)

---

## 🔧 Tools Used

- Python, Pandas, NumPy, Matplotlib, Seaborn
- Hugging Face Transformers + Datasets
- Scikit-learn for evaluation metrics
- Google Colab for training and experimentation

---


