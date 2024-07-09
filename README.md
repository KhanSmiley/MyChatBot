# MyChatBot
 
This project is a simple chatbot that uses OpenAI's GPT-3.5-turbo model to answer questions based on the content of an uploaded PDF document. The application is built using Streamlit for the frontend and LangChain for text processing and vector storage.
 
## Features
 
- Upload a PDF document
- Extract text from the PDF
- Split the extracted text into manageable chunks
- Generate embeddings for the text chunks using OpenAI
- Store the embeddings in a FAISS vector store
- Perform similarity searches on the stored embeddings
- Answer user questions based on the similarity search results
 
