# Multipdf Chatbot

A simple chatbot application that lets you upload multiple PDF documents and interact with them using natural language queries. Built with **LangChain**, **Google Gemini Flash**, and **Streamlit**.

---

## ✨ Features

* 📄 Upload and parse multiple PDF files
* 🔎 Ask natural language questions about the documents
* ⚡ Uses **Google Generative AI (Gemini Flash 2.5)** for fast responses
* 🧠 Vector store–powered retrieval for accurate context
* 🌐 Streamlit UI for an interactive experience

---

## 🚀 Installation

### 1. Clone the repository

```bash
git clone https://github.com/Srinivas-2410/pdf_chatbot.git
cd pdf_chatbot
```

### 2. Create and activate a virtual environment

```bash
python -m venv venv
source venv/bin/activate   # On macOS/Linux
venv\Scripts\activate      # On Windows
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

---

## ⚙️ Configuration

### Set your Google API key as an environment variable

```bash
# macOS/Linux
export GOOGLE_API_KEY="your_api_key_here"

# Windows (PowerShell)
setx GOOGLE_API_KEY "your_api_key_here"
```

---

## ▶️ Usage

### Run the Streamlit app

```bash
streamlit run app.py
```

### Access the app

Open the app in your browser at:
[http://localhost:8501](http://localhost:8501)

---

## 📂 Project Structure

```plaintext
multipdf_chatbot/
│── app.py                # Main Streamlit app
│── requirements.txt      # Python dependencies
│── .gitignore            # Git ignore file
│── README.md             # Project documentation
│── venv/                 # Virtual environment (excluded from Git)
```

---

## 📦 Requirements

* Python 3.10+
* Streamlit
* LangChain
* PyPDF2
* FAISS
* Google Generative AI SDK

---
