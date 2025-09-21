# OllamaChat

# Ollama LLM Chat App

A simple web app to chat with an **Ollama LLM** model using **Streamlit**. Ask questions, get answers, and experiment with your local language model.

## Features
- Chat with an Ollama LLM model locally
- Simple and clean Streamlit interface
- Easy to set up and run

## Requirements
- Python 3.10+
- [Ollama](https://ollama.com/) installed
- Streamlit

## Setup & Run
1. Clone the repo:  
bash
git clone https://github.com/yourusername/ollama-streamlit-app.git
cd ollama-streamlit-app

##Create a virtual environment:
python -m venv venv
# Activate:
# Windows: venv\Scripts\activate
# Linux/Mac: source venv/bin/activate


### Install dependencies:
pip install -r requirements.txt


### Pull the Ollama model:
ollama pull <model_name>

### streamlit run app.py
streamlit run app.py
