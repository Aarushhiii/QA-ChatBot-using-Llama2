
# Research Paper QA Chatbot using Llama2
This project implements a research assistant chatbot that collects research paper data, builds a vector store, and allows users to query papers using natural language. The system follows a Retrieval-Augmented Generation (RAG) pipeline to provide accurate, context-aware responses from academic content.

The goal is to automate literature exploration and assist researchers in quickly extracting information from large collections of papers.

## Methodology
- Research papers are collected and stored in structured format.
- Documents are cleaned and split into chunks.
- Embeddings are generated and stored in a vector database.
- User queries are embedded and matched using similarity search.
- Retrieved context is passed to the chatbot to generate answers.

## Example
Contains collected and preprocessed research paper data. 

## How to Run

pip install -r requirements.txt
python collect_research_paper_data.py
python create_vector_store.py
python main.py 

## Author
- Aarushi Jain
- Linkedin: https://www.linkedin.com/in/aarushi-jain-448606195/
