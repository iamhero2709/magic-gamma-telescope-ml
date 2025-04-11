# 🚀 MAGIC Gamma Telescope - Machine Learning Project

![GitHub last commit](https://img.shields.io/github/last-commit/yourusername/magic-gamma-telescope-ml) 
![GitHub stars](https://img.shields.io/github/stars/yourusername/magic-gamma-telescope-ml?style=social)

## 📌 Overview
This project classifies **gamma particles** vs **hadron particles** using the MAGIC Gamma Telescope dataset.  
We compare 4 ML models: **KNN, Naive Bayes, Logistic Regression, SVM** and a **Neural Network**.

## 🛠️ Installation
1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/magic-gamma-telescope-ml.git
 2.Install dependencies:
 ```bash
    pip install numpy pandas scikit-learn imbalanced-learn tensorflow matplotlib
```
##.📊 Dataset
Source: UCI ML Repo - MAGIC Gamma Telescope

Features: fLength, fWidth, fSize, etc. (10 total)

Target: class (Gamma=1, Hadron=0)

🧮 Models Used
Model	Accuracy	Precision	Recall
KNN	0.83	0.82	0.89
Logistic Regression	0.81	0.80	0.85
Neural Network	0.85	0.84	0.87
🎯 Results
Best model: Neural Network (85% Accuracy)

Confusion Matrix:
Confusion Matrix (optional)

▶️ How to Run
Open in Google Colab: Open In Colab

Click "Run All" (Runtime → Run all)

🤝 Contribution
Contributions welcome! Open an Issue or Pull Request.
