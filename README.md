# RAG PDF Chatbot using LangChain and FAISS

## Overview

This project demonstrates a simple Retrieval-Augmented Generation (RAG) pipeline using Python, LangChain, Hugging Face embeddings, and FAISS. The chatbot retrieves the most relevant information from a PDF document based on the user's question.

The project uses semantic search to find the most relevant text chunks from the document, making it useful for document-based question answering.

---

## Features

- Load PDF documents
- Split text into smaller chunks
- Generate embeddings using Hugging Face Sentence Transformers
- Store embeddings in a FAISS vector database
- Retrieve the most relevant document chunks based on user queries
- Interactive question-answer interface in Jupyter Notebook

---

## Technologies Used

- Python
- Jupyter Notebook
- LangChain
- Hugging Face Embeddings
- FAISS
- PyPDF
- Sentence Transformers

---



## Installation

Install the required libraries:

```bash
pip install langchain
pip install langchain-community
pip install langchain-text-splitters
pip install langchain-huggingface
pip install faiss-cpu
pip install sentence-transformers
pip install pypdf
```

---

## How to Run

1. Open the notebook in Jupyter Notebook.
2. Place `pythonlearn.pdf` in the project folder.
3. Run all notebook cells.
4. Enter a question related to the PDF.
5. The notebook retrieves the most relevant document sections.

---

## Workflow

```
PDF
   ↓
Load Document
   ↓
Split into Chunks
   ↓
Generate Embeddings
   ↓
Store in FAISS
   ↓
Retrieve Relevant Chunks
   ↓
Display Retrieved Information
```

---

## Sample Questions

- What is Python?
- What is a variable?
- Explain Python lists.
- What are functions?
- What are loops?

---

## Future Improvements

- Integrate a Large Language Model (LLM) for answer generation.
- Support multiple PDF documents.
- Develop a Streamlit web interface.
- Enable document upload through the user interface.

---

## Conclusion

This project demonstrates a basic Retrieval-Augmented Generation (RAG) workflow by combining document retrieval with semantic search. It highlights how FAISS and Hugging Face embeddings can efficiently locate relevant information from PDF documents, providing a strong foundation for building intelligent document-based chatbots.
