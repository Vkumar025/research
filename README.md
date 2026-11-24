# 🔬 ResearchMind – Multi-Agent AI Research System

ResearchMind is an AI-powered multi-agent research assistant that automates the complete research workflow. It uses specialized AI agents to search the web, extract relevant information, generate a structured research report, and review the final output for quality.

Built with **Streamlit**, **LangChain**, and modern LLM workflows, the application provides an intuitive interface for generating comprehensive research reports on any topic.

---

## 🚀 Features

- 🔍 **Search Agent** – Finds recent and relevant information from the web.
- 📄 **Reader Agent** – Scrapes and extracts detailed content from the best sources.
- ✍️ **Writer Agent** – Generates a well-structured research report.
- 🧐 **Critic Agent** – Reviews the report and provides feedback for improvements.
- 🎨 Modern and responsive Streamlit UI.
- 📥 Download generated research reports in Markdown format.

---

## 🛠️ Tech Stack

- **Python**
- **Streamlit**
- **LangChain**
- **LangGraph**
- **Groq LLM**
- **Tavily Search API**
- **BeautifulSoup**
- **Requests**
- **Python Dotenv**

---

## 📂 Project Structure

```text
Multi_agent_research_system/
│
├── app.py                 # Streamlit application
├── agents.py              # AI agents
├── pipeline.py            # Research workflow
├── tools.py               # Search & scraping utilities
├── requirements.txt
├── .gitignore
└── README.md
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/Vkumar025/Multi_agent_research_system.git
cd Multi_agent_research_system
```

### 2. Create a virtual environment

Windows

```bash
python -m venv .venv
.venv\Scripts\activate
```

Linux / macOS

```bash
python3 -m venv .venv
source .venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

---

## 🔑 Environment Variables

Create a `.env` file in the project root.

```env
GROQ_API_KEY=your_groq_api_key
TAVILY_API_KEY=your_tavily_api_key
OPENAI_API_KEY=your_openai_api_key
```

---

## ▶️ Run the Application

```bash
streamlit run app.py
```

The application will open in your browser at:

```
http://localhost:8501
```

---

## 🔄 Workflow

```text
User Input
      │
      ▼
Search Agent
      │
      ▼
Reader Agent
      │
      ▼
Writer Agent
      │
      ▼
Critic Agent
      │
      ▼
Final Research Report
```

---

## 📸 Preview

You can add screenshots of the application here after deployment.

---

## 🤝 Contributing

Contributions, feature requests, and bug reports are welcome.

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to your branch
5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Ayush Gupta**

- GitHub: https://github.com/ayushgupta1123
- LinkedIn: Add your LinkedIn profile here
