## ⚙️ Setup Instructions

---

### 1. Clone the Repository
```bash
git clone https://github.com/YOUR_USERNAME/financial-agent-with-memory.git
cd financial-agent-with-memory
```

---

### 2. Create a virtual environment

```bash
python -m venv .venv
source .venv/bin/activate   # macOS / Linux
# .venv\Scripts\activate    # Windows
```

---

### 3. Install Dependencies
```bash
pip install agno openai sqlalchemy fastapi uvicorn yfinance duckduckgo-search
```

---

### 4. Setup Agno
```bash
ag setup
```

---

### 5. Set Your OpenAI API Key
```bash
export OPENAI_API_KEY="your_api_key_here"   # macOS / Linux
# setx OPENAI_API_KEY "your_api_key_here"   # Windows
```

---

### 6. Run the application
```bash
python financial_agent_with_memory.py
```