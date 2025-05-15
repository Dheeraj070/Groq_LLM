# Groq LLM Chatbot (Streamlit)

This is a simple chatbot interface built using **Streamlit** and powered by **Groq-hosted LLaMA3 models**. It supports streaming responses and maintains chat history during a session.

---

## Live Demo

**Try it here:** 
https://groqllm-xccpsdhcwfeydanwcs8sid.streamlit.app/


---

## Features

- Streamlit UI with chat interface
- Real-time streaming responses from Groq API
- Model: `llama3-8b-8192`
- Session-based message history
- Clean and interactive layout

---

## Getting Started

### 1. Clone the Repo

```bash
git clone https://github.com/yourusername/groq-llm-chatbot.git
cd groq-llm-chatbot
```

### 2. Create .env with Your API Key

Create a .env file:
```bash
GROQ_API_KEY=your_actual_groq_api_key_here
```

### 3. Install Requirements

```bash
pip install -r requirements.txt
```

### 4. Run the App Locally

```bash
streamlit run app.py
```

---


## Deployment

### To deploy on Streamlit Community Cloud:

- Push your code to a GitHub repository.


- Go to https://streamlit.io/cloud.


- Connect your GitHub repo.


- Add GROQ_API_KEY in the Secrets section of Streamlit cloud.


- Deploy and get a public link.



---



## Example Usage
```bash
User: "What is quantum computing?"
AI (LLaMA3): "Quantum computing is an area of computer science based on quantum theory..."
```


---