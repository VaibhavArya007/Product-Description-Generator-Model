# Product-Description-Generator-Model
This project involves developing an advanced Product Description Generator that leverages Retrieval-Augmented Generation (RAG) and various machine learning algorithms to produce detailed and accurate product descriptions. The core functionality is built upon the Amazon Product Question and Answer (PQA) dataset,  focusing on Yes/No questions..

# RAG-Based Product Description and Query Handler

This project implements a Retrieval-Augmented Generation (RAG) model to generate product descriptions and handle user queries based on a given dataset. 

## Installation

To set up the environment and install required packages, follow these steps:

1. **Install necessary libraries**:
    - pandas
    - langchain
    - pinecone-client
    - openai
    - langchain-community
    - torch
    - datasets
    - transformers
    - tensorflow
    - playwright
    - html2text
    - sentence-transformers
    - faiss-cpu
    - accelerate
    - peft
    - bitsandbytes
    - trl
    - llama-index

2. **Mount Google Drive**: Ensure you have access to the dataset files stored in your Google Drive.

3. **Load and process the data**: Concatenate, filter, and process the JSON files containing the dataset to prepare it for model training and query handling.

4. **Model and Embeddings Setup**: Use `sentence-transformers/all-mpnet-base-v2` for generating embeddings and FAISS for vector storage and retrieval.

5. **Build the RAG Model**: Combine the retriever and language model to handle user queries and generate accurate responses based on the retrieved context.

---

This README provides a high-level overview of setting up and running the RAG-based model for product description and query handling without including any code. For detailed implementation, refer to the project's code files.
