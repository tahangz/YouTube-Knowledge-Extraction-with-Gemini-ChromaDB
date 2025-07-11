# YouTube Knowledge Extraction with Gemini & ChromaDB

This project demonstrates a pipeline for transforming YouTube video content into a searchable knowledge base using state-of-the-art AI tools:

- 🎥 **YouTube Transcripts**: Extracts subtitles/transcripts from videos
- 🧠 **Gemini AI**: Summarizes transcripts into key points using Google's Gemini (gemini-2.5-flash)
- 🗃️ **ChromaDB**: Stores summaries as embeddings for efficient semantic search

## 🔧 Technologies Used  
- **Python**  
- **[Gemini API](https://ai.google.dev)**  
- **[ChromaDB](https://www.trychroma.com/)**  
- **[YouTubeTranscriptApi](https://pypi.org/project/youtube-transcript-api/)**  
- **SentenceTransformers**  

## 🚀 Features  
- **Transcript Processing**  
  - Load and process YouTube transcripts.  
- **AI Summarization**  
  - Summarize content using Gemini AI.  
- **Vector Storage**  
  - Store summaries in ChromaDB.  
- **Semantic Search**  
  - Search stored notes with natural language.  

## 📁 Project Structure  
- `notebook.ipynb` → Full end-to-end workflow.  
- `requirements.txt` → List of dependencies.  
- `.env` → API keys (Gemini Key).  

## 🧪 Usage  
1. **Install dependencies**:  
   ```bash  
   pip install -r requirements.txt  
   ````
2. **Set your Gemini API key in .env:**

````env
GEMINI_API_KEY=your_key_here
````
3.**Run the notebook to:**

- Extract transcripts
- Generate summaries
- Store in Chroma
- Search your AI-powered video knowledge base

## 💡 Example Use Cases
- Auto-indexing podcast episodes

- Video summarization for research

- Building a custom AI tutor using YouTube content
