# 🔍 Semantic Search Chat

A lightweight AI app that lets you ask natural language questions and finds the most relevant answers from a set of documents using semantic similarity.

This app uses **Sentence Transformers**, **cosine similarity**, and **Streamlit** to give fast, accurate search results — with a conversational UI.

------------------------------------------------------------

🧠 HOW IT WORKS

This app is powered by:
- Sentence-Transformers: For generating embeddings of queries and documents
- Cosine Similarity: For measuring similarity between user queries and stored documents
- Streamlit: For the interactive web interface
- NumPy: For fast vector operations

------------------------------------------------------------

📌 FEATURES

- Upload a plain text file (`document.txt`) with one document per line
- Ask a question via natural language
- Uses semantic search to return the most relevant answer with a similarity score
- Simple chat-style history using Streamlit's session state

------------------------------------------------------------

🚀 INSTALLATION

1. Clone the repository:

   git clone https://github.com/yourusername/semantic-search-chat.git  
   cd semantic-search-chat

2. Create and activate a virtual environment:

   python -m venv venv  
   source venv/bin/activate      # On Windows: venv\Scripts\activate

3. Install dependencies:

   pip install -r requirements.txt

4. Add your text data:

   - Create a `document.txt` file in the root folder  
   - Each line should be a standalone document (sentence, paragraph, or entry)

------------------------------------------------------------

▶️ RUN THE APP

   streamlit run app.py


