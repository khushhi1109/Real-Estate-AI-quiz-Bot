# 🏠 Real Estate AI Tutor (RAG-Based)

![AI](https://img.shields.io/badge/AI-RAG%20System-blueviolet?style=for-the-badge)
![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge\&logo=python\&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-Google%20AI-orange?style=for-the-badge\&logo=google\&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-Vector%20DB-black?style=for-the-badge)
![Streamlit](https://img.shields.io/badge/Streamlit-App-red?style=for-the-badge\&logo=streamlit\&logoColor=white)

---

## 📌 Overview

**Real Estate AI Tutor** is an AI-powered educational system designed to simulate real-world real estate decision-making scenarios.
It leverages **Retrieval-Augmented Generation (RAG)** to generate intelligent, scenario-based questions and provide adaptive explanations.

---

## 🚀 Features

* 🤖 AI-generated scenario-based questions
* 📊 Comparative risk analysis (legal, financial, zoning)
* 🧠 Adaptive learning based on user performance
* 🔍 Semantic search using vector embeddings
* 📈 Real-world property data reasoning

---

## 🧠 Tech Stack

* **Frontend:** Streamlit
* **LLM:** Google Gemini
* **Vector Database:** ChromaDB
* **Embeddings:** `models/gemini-embedding-001`
* **Language:** Python

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/khushii109/Real-Estate-AI-quiz-Bot.git
cd Real-Estate-AI-quiz-Bot
```

---

### 2️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

---

### 3️⃣ Configure API Key

Create a `.streamlit/secrets.toml` file and add your API key:

```toml
GEMINI_API_KEY = "your_api_key_here"
```

---

### 4️⃣ Run the application

```bash
streamlit run app.py
```

---

## 🌐 Application Access

Once the app is running, open:

```
http://localhost:8501
```

---

## 📂 Project Structure

```
├── app.py
├── src/
├── data/
├── requirements.txt
├── README.md
```

---

## 🔒 Security & Configuration

* API keys are managed securely using `.streamlit/secrets.toml`
* Sensitive files are excluded via `.gitignore`
* Follow best practices to avoid exposing credentials in public repositories

---

## ✨ Author

**Khushi**

---

## ⭐ Future Improvements

* Advanced analytics dashboard
* Expanded real estate datasets
* Multi-user support system

---
