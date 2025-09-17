# RAG-Powered-Chatbot-for-News-Websites
This project is a Retrieval-Augmented Generation (RAG) chatbot designed to improve user interaction with news websites. It combines document retrieval with large language model (LLM) generation, enabling the chatbot to deliver accurate and context-aware responses by fetching relevant news articles and generating human-like conversational replies.

RAG-Powered Chatbot for News Websites

This is a **Retrieval-Augmented Generation (RAG) chatbot** designed to enhance user interaction with news websites. The chatbot combines document retrieval and large language model generation to deliver accurate, context-aware responses by fetching relevant news articles and generating conversational replies.

## 🔍 Features
- Retrieve relevant news articles based on user queries.
- Generate human-like, context-aware answers using Google Gemini API.
- Fast and scalable document search using vector databases (Qdrant / Chroma / FAISS).
- Embedding generation using Jina.
- Interactive frontend built with React.
- Optional Telegram bot integration for chatbot access outside the web.
- Simple REST API backend built with Node.js and Express.

## 🚀 Tech Stack
- **Frontend:** React, SCSS
- **Backend:** Node.js, Express
- **Embeddings:** Jina
- **Vector Database:** Qdrant / Chroma / FAISS
- **Language Model API:** Google Gemini API
- **Cache (Optional):** Redis
- **Telegram Bot (Optional)**

## ⚙️ How It Works
1. News articles are converted into vector embeddings and indexed in the vector database.
2. User enters a query through the frontend or Telegram bot.
3. Backend searches the vector database for relevant articles.
4. Retrieved documents and the user query are passed to the Google Gemini API.
5. The API generates a context-aware response.
6. The response is displayed in the frontend or sent via Telegram.
