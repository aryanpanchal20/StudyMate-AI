# StudyMate AI

StudyMate AI is an AI-powered study assistant that allows students to upload
PDF study material and ask questions about the uploaded documents.

The application uses Retrieval Augmented Generation (RAG) to retrieve relevant
information from uploaded PDFs before generating an answer.

## Planned Technology Stack

### Frontend
- React
- Vite
- JavaScript
- Bootstrap 5
- Axios

### Backend
- FastAPI
- Python
- LangChain
- ChromaDB
- PyPDF
- Uvicorn

### AI
- OpenAI-compatible LLM
- Embeddings
- Retrieval Augmented Generation (RAG)

## Project Status

🚧 Development started.

## Main Goal

Upload PDF → Extract text → Split text → Create embeddings → Store in ChromaDB → Retrieve relevant content → Generate answer with page citations.