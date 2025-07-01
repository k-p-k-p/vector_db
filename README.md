# 🔍 RAG with Groq + LangChain + ChromaDB

This project implements a **Retrieval-Augmented Generation (RAG)** pipeline using:

- 💬 [Groq](https://groq.com/) — fast inference with LLaMA or Gemma
- 🧠 LangChain — document parsing, chunking, and chaining
- 📄 Local PDFs — user-loaded documents
- 🧷 ChromaDB — local vector store for embeddings

---

## 📁 Folder Structure

vector_db/ <br>
├── notebook.ipynb # Main Jupyter notebook with code <br>
├── docs/ # Your local PDFs <br>
├── vector_store/ # Chroma vector storage (auto-generated) <br>
├── .env # API key (not included in repo) <br>
├── .gitignore <br>
├── requirements.txt <br>
└── README.md


---

## 🚀 How to Run

1. **Clone the repo**

```git clone https://github.com/your-username/vector_db.git```<br>
```cd vector_db ```

3. **Install dependencies**

```pip install -r requirements.txt```

3. **Add your Groq API key**

Create a .env file with:

```GROQ_API_KEY=your_api_key_here```

4. **Add your PDFs to the docs/ folder.**

Open the notebook
Run `notebook.ipynb` in Jupyter and follow the steps.
