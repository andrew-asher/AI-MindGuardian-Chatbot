# AI-MindGuardian-Chatbot

Prototype chatbot for mental health counseling using Llama-3.1-70b, Pinecone VectorDB, and Gradio, with embedded Psych8k data for context-aware conversations. Future improvements include code cleanup and LangGraph integration.

![MG 1](images/MG 1.png)
![MG 2](images/MG 2.png)
![MG 3](images/MG 3.png)
![MG 4](images/MG4 .png)

MindGuardian is a mental health counseling chatbot prototype developed using state-of-the-art AI models and technologies. This repository contains the code for setting up and running the chatbot, including the integration of Llama-3.1-70b-versatile, Pinecone vector database, and various other tools for a seamless conversational experience.

## Features

- **AI Model:** Llama-3.1-70b-versatile for advanced natural language understanding and response generation.
- **Conversational Memory:** Utilizes a memory buffer to remember previous interactions, providing context-aware responses.
- **Vector Database:** Pinecone is used to store and retrieve embedded data from the Psych8k dataset, enabling contextually relevant responses.
- **Embedding Model:** Nomic-ai/nomic-embed-text-v1.5 is used to embed the Psych8k dataset for efficient data retrieval.
- **User Interface:** Gradio is used to create a user-friendly interface for interacting with the chatbot.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/MindGuardian-Chatbot.git
   cd MindGuardian-Chatbot
