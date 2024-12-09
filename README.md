# 🗂️ Chat with Your Documents - PDF AI Assistant

This Streamlit-powered app allows you to upload PDF documents and interact with them conversationally using an LLM-based chatbot. The app uses the Ollama LLM, HuggingFace embeddings, and LlamaIndex for contextual search and response generation.

### 🚀 Features

##### PDF Upload and Indexing: 
Upload your .pdf files and index them for conversational interaction.
##### LLM-powered Responses: 
Uses Ollama LLM to generate concise and context-aware answers.
##### Custom Prompt Templates: 
Tailored prompts for generating relevant and step-by-step answers.
##### Streaming Responses: 
Chatbot responses are displayed in real-time.
##### PDF Preview: 
Embedded preview of uploaded PDFs in the app interface.
##### Session State Management: 
Tracks chat history and manages file caching for seamless user experience.

### 📖 How It Works

##### Upload a PDF: 
Upload any .pdf document using the sidebar uploader.
##### Index Your Document: 
The app processes your file and creates an index using HuggingFace Embeddings and VectorStoreIndex.
##### Ask Questions: 
Type your queries, and the chatbot will fetch the context from your document and generate answers.
##### Chat History: 
All exchanges are saved in the session for easy reference.

### 🛠️ Technologies Used

Streamlit: Simplifies building an interactive UI.
LlamaIndex: Manages embeddings and facilitates conversational interactions.
Ollama LLM: Generates high-quality responses.
HuggingFace Embeddings: Converts document data into vector embeddings for semantic search.

### 📝 Usage

Upload a PDF file in the sidebar.
Wait for the document to index (progress indicated in the UI).
Start asking questions in the chat interface.
