# Personal Agentic Query System

A **Production-Ready GenAI Application** built with modern AI and web technologies to create a personalized agentic chatbot experience.

## 🚀 Tech Stack

* **LangGraph (ReAct Agents)**
* **FastAPI** (Backend API)
* **Streamlit** (Frontend UI)
* **Groq & OpenAI** (LLMs)
* **LangChain** (Tool integrations)
* **Tavily** (Search Tool)
* **Uvicorn** (ASGI server)
* **Python**

---

## 🧠 Features

* Agentic AI chatbot powered by LangGraph and LLMs
* Search functionality via integrated Tavily API
* Clean separation of backend and frontend
* Interactive Swagger UI for API testing
* Model selection and system prompt customization in UI

---

## 🧩 Project Structure

```
project-root/
├── backend/            # FastAPI backend with AI agent setup
│   └── main.py         # API routes and schema models
├── frontend/           # Streamlit UI app
│   └── app.py          # Frontend app logic
├── utils/              # Utility functions and configurations
├── requirements.txt    # Python dependencies
└── README.md
```

---
## Technical Architecture
![image](https://github.com/user-attachments/assets/92a5b60d-3da1-418a-b2f6-6aecfe8c7ebe)
---

## 🔧 Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/agentic-ai-chatbot.git
cd agentic-ai-chatbot
```

### 2. Create Virtual Environment

```bash
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Set Environment Variables

Set your API keys for **Groq** and **Tavily** in a `.env` file or environment variables:

```env
GROQ_API_KEY=your-groq-api-key
TAVILY_API_KEY=your-tavily-api-key
OPENAI_API_KEY=your-openai-api-key
```

### 5. Run Backend (FastAPI)

```bash
uvicorn backend.main:app --reload
```

Access the API at: `http://localhost:8000`

Explore the API documentation at: `http://localhost:8000/docs`

### 6. Run Frontend (Streamlit)

```bash
streamlit run frontend/app.py
```

---

## 📦 Production Deployment

* Use **Uvicorn** with a production server like **Gunicorn**
* Containerize using Docker for scalable deployment

---

## 📬 Contributing

Pull requests and feedback are welcome! For major changes, open an issue first.

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

## 📍 Authors

* Built by \@athiyamanpro using OpenAI, LangGraph, Streamlit & FastAPI

---

## 📌 References

* [LangGraph Documentation](https://docs.langgraph.dev)
* [FastAPI](https://fastapi.tiangolo.com)
* [Streamlit](https://streamlit.io)
* [Groq](https://groq.com)
* [OpenAI](https://openai.com)
* [Tavily](https://tavily.com)
