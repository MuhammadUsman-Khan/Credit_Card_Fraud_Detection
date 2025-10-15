# 💳 Credit Card Fraud Detection using ML Pipelines

[![Open in Colab](https://img.shields.io/badge/Open%20in-Colab-blue)](https://colab.research.google.com/drive/1e1wUMAa_XjjWywGgf0MqM7b1c7qCJ3xF?usp=sharing)  
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)]()  

---

## 📘 Project Overview

This project focuses on building a **machine learning pipeline** to detect **fraudulent credit card transactions**.  
The notebook automates the **data preprocessing**, **model training**, and **prediction** stages using the power of **Scikit-learn pipelines** ensuring clean, modular, and reproducible workflows.  

Unlike typical EDA-based projects, this implementation goes straight into **model development** and **evaluation**.

---

## 🧠 Objectives

- Develop a **machine learning pipeline** for fraud detection.  
- Handle **class imbalance** effectively.  
- Automate **data preprocessing** (scaling, transformation).  
- Train and evaluate a **classification model** for predicting fraudulent transactions.  
- Produce **reliable predictions** using a clean, production-ready structure.

---

## 📂 Repository Structure

Credit_Card_Fraud_Detection/

├── README.md

└── Credit_Card_Fraud_Detection.ipynb


---

## ⚙️ Technologies Used

- **Python 3.8+**  
- **Pandas**, **NumPy** — data manipulation  
- **Scikit-learn** — model building, pipelines, metrics  
- **Google Colab / Jupyter Notebook**

---

## 🔄 Workflow

1. **Import Required Libraries**  
2. **Load Dataset** (credit card transactions)  
3. **Split into Features & Target**  
4. **Train/Test Split**  
5. **Preprocessing Steps in Pipeline**  
   - Standard Scaling  
   - Simple Imputer  
6. **Model Definition & Pipeline Creation**  
   - e.g. Logistic Regression
7. **Model Training & Evaluation**  
   - Accuracy  
8. **Prediction on Test Data**

---

## 📊 Results (Sample Format)

| Metric | Score |
|:-------|:------:|
| Train Accuracy | 0.9992 |
| Test Accuracy | 0.9991 |

The model performs well in identifying fraudulent transactions while minimizing false positives.

---

## 🚀 How to Run

1. Clone the repository:
   
  ``` git clone https://github.com/MuhammadUsman-Khan/Credit_Card_Fraud_Detection.git ```
  

Open the notebook:

```
jupyter notebook Credit_Card_Fraud_Detection.ipynb
```
or
Open directly in Google Colab from the link above.

Run all cells sequentially to reproduce the results.

## 🤝 Contributing
Contributions of additional visualizations, code cleanup, or deeper analysis are welcome!

Fork this repository

Create a new branch (git checkout -b feature-branch)

Make your changes and commit them

Push to your fork and open a Pull Request
