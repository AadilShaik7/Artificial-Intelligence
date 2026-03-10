ReadMe

You need the following installed:

Python 3.9+
Ollama
OpenAI Python SDK

1. Install Ollama

Download and install Ollama:
https://ollama.com/download
Verify installation:
ollama --version

2. Pull the Model

This project uses Llama 3.2.
Run:
ollama pull llama3.2
This downloads the model locally so it can run without internet.

3. Start the Ollama Server

Run:
ollama serve
Ollama will start a local API server at:
http://localhost:11434

4. Install Python Dependencies
   Install the OpenAI Python client:
   pip install openai

5. Run the Script
   Run the Python file:
   python main.py
   You will be asked to enter an initial student message:
