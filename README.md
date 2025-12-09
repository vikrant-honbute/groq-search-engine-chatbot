# 🔎 Groq Search Engine Chatbot

A simple Streamlit app that lets you chat with an AI agent powered by **Groq + LangChain**.  
The agent can search the **web**, **Wikipedia**, and **arXiv** to answer your questions with up-to-date and research-backed information.

---

## 🚀 Features

- 💬 **Chat interface** built with Streamlit
- ⚙️ **Groq LLM** via `ChatGroq` (Llama 3 model)
- 🌍 **Web search** using DuckDuckGo
- 📚 **Wikipedia summaries** via `WikipediaAPIWrapper`
- 📄 **Research papers** via `ArxivAPIWrapper`
- 🧠 **LangChain Agent** (`ZERO_SHOT_REACT_DESCRIPTION`) that decides which tool to use
- 🔁 Conversation history stored in `st.session_state`

---

## 🧱 Tech Stack

- **Frontend:** Streamlit
- **LLM:** Groq (via `langchain-groq`)
- **Framework:** LangChain, LangChain Community tools
- **Tools:**
  - `DuckDuckGoSearchRun` – web search
  - `WikipediaQueryRun` – Wikipedia lookup
  - `ArxivQueryRun` – arXiv papers

---

## 📁 Project Structure

```bash
groq-search-chatbot/
├── app.py              
├── requirements.txt
└── README.md
