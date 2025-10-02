# Email Retrieval & Parsing Prototype  

This project is a prototype I built to explore **retrieval-augmented generation (RAG)** workflows using email data. The main goal was to take messy, unstructured emails and turn them into something structured and searchable.  

## What it does  
- Parses raw emails into a **structured transaction DataFrame** with normalized fields  
- Embeds email chunks using **sentence-transformers**  
- Stores embeddings in a **FAISS index** for fast semantic search  
- Supports natural language queries with results grounded in actual email content  
- Experiments with **chunking strategies** (sentence, metadata-based) and **filtering** to improve retrieval quality  

## Tech Stack  
- **Languages:** Python  
- **Libraries:** Pandas, NumPy, FAISS, sentence-transformers  
- **Tools:** Jupyter Notebook, VS Code  

## Why I built this  
I wanted to experiment with **semantic search + RAG pipelines** on real-world text data (emails). 

## Example Use Case  
- Ask: *"When did I last send money for sushi?"*  
- System: retrieves the Venmo email → parses → returns structured result  


