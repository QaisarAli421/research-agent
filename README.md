# 🔬 ResearchMind – Multi-Agent AI Research System

ResearchMind is a multi-agent AI system that automates end-to-end research on any topic using LLM-powered agents.

It combines web search, content scraping, structured writing, and critique into a single intelligent pipeline.

---

## 🚀 Features

- 🔍 Search Agent – Finds relevant and recent information from the web  
- 📄 Reader Agent – Scrapes and extracts meaningful content  
- ✍️ Writer Agent – Generates structured research reports  
- 🧐 Critic Agent – Evaluates and improves the report  
- 🌐 Streamlit UI – Interactive frontend to run the pipeline  

---

## 🧠 Architecture

User Input → Search Agent → Reader Agent → Writer → Critic → Final Output

- Built using LangChain multi-agent system  
- Uses Groq LLM for fast inference  
- Tavily API for real-time web search  

---

## 🛠️ Tech Stack

- Python  
- LangChain  
- Groq API (LLM)  
- Tavily API (Search)  
- Streamlit (Frontend)  
- BeautifulSoup (Web scraping)  

---

## ⚙️ Setup Instructions

### 1. Clone the repo:
git clone https://github.com/QaisarAli421/research-agent.git
cd research-agent


---

### 2. Install dependencies

pip install -r requirements.txt


---

### 3. Create `.env` file

GROQ_API_KEY=your_groq_api_key
TAVILY_API_KEY=your_tavily_api_key


---

### 4. Run the app

#### Run UI

streamlit run app.py


#### Run CLI version

python pipeline.py


---

## 🔑 API Requirements

- Groq API key → for LLM  
- Tavily API key → for web search  

---

## 🌍 Deployment

The app can be deployed on:

- Streamlit Cloud  
- Render  
- Railway  

Make sure to add environment variables in deployment settings.

---

## 📸 Demo

(Add screenshots here after deployment)

---

## 🧠 Learnings

- Multi-agent orchestration using LangChain  
- Tool-based agent design  
- Prompt engineering for structured outputs  
- API integration (Groq + Tavily)  
- Streamlit deployment  

---

## 🚀 Future Improvements

- Add memory (vector database like Qdrant)  
- Multi-source scraping  
- Parallel agent execution  
- Better UI/UX  
- Caching results  

---

## 🤝 Contributing

Feel free to fork and improve this project.

---

## 📄 License

MIT License
