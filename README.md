# 🧠 Multi-Agent AI Web Developer Assistant (Frontend + Backend)

This project is an AI-powered chatbot that can route technical queries to different specialized agents:
- **Frontend Expert**
- **Backend Expert**
- **Web Developer Coordinator (Router Agent)**

Built using:
- [Chainlit](https://docs.chainlit.io/) for UI
- OpenAI-style client for Gemini (via `AsyncOpenAI`)
- Multi-agent logic via `Runner`, `Agent`, and `RunConfig` abstractions

---

## 📁 Project Structure

Runner_Openai_Agents_SDK_multi_agents/
│
├── main.py # Entry point for Chainlit app
├── .env # Environment variables (e.g. API keys)
├── agents/ # Custom agent logic and Runner
│ ├── init.py # Should contain Agent, Runner, etc.
│ └── (other agent files)
└── README.md
