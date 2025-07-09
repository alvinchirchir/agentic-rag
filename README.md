# Agentic AI: Web Scraper + Knowledge Querying

This project uses **LangChain**, **GPT4All**, and **ChromaDB** to build an AI agent that can:

- Scrape content from websites  
- Store it in a vector database  
- Answer questions based on that content using local LLMs  

Perfect for research, grant matching or knowledge retrieval tasks.

---

## Features

- Web scraping with Scrapy / BeautifulSoup  
- Local embedding and vector storage via ChromaDB  
- Retrieval-Augmented Generation (RAG) using GPT4All  
- Jupyter Notebook interface  
- Runs offline (with Ollama or GPT4All models)

---

## Getting Started

### 1. Install Python

Download and install **Python 3.80+** from:  
 https://www.python.org/downloads/

> During installation, **check the box** for “Add Python to PATH”.


### 2. Install Jupyter Notebook

Open your terminal (or command prompt) and run:

```bash
pip install notebook
```

### 2. Install Local LLM
Go to https://www.nomic.ai/gpt4all where you can download and install models locally. This project uses Ollama 3.2


### 3. Clone or Download the Repository

git clone https://github.com/alvinchirchir/agentic-rag
cd agentic-rag


### 4. Install Required Python Packages

pip install -r requirements.txt

### 5. Launch the Jupyter Notebook

jupyter notebook

