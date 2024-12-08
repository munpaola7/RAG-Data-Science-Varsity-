# RAG Application Using Knowledge Graph and Vector Search

## Overview
This project implements a Retrieval-Augmented Generation (RAG) application that leverages both Knowledge Graphs and Vector Search for improved performance in generating accurate and contextually appropriate responses. Using Wikipedia articles, the application creates a Knowledge Graph and a vector search database to retrieve relevant information and generates responses using a Language Model.

---

## Project Goals
1. **Implement Vector Search**:
   - Index and retrieve embeddings for Wikipedia articles.
   - Perform chunking, embedding generation, and efficient similarity searches.

2. **Integrate Knowledge Graphs**:
   - Use Knowledge Graphs to improve retrieval.
   - Query Knowledge Graphs using SPARQL to incorporate structured data into the pipeline.

3. **Generate Responses**:
   - Use a publicly available LLM to generate responses based on retrieved data.
   - Support both free and paid models (e.g., OpenAI’s models, Microsoft Phi, or LLaMA).

---

## Key Features
1. **Data Collection**:
   - Process 100,000 Wikipedia articles.
   - Use these articles to build a Knowledge Graph and vector database.

2. **Knowledge Graph Integration**:
   - Enhance retrieval using structured data from Knowledge Graphs.
   - Use SPARQL queries to extract meaningful relationships and concepts.

3. **Vector Search Implementation**:
   - Generate embeddings for text data using pre-trained models (e.g., BERT).
   - Use vector search libraries (e.g., Pinecone, FAISS) for efficient retrieval.

4. **RAG Pipeline**:
   - Combine vector search and Knowledge Graphs for enhanced retrieval.
   - Use an LLM to generate contextually rich and accurate responses.

5. **Evaluation**:
   - Assess response quality based on accuracy, relevance, and contextual fit.
   - Optimize the application for better performance.

---

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo-name.git
   cd your-repo-name
