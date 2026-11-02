# ResearchLens AI 🔍

An AI-powered Research Paper Question Answering System that allows users to upload PDF research papers and ask questions in natural language.

## 🚀 Features

- Upload research papers in PDF format.
- Extract and process PDF text.
- Split documents into overlapping text chunks.
- Generate semantic embeddings using Sentence Transformers.
- Perform similarity search using FAISS.
- Generate context-aware answers using Llama 3.2 through Ollama.
- Display retrieved source page references.
- Interactive web interface built with Gradio.

## 🛠️ Tech Stack

- Python
- Jupyter Notebook
- PyMuPDF
- Sentence Transformers
- FAISS
- Ollama
- Llama 3.2
- Gradio

## ⚙️ How It Works

1. Upload a research paper in PDF format.
2. Extract text from the PDF.
3. Split text into smaller chunks.
4. Generate embeddings using Sentence Transformers.
5. Store embeddings in a FAISS vector index.
6. Retrieve relevant passages based on the user's question.
7. Generate answers using a locally running Llama 3.2 model.
8. Display answers through the Gradio interface.

## 💻 Requirements

- Python 3.10+
- Ollama
- Llama 3.2 model
- Required Python libraries

## ▶️ Run Locally

Install dependencies:

```bash
pip install pymupdf sentence-transformers faiss-cpu gradio requests
```

Download the Llama model:

```bash
ollama pull llama3.2:3b
```

Start Ollama, open the Jupyter Notebook, and run the cells in sequence.

## 👨‍💻 Author

Developed as a Generative AI and RAG-based project.
