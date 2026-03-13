# Persistent Memory Agent System

An AI assistant that maintains long-term memory across topics and sessions,
allowing users to resume research where they left off.

## Features
- Topic-specific memory persistence
- Conversation history replay
- Lightweight storage using TinyDB
- Local LLaMA2 inference via Ollama
- Streamlit frontend

## How to Run
1. Pull model:
   ollama pull llama2
2. Start Ollama
3. Run app:
   streamlit run frontend.py
