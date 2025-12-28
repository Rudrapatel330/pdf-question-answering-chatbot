# PDF-Based Question Answering Chatbot

This project is a Python-based chatbot that allows users to upload PDF documents and ask questions based on the document content. The application analyzes the uploaded PDF and generates relevant answers using the Gemini API.

## Features
- Upload any PDF file
- Ask questions related to the PDF content
- Extracts and processes text from PDF documents
- Uses embeddings and vector search for better answer retrieval
- Simple and interactive UI built with Streamlit

## Technologies Used
- Python
- Streamlit
- Gemini API
- LangChain
- FAISS
- Hugging Face Embeddings

## How It Works
1. User uploads a PDF file.
2. The PDF content is loaded and split into smaller text chunks.
3. Text embeddings are created and stored using FAISS.
4. User asks a question related to the PDF.
5. The system retrieves relevant information and generates an answer using the Gemini API.

## Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/pdf-question-answering-chatbot.git

2. Install dependencies:
pip install -r requirements.txt

3. Create a .env file and add your Gemini API key:
GEMINI_API_KEY=your_api_key_here

4. Run the application:
streamlit run app.py

Notes
This is a learning-based project created for practice purposes.
The project currently supports PDF-based question answering only.
Future Improvements
Improve answer accuracy
Add support for more document formats
Enhance UI and performance

