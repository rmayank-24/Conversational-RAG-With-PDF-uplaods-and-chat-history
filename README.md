# Conversational-RAG-With-PDF-uplaods-and-chat-history

# 🧠 Conversational RAG with PDF Uploads and Chat History

A powerful, easy-to-use **Conversational RAG (Retrieval-Augmented Generation)** Streamlit web app that allows users to **upload PDFs** and **chat with the content**, while preserving **chat history across sessions**.

Built with **LangChain**, **Groq (Gemma 2)**, **HuggingFace Embeddings**, and **ChromaDB**, this project enables context-aware Q&A over custom documents using the latest LLMs.

---

## 🔥 Features

- 📄 Upload one or multiple PDF files.
- 🤖 Ask natural language questions about the content.
- 🧠 Uses **history-aware retriever** to maintain chat context.
- 🗂 Session-based persistent chat memory.
- 💬 Backed by **Groq's blazing-fast LLMs** (e.g., Gemma 2 9B).
- 🧩 Embeddings via HuggingFace (MiniLM).
- 🏪 Vector store powered by ChromaDB.
- 🌐 Deploy-ready for Streamlit Cloud.

---

## 🚀 Demo

👉 **Live App**: [Streamlit App](https://conversational-rag-with-pdf-uplaods-and-chat-history.streamlit.app)

---

## 🛠 Tech Stack

- **Frontend**: [Streamlit](https://streamlit.io/)
- **LLM**: [Groq API](https://console.groq.com/)
- **Embedding Model**: `all-MiniLM-L6-v2` (HuggingFace)
- **Vector Store**: ChromaDB
- **Document Parsing**: PyMuPDF via `langchain_community.document_loaders`
- **Session Memory**: LangChain's `ChatMessageHistory`
- **Prompt Engineering**: LangChain's `ChatPromptTemplate`

---

## 📦 Installation (Local)

### 1. Clone the Repo
```bash
git clone https://github.com/your-username/conversational-rag-with-pdf-uplaods-and-chat-history.git
cd conversational-rag-with-pdf-uplaods-and-chat-history


python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
HF_TOKEN=your_huggingface_token_here
