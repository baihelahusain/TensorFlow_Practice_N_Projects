# 📘 Deep Learning Projects – NLP & Time Series Forecasting  

![Python](https://img.shields.io/badge/Python-3.12+-blue.svg)  
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange.svg)  
![NLP](https://img.shields.io/badge/NLP-Natural%20Language%20Processing-green.svg)  

This repository contains two major **Deep Learning** projects implemented in **TensorFlow/Keras**, demonstrating practical skills in **Natural Language Processing (NLP)** and **Time Series Forecasting**.  

---

## 🚀 Projects Overview  

### 1️⃣ SkimLit – NLP for Medical Abstracts  
- **Goal**: Classify sentences from **PubMed medical abstracts** into categories (*Objective, Methods, Results, Conclusions*).  
- **Techniques Used**:  
  - Text preprocessing: tokenization, embeddings, padding.  
  - Architectures: Conv1D, LSTM, GRU, and Transformer-based models.  
  - Pretrained embeddings + attention mechanisms.  
- **Results**:  
  - ✅ Accuracy: **82.83%**  
  - 📉 Loss: **0.9459**  
- **Impact**: Automates biomedical text classification, inspired by the *PubMed 200k RCT* dataset.  

---

### 2️⃣ Time Series Forecasting with TensorFlow  
- **Goal**: Forecast future values in **time-series datasets**.  
- **Techniques Used**:  
  - Data windowing & horizon strategies.  
  - Deep learning models: Dense, CNN, LSTM/RNN.  
  - Optimization: early stopping, learning rate scheduling.  
  - Evaluation: MAE, MSE + forecast visualizations.  
- **Results**:  
  - Achieved **low MAE/MSE compared to naive baselines**.  
- **Impact**: Demonstrates ability to solve real-world forecasting problems with neural networks.  

---

## 🛠️ Tech Stack  
- **Programming Language**: Python  
- **Libraries**: TensorFlow/Keras, NumPy, Pandas, Matplotlib, Scikit-learn  

---

## 📂 Repository Structure  
├── 09_SkimLit_nlp_milestone_project_2.ipynb # NLP for Medical Abstracts
└── README.md # Project Documentation

- Biomedical **text classification** with NLP and deep learning.  
- Time-series **forecasting pipelines** with Dense, CNN, and LSTM models.  
- Performance optimization using callbacks & hyperparameter tuning.  
- Leveraging TensorFlow/Keras for **end-to-end ML development**.

## 📌 How to Run  
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/deep-learning-projects.git

   cd deep-learning-projects
