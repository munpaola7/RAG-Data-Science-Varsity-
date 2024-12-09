# RAG Application Using Knowledge Graph and Vector Search

## Overview
This project implements a Retrieval-Augmented Generation (RAG) application that leverages both Knowledge Graphs and Vector Search for improved performance in generating accurate and contextually appropriate responses. Using Wikipedia articles, the application creates a Knowledge Graph and a vector search database to retrieve relevant information and generates responses using LLM.

---

## Project Features
1. **Data Collection**:
   - Process 100,000 Wikipedia articles.
   - Use these articles to build a Knowledge Graph and vector database.

2. **Knowledge Graph Integration**:
   - Enhance retrieval using structured data from Knowledge Graphs using Neo4j.
   - Use query mechanisms to extract meaningful relationships and concepts.

3. **Vector Search Implementation**:
   - Generate embeddings for text data using pre-trained models with Pinecone.
   - Use vector search libraries for efficient retrieval.

4. **RAG Pipeline**:
   - Combine vector search and Knowledge Graphs for enhanced retrieval.
   - Use an LLM to generate contextually accurate responses.

5. **Evaluation**:
   - Assess response quality based on accuracy, relevance, and contextual fit.
   - Optimize retrieval and generation processes.

---

## Libraries Needed
Ensure you have the following libraries installed before running the project:

1. **Data Processing**:
   - `pandas`
   - `pyarrow`
   - `datasets`
   - `spacy`

2. **Embedding Generation**:
   - `transformers`
   - `torch`
   - `tiktoken`

3. **Vector Search**:
   - `pinecone-client`

4. **Knowledge Graph Integration**:
   - `neo4j`
   - `tqdm`

5. **Utilities**:
   - `langchain`
   - `re`

---

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo-name.git
   cd your-repo-name

## Contributors

1. Paola Munoz
2. Hilary Wang
3. Rohan Vuppala
