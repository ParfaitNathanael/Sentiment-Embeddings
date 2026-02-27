<p align="center">
  <img src="images/Project_Banner.png" alt="Project Banner" width="80%" style="max-width: 1000px;"/>
</p>

<h1 align="center">🐦 Twitter Sentiment Analysis using MiniLM Embeddings 🚀</h1>

<p align="center">
  <a href="#">
    <img src="https://img.shields.io/badge/Python-3.8%2B-blue" alt="Python">
  </a>
  <a href="#">
    <img src="https://img.shields.io/badge/License-MIT-green" alt="License">
  </a>
  <a href="https://github.com/m1n1v1rus/Sentiment-Embeddings/stargazers">
    <img src="https://img.shields.io/github/stars/m1n1v1rus/Sentiment-Embeddings" alt="Stars">
  </a>
</p>


[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/16x54MsCTOh3wqDIc3v9aS4fzghPs5xLd)

## 📌 Project Overview
Twitter sentiment analysis using **all-MiniLM-L6-v2** sentence embeddings. This project compares multiple machine learning models for sentiment classification (positive, negative, neutral) and includes comprehensive visualizations.

## ✨ Features
- **Text Preprocessing** - Complete tweet cleaning pipeline
- **Sentence Embeddings** - Using all-MiniLM-L6-v2 (384-dim vectors)
- **4 Classification Models** - Logistic Regression, XGBoost, SVM, Random Forest
- **Cosine Similarity Analysis** - Embedding space visualization
- **2D Visualization** - UMAP dimensionality reduction
- **Custom Predictions** - Test with your own tweets

## 📊 Results
| Model | Accuracy | F1-Score |
|-------|----------|----------|
| SVM (RBF) | 68.20% | 0.684 |
| Logistic Regression | 66.40% | 0.663 |
| XGBoost | 63.50% | 0.637 |
| Random Forest | 61.80% | 0.618 |

## 🖼️ Visualizations

### Sentiment Distribution
![sentiment distribution](images/sentiment_distribution.png)

### Confusion Matrix (SVM - Best Model)
![confusion matrix](images/confusion_matrix.png)

### Model Comparison
![model comparison](images/model_comparison.png)

### Word Clouds
![wordclouds](images/wordclouds.png)

### Cosine Similarity Between Classes
![cosine similarity](images/cosine_similarity.png)

### Tweet Length Analysis
![text analysis](images/text_length_analysis.png)

## 🛠️ Tech Stack
- Python 3.x
- sentence-transformers
- scikit-learn
- XGBoost
- UMAP
- matplotlib, seaborn

---
## 🤝 Contributing

All contributions are welcome — bug fixes, feature enhancements, or documentation improvements!

Please give appropriate credit to the original author if you use or modify this tool in your own projects.

---

## 📜 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

## 👤 Author

**Ayush Mani**  
🔗 GitHub: [@m1n1v1rus](https://github.com/m1n1v1rus)

---


## 🚀 Quick Start
```bash
# Clone repository
git clone https://github.com/m1n1v1rus/Sentiment-Embeddings-Project.git

# Install requirements
pip install -r requirements.txt

# Run notebook
jupyter notebook Sentiment_Embeddings_Project.ipynb
```
