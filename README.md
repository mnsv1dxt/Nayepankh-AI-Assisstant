NayePankh AI Assistant:-

An AI-powered chatbot that answers questions about the NayePankh Foundation using Retrieval-Augmented Generation (RAG).


Project Overview:-

This project was developed to provide users with an intelligent chatbot capable of answering questions using information extracted from the official NayePankh Foundation website.

Instead of sending the entire website to the AI model, the chatbot retrieves only the most relevant information using semantic search before generating an answer.


Features:-

- AI-powered chatbot
- Multi-page website crawling
- Website content extraction
- Intelligent text chunking
- Semantic Search using FAISS
- Retrieval-Augmented Generation (RAG)
- Local Llama 3.2 model (Ollama)
- Streamlit web interface
- Chat history
- NayePankh branding


Technologies Used:-

- Python
- Streamlit
- Ollama
- Llama 3.2
- Sentence Transformers
- FAISS
- BeautifulSoup
- Requests
- NumPy
  

System Architecture:-

Website
↓
Crawler
↓
Text Cleaning
↓
Chunking
↓
Sentence Transformers
↓
FAISS Vector Database
↓
Relevant Chunks
↓
Llama 3.2 (Ollama)
↓
Answer


Installation

```bash
git clone <repository-url>

cd NayePankh-AI-Assistant

pip install -r requirements.txt

ollama pull llama3.2:3b

streamlit run app.py
```

Project Structure

```
app.py
rag.py
scrape.py
chunk_data.py
build_vector_database.py
search.py
website.index
chunks.pkl
requirements.txt
README.md
```

Future Improvements

- Source citations
- Voice assistant
- Multi-language support
- PDF document chatbot
- Better UI design


Developed By-
Manasvi Dixit
B.Tech CSE (AI & ML)
GD Goenka University
