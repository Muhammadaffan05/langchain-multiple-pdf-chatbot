# PDF Chatbot using Gemini-Pro

## Overview
This project allows users to interact with PDF documents using a conversational AI model. By leveraging Google Gemini-Pro for answering questions and FAISS for vector storage, users can upload PDFs, process their content, and ask questions about them. The system retrieves relevant text chunks and provides accurate responses based on the context of the PDFs.

## Features
- Upload multiple PDF files.
- Extract text from PDFs.
- Split extracted text into manageable chunks.
- Create and store vector embeddings using FAISS.
- Use Google Gemini-Pro for answering questions.
- Provide accurate responses based on PDF content.
- Simple and interactive UI using Streamlit.

## Technologies Used
- **Python**: Core programming language.
- **Streamlit**: For creating the user interface.
- **PyPDF2**: For extracting text from PDFs.
- **LangChain**: For text processing and AI model integration.
- **Google Generative AI (Gemini-Pro)**: For answering questions.
- **FAISS**: For storing and retrieving vector embeddings.
- **dotenv**: For managing API keys securely.


## Notes
- Ensure your Google API Key is valid and has access to Gemini-Pro services.
- The FAISS index is stored locally and reused for faster processing.

## PDF Chatbot
This project serves as a **PDF Chatbot**, allowing users to ask questions about uploaded PDFs and receive accurate, context-aware responses. By leveraging **Google Gemini-Pro** and **FAISS**, the chatbot efficiently retrieves information, making document interaction seamless and user-friendly.



