
# 🧑‍⚖️ Wakeel.AI– Indian Legal Chat Assistant

LawBot is an AI-powered chatbot that answers questions about **Indian laws**. It leverages state-of-the-art language models fine-tuned on legal datasets to provide fast, accurate, and contextual answers based on Indian legal statutes and court rulings.

---

## 🚀 Features

- ⚖️ Understands and answers questions about Indian law  
- 💬 Interactive chat interface with natural language processing  
- 🧠 Powered by the **LLaMA 3.3 8B** model fine-tuned using **QLoRA**  
- 🔍 Optional RAG setup using **ChromaDB** or **FAISS** for enhanced retrieval  
---

## 📦 Dataset

- Includes various Indian legal topics such as:
  - IPC (Indian Penal Code)
  - CrPC
  - Constitution
  - Civil and Criminal law
  - Case summaries and interpretations

---

## 🛠️ Setup & Installation

### 1. Clone the Repository

```bash
https://github.com/Rickyy-Sam07/wakeel_V1.git
cd wakeel_V1
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Model Training (QLoRA on Google Colab)

- Follow the notebook
- Uses PEFT + QLoRA for low-RAM training
- Model: `LLaMA 3.3 8B`
- Trained on Google Colab (T4/L4 GPU)

### 4. Retrieval Augmented Generation (Optional)

Set up ChromaDB/FAISS to enhance response quality with real-time document retrieval:

```bash
# Example ChromaDB setup
pip install chromadb
# Preprocess and embed documents
```

---

## 🖥️ Running the Bot Locally

```bash
python wakeel_v1.py
```

- Access at `http://localhost:8000`
- Interactive chat powered by FastAPI/Streamlit (depending on your frontend)

---

## 🌐 Deployment

- Easily deploy on platforms like **Render**, **Vercel**, or **Hugging Face Spaces**
- [Optional] Docker support (add `Dockerfile` if needed)

---

## 🧠 Tech Stack

- **Python** (FastAPI / Streamlit)
- **Transformers**, **PEFT**, **QLoRA**
- **ChromaDB / FAISS** (for RAG)
- **Google Colab** (training)

---

## 📄 Example Questions

- *What is IPC Section 302?*  
- *Can a minor be arrested under Indian law?*  
- *What are the fundamental rights under Article 21?*

---

## 📢 Disclaimer

> **wakeel.ai is for informational purposes only and should not be used as a substitute for professional legal advice.**

---

## 🙌 Demo

> **here is a demo video of out 1st version of our waakel.ai : **



https://github.com/user-attachments/assets/8873b6cf-6a7b-40f2-80e5-2345e1f0d576



## 🧑‍💻 Author

**Sambhranta Ghosh**  
AI Enthusiast | LegalTech | Open Source Contributor

---
