# 📚 Semantic Book Recommender

An interactive book recommendation app powered by semantic search.
This app uses LangChain, ChromaDB, and HuggingFace sentence-transformers to embed book descriptions and recommend the most relevant books based on user queries.

### 🚀 Demo

👉 Live App: https://huggingface.co/spaces/vishalsetti/semantic-book-recommender

### ✨ Features
	•	🔎 Semantic Search – Understands meaning beyond keyword matches
	•	📖 Book Database – Built from a collection of book descriptions
	•	⚡ Fast Retrieval – Uses ChromaDB vector store for efficient similarity search
	•	🤗 Hugging Face Models – Embeddings via sentence-transformers/all-MiniLM-L6-v2

### 🛠️ Tech Stack
	•	Python 3.10+
	•	Streamlit – UI framework
	•	LangChain – Orchestration and embeddings
	•	ChromaDB – Vector database
	•	sentence-transformers – Embedding model
	•	Hugging Face Spaces – Hosting

### 📂 Project Structure
```
📦 semantic-book-recommender
 ┣ 📜 app.py                # Main Streamlit app
 ┣ 📜 requirements.txt      # Dependencies
 ┣ 📜 README.md             # Project documentation
 ┗ 📂 data/                 # Book dataset
```

### 📌 Usage
	1.	Enter a query (e.g., “magic school adventure”) in the search bar.
	2.	The app finds the most semantically similar books.
	3.	Results are displayed with titles and descriptions.
