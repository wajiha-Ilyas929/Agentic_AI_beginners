# 🤖 Agentic AI Workshop

### 🧩 Hands-on Introduction for University Students

Welcome to the **Agentic AI Workshop** — a 2-hour hands-on session designed for CS and SE students to explore how modern AI systems can reason, plan, use tools, and act autonomously.

---

## 🎯 Workshop Objectives

By the end of this workshop, you will:
- Understand **what Agentic AI is** and how it differs from traditional AI.
- Learn how to interact with **LLMs programmatically**.
- Build **LangChain-based AI workflows** including memory, tools, and retrieval (RAG).
- Get a roadmap to start your **career in Agentic AI**.

---

## 🧱 Repository Structure

```
agentic-ai-workshop/
│
├── notebooks/
│   └── Agentic_AI_Workshop.ipynb     ← Main hands-on notebook
│
├── .env.example                       ← Example environment file
├── requirements.txt                   ← All required dependencies
└── README.md                          ← You are here
```

---

## ⚙️ Setup Instructions

### 1. Clone this repo
```bash
git clone https://github.com/wajiha-Ilyas929/Agentic_AI_beginners.git
cd Agentic_AI_Workshop/
```

### 2. Create and activate a virtual environment
```bash
python -m venv .venv
source .venv/bin/activate    # (use `.venv\Scripts\activate` on Windows)
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

### 4. Add your API key(s)

Create a `.env` file in the root directory and include:

```bash
GROQ_API_KEY=your_groq_api_key_here
```

(Optional) If using OpenAI:
```bash
OPENAI_API_KEY=your_openai_api_key_here
```

### 5. Launch Jupyter Notebook
```bash
jupyter notebook
```
Then open `Agentic_AI_Workshop.ipynb`.

---

## 💻 Hands-On Topics Covered

| Section | Description |
|----------|--------------|
| **1. Simple LLM Calls** | Basic text generation using an API |
| **2. Prompt Engineering** | Using structured prompts for control |
| **3. Tools Integration** | Adding functions or APIs into your agent |
| **4. LangChain Basics** | Understanding LLMs, Chains, and Pipelines |
| **5. Chain Types** | Conversation, Summarization, and Map-Reduce |
| **6. Memory in LangChain** | Keeping conversational context |
| **7. RAG (Retrieval-Augmented Generation)** | Combining LLMs with your own data |

---

## 📚 Resources

- [LangChain Documentation](https://python.langchain.com/docs/)
- [Groq API Docs](https://console.groq.com/docs)
- [LangGraph](https://langchain-ai.github.io/langgraph/)
- [OpenAI Function Calling Guide](https://platform.openai.com/docs/guides/function-calling)
- [DeepLearning.AI — LangChain Course](https://www.deeplearning.ai/short-courses/langchain-for-llm-application-development/)

---

## 🚀 Career Roadmap in Agentic AI

1. Learn **Python + AI basics**
2. Explore **LLM APIs (OpenAI, Groq, Anthropic)**
3. Practice **LangChain & Agent frameworks**
4. Learn **tool integration & orchestration**
5. Deploy agents on cloud or API endpoints
6. Contribute to **open-source projects**

---

## 🧩 License

This workshop is distributed under the MIT License.  
Feel free to use and modify for educational purposes.

---

## ⭐ Acknowledgements

Special thanks to:
- [LangChain](https://github.com/langchain-ai/langchain)
- [Groq](https://groq.com)
- [OpenAI](https://openai.com)
- All students participating in this workshop 🚀
