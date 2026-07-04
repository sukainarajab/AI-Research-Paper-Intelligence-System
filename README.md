# AI Research Paper Intelligence System

An AI-powered Research Paper Intelligence System built using **Deep Learning** and **Natural Language Processing (NLP)**. This project enables users to search research papers semantically, generate concise summaries, extract key information, classify research domains, and answer questions based on the retrieved paper.

## Features

-  **Semantic Search**
  - Retrieves the most relevant research papers using Sentence Transformers and FAISS based on semantic similarity.

-  **Abstractive Summarization**
  - Generates concise summaries of research paper abstracts using the BART transformer model.

-  **Keyword Extraction**
  - Extracts the most important keywords and phrases using KeyBERT.

-  **Named Entity Recognition (NER)**
  - Identifies important entities such as organizations, people, locations, and technical terms using spaCy.

-  **Zero-Shot Topic Classification**
  - Classifies research papers into AI/ML domains without additional training using BART-MNLI.

- **Question Answering**
  - Allows users to ask questions related to the retrieved research paper and extracts answers using DistilBERT.

---

##  Tech Stack

- Python
- Pandas
- Sentence Transformers
- FAISS
- Hugging Face Transformers
- BART
- DistilBERT
- KeyBERT
- spaCy

---

## Workflow

1. Load the research paper dataset.
2. Generate embeddings using Sentence Transformers.
3. Perform semantic search with FAISS.
4. Retrieve the most relevant research paper.
5. Generate a summary using BART.
6. Extract keywords using KeyBERT.
7. Perform Named Entity Recognition using spaCy.
8. Classify the paper using Zero-Shot Classification.
9. Answer user queries using DistilBERT Question Answering.

---

## Future Improvements

- Support PDF upload for custom research papers.
- Build a Streamlit web interface.
- Add citation recommendations.
- Improve retrieval with Retrieval-Augmented Generation (RAG).
- Support multilingual research papers.

---

## Author

**Sukaina Rajab**


