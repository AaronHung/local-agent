# 🤖 local-agent

Build your own **fully local AI agents** using Python — no API keys, no cloud fees.

This project demonstrates how to set up and run local language model agents using:

- 🧠 [Ollama](https://ollama.ai/) – Run large language models locally (e.g. LLaMA, Mistral)
- 🔗 [LangChain](https://github.com/langchain-ai/langchain) – Framework for building agent workflows
- 📚 [ChromaDB](https://www.trychroma.com/) – Lightweight local vector store for RAG (retrieval augmented generation)

All components are 100% offline and **free to use locally**.

---

## 🚀 Features

- 🔧 Fully local agent execution using Ollama
- 🔍 Document embedding and semantic search with ChromaDB
- 🧩 Modular agent logic via LangChain
- 🛠️ Designed for extensibility (tools, memory, RAG, etc.)

---

## 📦 Requirements

- Python 3.10+
- [Ollama](https://ollama.ai/)
- pip packages:
  ```bash
  pip install -r requirements.txt
  ```

---

## 🧪 Quick Start

```bash
# 1. Run an Ollama model
ollama run mistral

# 2. Start your local agent
python agent.py
```

> You can switch models like `llama2`, `mistral`, or `codellama` by changing the agent config.

---

## 📁 Project Structure

```bash
local-agent/
├── agent.py           # Main agent logic
├── vector_store.py    # ChromaDB setup and retrieval
├── tools/             # Optional agent tools
├── docs/              # Embedded documents for search
└── README.md
```

---

## 🧠 Coming Soon

- Memory-enhanced agents
- Custom toolchains
- Agent CLI / Web UI

---

## 📝 License

This project is open source under the [MIT License](LICENSE).

```

---
```
