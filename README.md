# 🧠 Mental Wellness Assistant

A compassionate and intelligent chatbot designed to assist users with mental well-being by providing supportive, clear, and empathetic responses. This chatbot leverages state-of-the-art language models and vector search technology to deliver relevant, thoughtful answers to mental health-related queries.

---

## Overview

This project builds a mental health chatbot using:

- **LangChain** with Groq integration for highly efficient model inference.
- **ChromaDB** vector database for semantic search on mental health documents.
- **HuggingFace Embeddings** via SentenceTransformers to convert text into meaningful vector embeddings.
- **Gradio** interface for an interactive, user-friendly chat UI.

The chatbot can answer questions based on both general knowledge and contextually relevant documents, making it a helpful companion for exploring mental health topics.

---

## Features

- Compassionate, thoughtful chatbot responses tailored to mental health questions.
- Retrieval-augmented generation using a vector database of mental health resources.
- Easy-to-use web interface with a clear disclaimer for emergency guidance.
- Modular architecture using LangChain for extensibility and integration.

---

## Installation and Setup

1. Clone this repository to your local machine.
2. Install the necessary packages using:
pip install -r requirements.txt
3. Prepare your mental health resource documents (PDFs) and place them in the designated `/data` directory.
4. Configure your Groq API key (or alternative LLM key) as an environment variable:
export GROQ_API_KEY="your_api_key_here"
5. Run the chatbot application:
python app.py


---

## Usage

- Start the chatbot and type your mental health questions.
- For serious concerns or emergencies, always contact a licensed professional or local helpline.
- Type `exit` to end the conversation.

---

## Code Structure

- **initialize_llm()**: Initializes the language model with Groq integration.
- **create_vector_db()**: Loads and processes documents into a persistent vector database.
- **setup_qa_chain()**: Builds the retrieval question-answering chain.
- **chatbot_fn()**: Handles user input and fetches model responses.
- **Gradio Interface**: Provides an interactive web UI for chatting.

---

## Acknowledgements

This chatbot project was developed inspired by a comprehensive tutorial from YouTube. Thanks to the content creator for sharing valuable knowledge and guidance that made this possible.

---

## Disclaimer

⚠️ **Important:** This chatbot is designed to provide supportive information and is not a substitute for professional medical advice, diagnosis, or treatment. In case of emergency or serious mental health concerns, please contact qualified healthcare professionals or local emergency services immediately.

---

## Contact & Contributions

For suggestions, issues, or contributions, please open an issue or submit a pull request on GitHub.

---

Thank you for exploring this mental health chatbot project. May it serve as a helpful tool in your well-being journey.
