<h1 align="center">🧠 Dark Pattern Buster – AI/ML Module</h1>

<p align="center">

  <img src="https://img.shields.io/badge/Python-3.10-blue" />
  <img src="https://img.shields.io/badge/NLP-Text_Classification-green" />
  <img src="https://img.shields.io/badge/License-MIT-lightgrey" />
</p>

---

## 🎯 Overview

Welcome to my **self-built AI/ML backend** for the **Dark Pattern Buster** project — a tool designed to detect deceptive UI/UX elements in e-commerce platforms. This repo showcases my independent learning and development of the **AI-powered text classifier**.

> ⚠️ This is not the full original repo. Inspired by *Ecommerce Sevak (IIT Bhilai)*’s Dark Pattern Buster, this is my **personal AI/ML module** developed for learning and showcasing NLP model deployment.

---

## 🚀 Features

✨ Classifies user interface texts (e.g., "Only 1 left!") into dark pattern types  
🧠 Built using **Python + Flask + Scikit-learn**  
📜 Processes text via **NLP (TF-IDF, tokenization)**  
🔗 REST API for real-time classification  
🔍 Planned: LLM prompt analysis of privacy policy text (via LLaMA/OpenAI)

---

## 🛠️ Tech Stack

| Area            | Tools Used                         |
|-----------------|------------------------------------|
| 👨‍💻 Language     | Python, JavaScript (future UI)     |
| 📦 Backend API   | Flask                              |
| 🤖 ML/NLP        | Scikit-learn, TF-IDF, Logistic Reg |
| 📊 Analytics     | F1-Score, Precision, Recall         |
| 🧠 Future AI     | LLaMA / OpenAI prompting (privacy) |

---

## 🧪 Sample Input & Output

### 📨 Request (to `/predict`)
```json
{
  "text": "Only 2 items left in stock! Hurry!"
}
📤 Response
json

{
  "label": "Urgency Pattern"
}
🧠 Learning Objectives

📚 Understand NLP preprocessing (stopwords, tokenization, TF-IDF)

🧠 Train and evaluate ML models for text classification

🔌 Expose model via Flask API

🔍 Explore ethical implications of dark UX design

💬 Practice LLM-based privacy policy analysis

📦 Project Structure

dark-pattern-buster-aiml/
│
├── app.py                 # Flask backend
├── model/train_model.py   # ML training script
├── utils/preprocess.py    # Text preprocessing
├── data/dataset.csv       # Training data
├── requirements.txt
└── README.md
🖥️ Setup Instructions

git clone https://github.com/Mgaul6/dark-pattern-buster-aiml.git
cd dark-pattern-buster-aiml
pip install -r requirements.txt
python app.py


📖 Inspired by Deceptive Patterns
