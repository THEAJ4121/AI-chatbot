# AI-chatbot

Ollama Download Page: https://ollama.com/
Ollama GitHub Repo: https://github.com/ollama/ollama

Ollama Chatbot
This is a simple command-line chatbot powered by Ollama and the langchain_ollama library.

It uses the llama3 model locally through Ollama to answer your questions based on conversation history.

Requirements:
Python 3.8 or higher
Ollama installed and running locally
Download Ollama
Ollama GitHub Repo

Required Python libraries:

langchain_ollama
langchain_core

Install Python libraries:

pip install langchain_ollama langchain_core

Install and run Ollama on your system:

Download and install Ollama from https://ollama.com/

Start the Ollama service by running:

ollama serve
Pull the llama3 model (if not already pulled):

ollama run llama3
Running the Chatbot
Save the provided main.py file.

In your terminal, navigate to the folder containing main.py and run:

python main.py
Start chatting!
Type your questions, and the chatbot will answer.
Type exit to quit the chatbot.

How It Works
It uses a prompt template to format conversation history and user questions.

It connects to the local Ollama server to query the llama3 model.

It stores conversation history to give more context-aware responses.

Notes
Make sure the Ollama service is running before starting the chatbot.

You can replace "llama3" with any other model available in Ollama by changing this line in main.py:
