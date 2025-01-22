# Ollama Deepseek Local Chatbot 🤖

App by [Build Fast with AI](https://www.buildfastwithai.com/genai-course)

A lightweight, offline-capable chatbot powered by Deepseek R1 1.5B and Ollama, running completely on your local machine. No internet required!

## Features ✨

- 🏃‍♂️ Runs 100% locally - no internet or cloud services needed
- 💨 Streaming responses like ChatGPT
- 🧠 Shows AI thinking process in expandable sections
- 🎯 Uses the tiny but mighty Deepseek R1 1.5B model
- 🚀 Built with Streamlit for a clean, modern UI

## Prerequisites

- Python 3.10+
- [Ollama](https://ollama.ai/) installed on your system
- Deepseek R1 1.5B model pulled in Ollama

## Quick Start 🚀

1. Install Ollama and pull the Deepseek model:

2. Clone this repository:
```bash
git clone [your-repo-url]
cd [your-repo-name]
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Run the app:
```bash
streamlit run deepseek-r1-streamlit.py
```

## How It Works 🛠️

The app uses:
- Ollama for running the Deepseek R1 1.5B model locally
- LangChain for model interaction
- Streamlit for the web interface
- Streaming responses for real-time interaction
- Expandable "thinking process" sections to see the AI's reasoning


## Dependencies 📦

The project uses three main Python packages:
```
streamlit
langchain
langchain-community
```

## Usage Examples 💡

After starting the app:
1. Open your browser at `http://localhost:8501`
2. Type your question in the chat input
3. Watch the AI respond in real-time
4. Click "Show AI thinking process" to see the reasoning

## Offline Usage 🔌

This chatbot is designed to work completely offline. Once you have:
1. Installed Ollama
2. Downloaded the Deepseek model
3. Installed Python dependencies

You can disconnect from the internet and continue using the chatbot!


## Acknowledgments 🙏

- [Ollama](https://ollama.ai/) for the local model serving
- [Deepseek](https://deepseek.ai/) for the amazing 1.5B model
- [LangChain](https://github.com/langchain-ai/langchain) for the framework
- [Streamlit](https://streamlit.io/) for the web interface

---

Made with ❤️ for the local AI community