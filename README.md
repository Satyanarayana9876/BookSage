# 📚 BookSage – LLM-Powered Book Recommendation System

BookSage is a machine learning-powered system that leverages **Large Language Models (LLMs)** and **vector search** to provide personalized book suggestions based on user input.  
By analyzing book descriptions, the system recommends books based on **semantic meaning** and **emotional tone**.


## 🛠️ Project Components

1. **Text Data Cleaning** – `data-exploration.ipynb`  
   Preprocesses and cleans raw book metadata.  

2. **Vector Search** – `vector-search.ipynb`  
   Builds a vector database with **ChromaDB** to support semantic similarity search.  

3. **Zero-Shot Classification** – `text-classification.ipynb`  
   Uses LLMs to classify books into categories without explicit training.  

4. **Sentiment & Emotion Analysis** – `sentiment-analysis.ipynb`  
   Performs sentiment/emotion extraction to capture the *tone* of books.  

5. **Web Application** – `gradio-dashboard.py`  
   Interactive UI for users to query and explore recommendations.

---

## 🚀 Features

- 🔄 **Text Data Cleaning**: Prepares and processes raw book descriptions.  
- 🔍 **Semantic (Vector) Search**: Uses vector embeddings to find books most similar to a natural language query.  
- 🏷️ **Text Classification (Zero-Shot)**: Classifies books as *Fiction* or *Non-Fiction* using LLMs, enabling filtering.  
- 😊 **Sentiment & Emotion Analysis**: Extracts emotions like *suspenseful, joyful, sad*, etc., to sort books by tone.  
- 🌐 **Interactive Web App**: Gradio-based dashboard for users to explore book recommendations.

---

## 🧰 Technologies Used

- **NLP & Machine Learning**:  
  - [sentence-transformers](https://www.sbert.net/)  
  - [torch](https://pytorch.org/)  
  - [transformers](https://huggingface.co/transformers/)  

- **Data Processing**:  
  - [pandas](https://pandas.pydata.org/)  
  - [numpy](https://numpy.org/)  

- **Vector Search**:  
  - [ChromaDB](https://www.trychroma.com/)  
  - [LangChain](https://www.langchain.com/)  

- **Web App UI**:  
  - [Gradio](https://www.gradio.app/)  

