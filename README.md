# Voice-Activated Fully Local RAG System

## Overview
This project demonstrates how to create a **voice-activated, fully-local Retrieval Augmented Generation (RAG) system** that enables interactive, local search and generation capabilities without requiring a cloud connection. The system uses a **combination of local models** and **voice recognition** to deliver seamless, real-time conversational experiences.

## Features
- **Voice Activation**: Built using **speech-to-text (STT)** technology to trigger interactions.
- **Local RAG**: Retrieval is performed locally using vector-based search for quick and private information retrieval.
- **Seamless Integration**: Combines **voice recognition**, **local embeddings**, and **generation models** for real-time responses.

## Technologies
- **Speech-to-Text**: [Google Speech-to-Text API](https://cloud.google.com/speech-to-text)
- **RAG Model**: [FAISS](https://github.com/facebookresearch/faiss), **Langchain**
- **Embeddings**: **Sentence-BERT**, **OpenAI embeddings**
- **Text Generation**: **GPT-3** or local language models
- **Python Libraries**: `speech_recognition`, `transformers`, `langchain`

## How It Works
1. **Speech Input**: The system listens for voice input using **speech recognition**.
2. **Retrieval**: Voice input is processed, and relevant documents are retrieved locally from a **vector search** system.
3. **Response Generation**: The retrieved documents are fed into a **language model** to generate an appropriate response.

## Installation
1. Clone this repository:
    ```bash
    git clone https://github.com/your-username/voice-activated-rag-system.git
    ```
2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Set up your **Speech-to-Text API** and **RAG system** models.
4. Run the main script:
    ```bash
    python main.py
    ```

## Usage
To interact with the system:
- Simply **speak to trigger the system**, and it will respond based on the local RAG setup.
- Ideal for **offline usage** or **privacy-focused applications**.

## Contributions
Feel free to fork this project and make contributions. If you have any suggestions or improvements, feel free to create a pull request!
