# AI-Powered Document Q&A System

This project implements an AI-powered question-answering system that can process PDF documents, embed their content, and answer user queries based on the document's information. The system uses advanced natural language processing techniques and vector storage for efficient information retrieval.

## Features

- PDF document loading and processing
- Text chunking for efficient processing
- Embedding generation using HuggingFace models
- Vector storage using Pinecone for fast similarity search
- Question answering using a fine-tuned language model
- Support for Turkish language queries and responses
- Performance timing for query responses

## Technologies Used

- LangChain
- Pinecone
- Hugging Face Transformers
- CTransformers
- PyPDF
- Sentence Transformers

## Setup

1. Install the required packages:
   
pip install langchain pinecone-client transformers huggingface-hub ctransformers langchain-community pypdf sentence_transformers


3. Set up your Pinecone API key and environment:

PINECONE_API_KEY = "your-api-key"

PINECONE_API_ENV = "your-environment"

## Note

This project uses a specific Turkish language model (mradermacher/Trendyol-LLM-7b-chat-v1.8-GGUF). Ensure you have the correct model file or adjust the model configuration as needed.

## Future Improvements

- Implement error handling and logging
- Add support for multiple document types
- Improve the PDF generation functionality
- Implement a user interface for easier interaction

## Contributor

Yusuf Enes KURT
