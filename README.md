# 🤖 RAG-Based PDF Chatbot

A modern **Retrieval-Augmented Generation (RAG)** chatbot that allows users to upload PDF documents and interact with them using natural language.  
The system retrieves relevant document context using **FAISS vector search** and generates grounded answers using **Google Gemini LLM**.

---

## ✨ Features

- 📄 PDF upload support (single document)
- ✂️ Intelligent text chunking with overlap
- 🧠 Semantic search using HuggingFace embeddings
- 🔍 FAISS-powered vector retrieval
- 💬 Context-aware chatbot (RAG)
- 🕘 Persistent chat history (session-based)
- ⚡ Fast inference with Gemini Flash Lite
- 🔐 Secure API key handling via `.env`

---

## 🏗️ System Architecture

<img width="231" height="550" alt="image" src="https://github.com/user-attachments/assets/271c5dd3-d2bc-47ea-acf5-b7cbfcea45f7" />


---

## 🧰 Tech Stack

- **Frontend:** Streamlit  
- **LLM:** Google Gemini (`gemini-2.5-flash-lite`)  
- **Embeddings:** HuggingFace `all-MiniLM-L6-v2`  
- **Vector DB:** FAISS  
- **Frameworks:** LangChain, PyPDF  
- **Language:** Python  

---

## 📂 Project Structure

<img width="238" height="178" alt="image" src="https://github.com/user-attachments/assets/7698bd9f-c5d4-4108-84cf-8a309b8e4f58" />

---

## ⚙️ Installation

```bash
git clone https://github.com/your-username/rag-pdf-chatbot.git
cd rag-pdf-chatbot
pip install -r requirements.txt
GOOGLE_API_KEY=your_api_key_here
streamlit run app.py
http://localhost:8501
