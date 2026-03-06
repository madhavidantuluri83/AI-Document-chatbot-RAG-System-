# AI-Document-chatbot-RAG-System-
A user uploads a document (PDF or text), and the AI answers questions from that document.

Example:
Document: Company Policy PDF
User asks: "What is the leave policy?"
The AI reads the document and answers correctly.

**Technologies to Use**
Backend: FastAPI
AI: OpenAI API
Framework: LangChain
Vector database: FAISS

**Architecture Flow:**

1️⃣ User uploads PDF
2️⃣ Text is extracted
3️⃣ Text is split into chunks
4️⃣ Chunks stored in vector database
5️⃣ User asks question
6️⃣ AI retrieves relevant text
7️⃣ AI generates answer

Install Packages:
pip install fastapi uvicorn langchain openai faiss-cpu pypdf
