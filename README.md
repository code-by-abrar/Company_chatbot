# 🤖 Enterprise RAG Chatbot 
An end-to-end, cost-effective Retrieval-Augmented Generation (RAG) AI Chatbot. This project ingests complete websites, vectorizes the knowledge, and serves a beautifully designed, modern UI to answer user queries with high accuracy. 

Built specifically to utilize high-performance, free-tier developer tools like **Groq (Llama 3)** and **FireCrawl**, ensuring a zero-to-low cost deployment architecture while maintaining enterprise-grade accuracy.

---

## ✨ Features

* **Advanced Web Scraping:** Uses the FireCrawl API to bypass JavaScript/Security blocks and extract clean Markdown from complex dynamic websites.
* **Ultra-Fast LLM Inference:** Powered by Groq's LPU and `llama-3.3-70b-versatile` for lightning-fast, high-quality responses.
* **Local Vector Database:** Integrates ChromaDB with HuggingFace embeddings (`all-MiniLM-L6-v2`) for efficient, secure, and local semantic search.
* **Modern Frontend:** A beautiful, responsive split-screen UI built with HTML/CSS/JS. Features include markdown parsing, animated typing indicators, and floating UI elements.
* **Robust Backend:** Built with FastAPI for high performance and easy API endpoint management.

---

## 🛠️ Tech Stack

### Backend & AI
* **Framework:** Python, FastAPI, Uvicorn
* **LLM & Orchestration:** LangChain, Groq API (`llama-3.3-70b-versatile`)
* **Embeddings:** HuggingFace (`sentence-transformers/all-MiniLM-L6-v2`)
* **Vector Store:** ChromaDB
* **Data Ingestion:** FireCrawl API, BeautifulSoup4

### Frontend
* **Core:** HTML5, CSS3, Vanilla JavaScript
* **Libraries:** Marked.js (Markdown rendering), FontAwesome (Icons)
* **Fonts:** Google Fonts (Poppins)

