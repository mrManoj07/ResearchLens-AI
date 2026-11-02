# ResearchLens AI 🔍

An AI-powered Research Paper Question Answering System that allows users to upload PDF research papers and ask questions in natural language. It uses Retrieval-Augmented Generation (RAG) to retrieve relevant information and generate context-aware answers.

## 🚀 Features

- Upload research papers in PDF format.
- Extract and process PDF text.
- Split documents into overlapping text chunks.
- Generate semantic embeddings using Sentence Transformers.
- Perform similarity search using FAISS.
- Generate context-aware answers using Llama 3.2 through Ollama.
- Display retrieved source page references.
- Interactive web interface built with Gradio.
- Run AI models locally using Ollama.

## 🛠️ Tech Stack

- Python
- Jupyter Notebook
- PyMuPDF
- Sentence Transformers
- FAISS
- Ollama
- Llama 3.2
- Gradio
- NumPy

## ⚙️ How It Works

1. Upload a research paper in PDF format.
2. Extract text from the PDF.
3. Split text into smaller overlapping chunks.
4. Generate embeddings using Sentence Transformers.
5. Store embeddings in a FAISS vector index.
6. Retrieve relevant passages based on the user's question.
7. Generate answers using a locally running Llama 3.2 model.
8. Display answers with retrieved source page references through Gradio.

## 💻 Requirements

- Python 3.10+
- Ollama
- Llama 3.2 model
- Required Python libraries

## 📦 Installation

Install the required Python libraries:

```bash
pip install -r requirements.txt
```

Download the Llama 3.2 model:

```bash
ollama pull llama3.2:3b
```

## ▶️ Run Locally

1. Install Python dependencies.
2. Install and start Ollama.
3. Download the Llama 3.2 model.
4. Open `ResearchLens_AI.ipynb` in Jupyter Notebook.
5. Run the notebook cells in sequence.
6. Launch the Gradio interface.
7. Upload a research paper PDF and start asking questions.

## 📁 Project Structure

```text
ResearchLens-AI/
│
├── ResearchLens_AI.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

## 🔮 Future Improvements

- Improve retrieval accuracy.
- Add more accurate source citations.
- Support multiple research papers.
- Improve the user interface.
- Add chat history and conversation memory.

## 👨‍💻 Author

**Manoj**

GitHub: [@mrManoj07](https://github.com/mrManoj07)

---

⭐ If you find this project useful, consider giving it a star!
