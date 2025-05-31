# 🧠 Mini RAG with Pinecone and Embeddings

This project is a minimal implementation of a **Retrieval-Augmented Generation (RAG)** model using [Pinecone](https://www.pinecone.io/) and multilingual sentence embeddings. It demonstrates how to index a small dataset, query it semantically, and retrieve relevant results based on vector similarity.

---

## 🚀 Features

- Uses `Pinecone` for vector similarity search.
- Embeds textual data using `multilingual-e5-large` model.
- Demonstrates upserting and querying data.
- Implements semantic search in a few lines of code.
- Easily adaptable to larger RAG workflows.

---

## 📦 Setup Instructions

### 1. Clone the Repository

git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name

### 2. Install Required Libraries

- pip install protoc_gen_openapiv2
- pip install -U pinecone

## 🔐 Pinecone API Key
### Set your Pinecone API key:

- from pinecone.grpc import PineconeGRPC as Pinecone
- pc = Pinecone(api_key="YOUR_API_KEY")

  ### 📊 Data & Embeddings
  ### 🧬 Index Creation & Upsertion
  - Create a serverless index and upload vectors:

  ### 🔍 Querying the Vector DB
  - Query the index with a semantic question:
 
  ### 🧠 Ideal For:
  - Rapid prototyping of RAG systems

  - Understanding semantic search with Pinecone

  - Creating Q&A systems or AI companions

  ### 🤝 Contributing
  Feel free to fork, improve, and submit pull requests! Suggestions are welcome.
