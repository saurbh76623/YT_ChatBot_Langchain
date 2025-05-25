# YT_ChatBot_Langchain

# YouTube Chatbot using LangChain
🔍 Project Overview
This project is an intelligent chatbot that allows users to ask questions about any YouTube video and receive answers based on the video’s transcript. It uses LangChain, OpenAI’s GPT models, and vector embeddings to retrieve relevant chunks from the transcript and generate responses.

Whether it's summarizing the video, extracting facts, or answering detailed questions — this chatbot acts as your smart assistant for YouTube content.

# Features
Extracts transcript from any public YouTube video.

Embeds transcript chunks into vector space using OpenAI embeddings.

Uses FAISS (or ChromaDB) for fast semantic search.

Retrieves the most relevant parts of the transcript for a given question.

Uses GPT-3.5/4 via LangChain to generate human-like responses.

Simple UI with Streamlit for interactive use.

# Use Cases
Ask questions about a long podcast or lecture.

Get a summary of a video.

Ask for specific timestamps or sections.

Use in ed-tech, video summarization tools, or AI tutors.

# Tech Stack Used

| Component          | Tool/Library               |
| ------------------ | -------------------------- |
| LLM                | OpenAI GPT-4 via LangChain |
| Transcript Parsing | `youtube-transcript-api`   |
| Text Embeddings    | OpenAI Embeddings          |
| Vector Search      | FAISS / ChromaDB           |
| Backend Logic      | Python, LangChain          |
| Frontend           | Streamlit / Gradio         |
| Text Splitter      | RecursiveCharTextSplitter  |

