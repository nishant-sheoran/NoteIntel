# NoteIntel

## 📌 Overview
This project implements a **Deep Learning-based Fake Banknote Detection System** using an **Artificial Neural Network (ANN)**. It aims to distinguish between genuine and counterfeit banknotes based on extracted image features. The model is trained on a publicly available **Banknote Authentication Dataset**, making it a robust solution for real-world currency authentication.

## 🎯 Objective
The primary goal of this project is to develop an efficient and accurate model that classifies banknotes as **real** or **fake** based on numerical features extracted from images.

## 📂 Dataset Information
- The dataset consists of **features extracted from banknote images** captured using industrial-grade cameras.
- **Features Used:**
  - **VWTI**: Variance of Wavelet Transformed Image
  - **SWTI**: Skewness of Wavelet Transformed Image
  - **CWTI**: Curtosis of Wavelet Transformed Image
  - **EI**: Entropy of Image
  - **Class**: 1 (Genuine), 0 (Forged)
- Dataset Source: [Banknote Authentication Dataset](https://www.kaggle.com/datasets/gauravduttakiit/banknote/data?select=train.csv)

## 🛠 Project Workflow
1️⃣ **Data Preprocessing** – Load dataset, handle missing values, and apply feature scaling.
2️⃣ **Model Training** – Implement a deep learning ANN for classification.
3️⃣ **Evaluation** – Measure accuracy, precision, recall, and F1-score.
4️⃣ **Prediction System** – Develop a function for real-time predictions.

## 🚀 Model Performance
The ANN model achieves **high accuracy (~99-100%)**, demonstrating its effectiveness in counterfeit detection. Performance metrics:
- **Accuracy**: 99-100%
- **Precision**: ~99%
- **Recall**: ~100%
- **F1-Score**: ~99%

## 📖 Usage Guide
### 1️⃣ Setup Environment
```bash
pip install -r requirements.txt
```
### 2️⃣ Run the Training Script
```bash
python train.py
```
### 3️⃣ Make Predictions
Use the provided function to classify new banknotes as **real** or **fake**.

## 🔮 Future Enhancements
This project will be **integrated into a real-world ATM security system**, forming a part of **CashSentinel**—a smart ATM security project:
- **🔗 Integration with Java-based ATM Simulator** ([Trinity-Rich-Bank](https://github.com/nishant-sheoran/Trinity-Rich-Bank))
- **🤖 AI-powered Fraud Detection** with real-time REST API communication.
- **🛡 Enhanced Security** for banking transactions using Deep Learning.
- **🔍 Smart ATMs** that detect counterfeit cash before processing transactions.

> **CashSentinel GitHub Repository:** [CashSentinel](https://github.com/nishant-sheoran/CashSentinel)

## 🤝 Contributing
We welcome contributions! 🚀 If you want to contribute:
1. **Fork the repository**
2. **Create a new branch** (`feature-new-improvement`)
3. **Make your changes** and **commit**
4. **Submit a Pull Request (PR)** with a brief description

## 📜 License
This project is open-source and available under the **MIT License**.

---

📌 **Author:** [Nishant Sheoran](https://github.com/nishant-sheoran)  
If you find this project useful, **give it a ⭐ on GitHub!**


