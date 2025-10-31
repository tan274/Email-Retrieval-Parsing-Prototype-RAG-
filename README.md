# Email Retrieval & Parsing Prototype  

This project is a prototype I built to explore **retrieval-augmented generation (RAG)** workflows using email data. 

## What it does  
- Parses simulated Venmo Paypal emails into a **structured transaction DataFrame** 
- Embeds email chunks using **sentence-transformers**  
- Stores embeddings in a **FAISS index** for fast semantic search  
- Supports natural language queries with results grounded in actual email content  
- Currently experimenting with **field based filtering** to improve retrieval quality  

## Tech Stack  
- **Languages:** Python  
- **Libraries:** Pandas, FAISS, sentence-transformers  
- **Tools:** Jupyter Notebook, VS Code  

## Why I built this  
I wanted to experiment with **semantic search + RAG pipelines** on real-world text data (emails). 

## Example Use Case  
- Ask: *"When did I last send money for sushi?"*  


