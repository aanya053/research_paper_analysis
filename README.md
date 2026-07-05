# 📚 ResearchLens AI

ResearchLens AI is an AI-powered research paper search system that enables semantic retrieval of Machine Learning research papers from the ArXiv dataset. It leverages transformer-based embeddings, vector similarity search, AI-powered summarization, and keyword extraction to help users quickly discover and understand relevant research papers.

---

## 🚀 Features

- 🔍 Semantic search using Sentence Transformers
- ⚡ Fast vector similarity search with FAISS
- 🤖 AI-generated paper summaries using BART
- 🏷️ Automatic keyword extraction using KeyBERT
- 📄 Compare research papers using semantic similarity
- 🧠 LangChain tool integration for research paper retrieval
- 📚 Search across 15,000+ Machine Learning research papers from ArXiv

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Hugging Face Datasets
- Sentence Transformers
- FAISS
- Hugging Face Transformers
- KeyBERT
- LangChain
- Scikit-learn

---

## 📂 Project Workflow

1. Load the ArXiv Machine Learning Papers dataset from Hugging Face.
2. Preprocess research paper titles and abstracts.
3. Generate sentence embeddings using **all-MiniLM-L6-v2**.
4. Build a FAISS vector index for efficient semantic retrieval.
5. Search papers based on semantic similarity.
6. Generate concise summaries using **facebook/bart-large-cnn**.
7. Extract important keywords using **KeyBERT**.
8. Compare research papers based on semantic similarity, summaries, and extracted keywords.
9. Expose semantic search functionality as a LangChain tool.

---

## 🤖 Models Used

### Embedding Model
- all-MiniLM-L6-v2

### Summarization Model
- facebook/bart-large-cnn

### Keyword Extraction
- KeyBERT

---

## 📊 Dataset

- **Dataset:** CShorten/ML-ArXiv-Papers
- **Source:** Hugging Face Datasets
- **Subset Used:** First 15,000 research papers

---

## 📁 Project Structure

```
ResearchLens_AI.ipynb
├── Dataset Loading
├── Data Preprocessing
├── Embedding Generation
├── FAISS Index Creation
├── Semantic Search
├── AI Summarization
├── Keyword Extraction
├── LangChain Tool
└── Paper Comparison
```

---

## ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/yourusername/ResearchLens-AI.git
```

Navigate to the project

```bash
cd ResearchLens-AI
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Notebook

Launch Jupyter Notebook or Google Colab and execute all cells in:

```
ResearchLens_AI.ipynb
```

---

## 📈 Future Improvements

- Hybrid Search (Semantic + TF-IDF)
- Streamlit Web Application
- Research Paper Recommendations
- Search Filters
- Export Search Results
- Research Chat Assistant
- PDF Upload & Analysis

---

## 👩‍💻 Author

**Aanya Mahajan**

Computer Science Engineering Student

Interested in Artificial Intelligence, Machine Learning, NLP, and Full-Stack Development.

---

## 📄 License

This project is intended for educational and learning purposes.
