<img width="1920" height="1020" alt="Screenshot 2026-03-03 223522" src="https://github.com/user-attachments/assets/f61d17a7-8aeb-477e-be2c-bde71f7fb8d8" />
# Built-an-Agentic-RAG-System-with-Langflow-Groq
Excited to share that I’ve successfully completed an Agentic Retrieval-Augmented Generation (RAG) system using Langflow and Groq LPU-powered inference.
# 🤖 Agentic RAG System with Langflow + Groq

## 🚀 Overview
This project implements an Agentic Retrieval-Augmented Generation (RAG) system using Langflow. 

Unlike traditional linear RAG pipelines, this system enables autonomous tool selection and structured function calling. The Agent dynamically decides when to retrieve context from the vector database and when to respond directly.

## 🧠 Architecture

User Query  
    ↓  
Agent (Tool-Calling Enabled LLM via Groq)  
    ↓  
Retriever (Vector DB)  
    ↓  
Context Grounding  
    ↓  
Final Response  

## ✨ Key Capabilities

- Dynamic tool invocation
- Validated structured tool calls
- Reduced hallucination via grounded retrieval
- High-speed inference using Groq LPU acceleration
- Visual orchestration via Langflow

## 🛠 Tech Stack

- Orchestration: Langflow
- LLM: Groq API
- Vector Store: Astra DB
- Embeddings: [Specify model]
- Language: Python

## 📌 Key Learning

Proper tool registration is critical in agent frameworks.  
If a model attempts to call a tool not included in `request.tools`, validation fails.

Understanding this improved system robustness significantly.<img width="1920" height="1080" alt="langflow" src="https://github.com/user-attachments/assets/0e59282d-8135-40df-b200-214dfe230492" />

the response for the agentic ai is ![Uploading Screenshot 2026-03-03 223522.png…]()
