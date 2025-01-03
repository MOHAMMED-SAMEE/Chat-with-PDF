Chat with PDF is an interactive chatbot application that enables users to ask questions about the content of uploaded PDF files. The app processes the text from PDFs, generates embeddings, and uses Google's Gemini AI to answer user queries accurately.

Features ✨
Automatic PDF Processing: Reads and processes all PDFs from a predefined directory upon app startup.
Advanced AI-Powered Chat: Uses Google Generative AI (Gemini) for natural language understanding and question answering.
Interactive Interface: Streamlit-based user-friendly interface for seamless interaction.
Text Chunking: Splits large PDF content into manageable chunks for efficient processing.
FAISS Vector Store: Creates and queries a vector store for similarity-based question answering.
Installation and Setup 🛠️
Prerequisites
Python 3.9 or later installed on your system.

Required libraries installed:

streamlit
PyPDF2
langchain
langchain-google-genai
google-generativeai
faiss-cpu
python-dotenv
A Google Generative AI API key to enable AI-based question answering.

Acknowledgments 🙏
Google Generative AI for AI models.
Streamlit for the web application framework.
LangChain for simplifying AI workflows.
