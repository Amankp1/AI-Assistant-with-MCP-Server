# 🧠 MCP Interactive Chat with Memory (Groq + LangChain)

This repository contains an asynchronous Python-based interactive memory-enabled chatbot powered by [LangChain](https://www.langchain.com/), [Groq API](https://console.groq.com/), and a modular tool configuration system via `MCPClient`.

💬 The assistant supports contextual memory, external tools (like browser agents), and a CLI chat interface. It uses the powerful `qwen-qwq-32b` model from Groq.

---

## 🚀 Features

- ✅ Asynchronous CLI chat loop
- ✅ Supports memory-based conversation history
- ✅ Customizable with external tool plugins via `browser_mcp.json`
- ✅ Works with Groq-hosted LLMs via LangChain
- ✅ Clean exit, error handling, and "clear history" support

---

## 🧩 Tech Stack

- **Python 3.10+**
- **LangChain**
- **Groq (LLM hosting)**
- **MCP Framework** (custom modular agent and client)
- **AsyncIO** for smooth interactive input
- **dotenv** for secure API key management

