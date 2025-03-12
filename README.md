# Conversational RAG with PDF Uploads and Chat History
- This Streamlit application implements a Retrieval-Augmented Generation (RAG) chatbot that allows users to upload PDFs and interact with their content through a conversational interface. It uses LangChain, FAISS for vector storage, Hugging Face embeddings, and Groq LLM for generating responses.

# Features
- Upload PDF files and extract content
- Create vector embeddings using FAISS and Hugging Face models
- Implement history-aware retrieval to enhance conversational accuracy
- Utilize Groq LLM for generating contextually relevant answers
- Maintain chat history using LangChain's chat message history
- Installation

## Prerequisites
- Ensure you have Python installed (>= 3.8) and set up a virtual environment:
python -m venv venv
source venv/bin/activate   # On macOS/Linux
venv\Scripts\activate      # On Windows

# Install Dependencies
- Run the following command to install required libraries:
  - pip install -r requirements.txt
- Create a .env file in the root directory and add your Hugging Face API Token:
  - HF_TOKEN=your_huggingface_token

# Usage
1. Run the Application
- streamlit run app.py
2. Provide your Groq API Key in the input field.
3. Upload a PDF file to process its content.
4. Enter your questions in the chat interface to retrieve context-aware responses.

# File Structure
📂 Conversational-RAG
├── app.py             # Main Streamlit application
├── requirements.txt   # Required Python packages
├── .env               # Environment variables
├── README.md          # Documentation

# Dependencies
- streamlit
- langchain
- langchain_community
- langchain_groq
- langchain_huggingface
- langchain_text_splitters
- langchain_core
- faiss-cpu
- pypdf
- python-dotenv

# Contributing
- Feel free to submit issues or pull requests to improve the project.

# Author
- Prathik M Hadagali
