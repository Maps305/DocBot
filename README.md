# DocBot
AI Chatbot That Answers Questions From a PDF

## Goal
Build a small web-based or CLI tool that:
  Accepts a PDF or set of documents (e.g., notes, articles, reports).
  Uses embeddings + a vector store to retrieve relevant chunks.
  Uses an LLM (like GPT-4 or OpenAI API) to answer questions using those documents.
Stack
| Component          | Tool                                                     |
| ------------------ | -------------------------------------------------------- |
| LLM                | OpenAI (via LangChain)                                   |
| Embeddings         | OpenAIEmbeddings                                         |
| Vector Store       | FAISS (local, lightweight, perfect for demo)             |
| Document Loader    | LangChain PDF loader or `PyMuPDF`                        |
| Backend (optional) | Python with Streamlit (easy UI) or Flask                 |
| Deployment         | Optional, can run locally or on Replit/Streamlit Sharing |

### Step-by-Step Plan
Day 1 ()
Understand Core Concepts + Start Code
✅ Day 2 ()
Build a Small UI / Polish & Document
