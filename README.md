# GenAI-learnings

A curated collection of Udemy course projects for artificial intelligence, deep learning, natural language processing, and generative AI.

## Repository Overview

This repository contains hands-on examples covering:
- neural network classification and regression
- simple RNN and LSTM models
- LangChain basics and advanced workflows
- OpenAI and Ollama integrations
- chatbot design, message history, and conversational QA
- retrieval-augmented generation (RAG) with document search

## Folder Structure

- `01_annclassification/`
  - ANN classification and regression demos
  - key files: `app.py`, `prediction.ipynb`, `hyperparametertuningann.ipynb`, `salaryregression.ipynb`, `Churn_Modelling.csv`, `model.h5`

- `02_simple_rnn_imdb/`
  - IMDB sentiment analysis with a simple RNN
  - key files: `main.py`, `prediction.ipynb`, `embedding.ipynb`, `simple_rnn_imdb.h5`

- `03_LSTM RNN/`
  - LSTM-based text generation and next-word prediction
  - key files: `app.py`, `next_word_lstm_model_with_early_stopping.h5`, `next_word_lstm.h5`, `hamlet.txt`

- `04_Basics_Of_Langchain/`
  - LangChain fundamentals and data pipeline examples
  - includes OpenAI/Ollama examples, text splitting, embeddings, and vector stores
  - key subfolders: `1.1-openai/`, `1.2-ollama/`, `3.2-DataIngestion/`, `3.3-Data Trnasformer/`, `4-Embeddings/`, `5-VectorStore/`

- `05_openai/`
  - OpenAI and Ollama starter projects
  - key files: OpenAI demo notebooks and `app.py`

- `06_LCEL/`
  - LLM client/server demo with local HTTP service
  - key files: `client.py`, `serve.py`, `simplellmLCEL.ipynb`

- `07_chatbot_messagehistory/`
  - Chatbot examples with message history and retrieval
  - key notebooks: `1-chatbots.ipynb`, `vectorretriever.ipynb`

- `08_conversation_chatbot/`
  - Conversational QA chatbot example
  - key notebook: `conversationqa.ipynb`

- `09_langchainupdated/`
  - Updated LangChain examples and modern workflow demos
  - key files: `main.py`, `pyproject.toml`, `requirements.txt`, notebooks in `updatedlangchain/`

- `10_OpenAI+Chatbot/`
  - OpenAI chatbot and Ollama chatbot apps
  - key files: `2-OpenAI Chatbot/app.py`, `3-Ollama Chatbot/app.py`, `.env`, `requirements.txt`

- `11_RAG Document Q&A/`
  - Retrieval-Augmented Generation with document embeddings
  - key files: `main.py`, `app_huggingfaceembedding.py`, `research_papers/`

## Getting Started

1. Choose a folder based on the topic you want to explore.
2. Install dependencies from that folder:
   ```bash
   pip install -r "<folder>/requirements.txt"
   ```
3. Open and run the notebooks with Jupyter or JupyterLab, or run the Python app files directly.

## Notes

- Keep API credentials safe and add them to `.env` where required.
- Many folders include notebooks for learning and script files for demo apps.
- This repository is organized to progress from core deep learning models to modern LangChain and RAG applications.
