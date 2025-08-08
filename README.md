# 📊 Financial Agent with Memory

An **AI-powered finance assistant** built using [Agno](https://docs.agno.com), [OpenAI GPT models](https://platform.openai.com/), [Yahoo Finance](https://pypi.org/project/yfinance/), and [DuckDuckGo search](https://duckduckgo.com/), with **persistent SQLite memory** for personalized, context-aware market insights.

---

## 🚀 Features
- 📈 **Market Analysis** – Real-time stock prices, historical data, and financial ratios.
- 🔍 **Web Search** – Fetch the latest market news and trends.
- 🧠 **Persistent Memory** – Remembers your preferences and previous chats using SQLite.
- 🖥 **Interactive Web UI** – Access via [Agno Playground](https://app.agno.com/playground).

---


---

## ⚙️ Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/YOUR_USERNAME/financial-agent-with-memory.git
cd financial-agent-with-memory


### 2. Create a visual environment
python -m venv .venv
source .venv/bin/activate   # macOS / Linux
# .venv\Scripts\activate    # Windows

### 3. Install Dependencies
pip install agno openai sqlalchemy fastapi uvicorn yfinance duckduckgo-search

### 4. Setup Agno
ag setup

### 5. Set Your OpenAI API Key
export OPENAI_API_KEY="your_api_key_here"   # macOS / Linux
# setx OPENAI_API_KEY "your_api_key_here"   # Windows

### 6. Run the application
python financial_agent_with_memory.py



