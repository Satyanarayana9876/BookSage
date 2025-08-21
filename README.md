The BookSage is a machine learning-powered system that leverages Large Language Models (LLMs) and vector search to provide personalized book suggestions based on user input. By analyzing book descriptions, the system finds similar books based on semantic meaning and emotional tone.

There are five components to this project:
1)Text data cleaning (data-exploration.ipynb)
2)Semantic (vector) search and how to build a vector database (vector-search.ipynb). This allows users to find the most similar books to a natural language query. 
3)Doing text classification using zero-shot classification in LLMs (text-classification.ipynb). This allows us to classify the books as "fiction" or "non-fiction", creating a facet that users can filter the books on. 
4)Doing sentiment analysis using LLMs and extracting the emotions from text (sentiment-analysis.ipynb). This will allow users to sort books by their tone, such as how suspenseful, joyful or sad the books are.
5)Creating a web application using Gradio for users to get book recommendations (gradio-dashboard.py).

Technologies Used
🧠 NLP & Machine Learning: sentence-transformers, torch, transformers
📊 Data Processing: pandas, numpy
📌 Vector Search: chromadb, langchain
🌐 Web App UI: gradio
