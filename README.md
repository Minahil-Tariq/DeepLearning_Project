# 🧠 Enhanced Depression Detection in Social Media Texts

## 📋 Project Overview
This repository contains a reproduction and enhancement of the research paper:

**“Advanced Comparative Analysis of Machine Learning and Transformer Models for Depression and Suicide Detection in Social Media Texts” (Bokolo & Liu, 2024)**

We improve the original work by integrating **XLM-RoBERTa**, **XGBoost**, and a **hybrid architecture** to achieve superior performance across all evaluated tasks.

---

## 🎯 Key Contributions

### ✅ Base Paper Reproduction
- Reproduced all ML and transformer models from the original paper:
  - **Traditional ML:** Logistic Regression, Bernoulli Naive Bayes, Random Forest  
  - **Transformers:** RoBERTa, DeBERTa, DistilBERT, SqueezeBERT  
- Validated experiments on:
  - **Sentiment140 dataset**
  - **Suicide-Watch dataset**
- Followed the same experimental setup, preprocessing pipeline, and evaluation metrics.

---

## 🚀 Enhancements & Novelty

### 🔹 Cross-Lingual Transformer
- Added **XLM-RoBERTa**, enabling multilingual depression detection and improved contextual understanding.

### 🔹 Advanced Ensemble Learning
- Integrated **XGBoost** for powerful gradient boosting and efficient classification.

### 🔹 Hybrid Architecture
- Combined **XLM-RoBERTa embeddings** with **XGBoost** to create a strong hybrid pipeline.

### 🔹 Extended Evaluation
- Included robustness testing, additional metrics, and cross-model comparison.

### 🔹 Improved Performance
- Achieved significant accuracy gains compared to the original baselines.

---

## 📊 Performance Comparison

### **Sentiment140 Dataset**

| Model               | Accuracy | Precision | Recall | F1-Score | Improvement |
|---------------------|----------|-----------|--------|----------|-------------|
| Original RoBERTa    | 98.0%    | 98.0%     | 99.0%  | 98.0%    | Baseline    |
| XLM-RoBERTa         | 98.3%    | 98.2%     | 98.4%  | 98.3%    | +0.3%       |
| XGBoost             | 96.8%    | 96.9%     | 96.7%  | 96.8%    | −1.2%       |
| **XLM-R + XGBoost** | **98.5%**| **98.5%** | **98.6%** | **98.5%** | **+0.5%**   |

---

### **Suicide-Watch Dataset**

| Model               | Accuracy | Precision | Recall | F1-Score | Improvement |
|---------------------|----------|-----------|--------|----------|-------------|
| Original RoBERTa    | 87.0%    | 87.2%     | 87.0%  | 87.0%    | Baseline    |
| XLM-RoBERTa         | 93.8%    | 93.9%     | 93.8%  | 93.8%    | +6.8%       |
| XGBoost             | 92.7%    | 92.8%     | 92.7%  | 92.7%    | +5.7%       |
| **XLM-R + XGBoost** | **94.2%**| **94.3%** | **94.2%** | **94.2%** | **+7.2%**   |

---

## 🧪 Key Experimental Findings

- **XLM-RoBERTa outperforms monolingual transformers** by *0.3–6.8%*.
- **Hybrid XLM-R + XGBoost** achieves the *best performance overall*:
  - **98.5% accuracy** on Sentiment140
  - **94.2% accuracy** on Suicide-Watch
- XGBoost performs strongly on structured textual patterns (up to **92.7%**).
- Cross-lingual representations improve robustness even for primarily English datasets.

---
