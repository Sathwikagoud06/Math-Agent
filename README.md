
# Human-in-the-Loop: Feedback-Based Math Agent

## 🔍 Overview
This project implements an intelligent math-solving agent using an Agentic-RAG architecture. It incorporates a knowledge base, fallback web search, input-output guardrails, and a human-in-the-loop mechanism for iterative feedback.

## 💡 Features
- VectorDB-powered Knowledge Base for math Q&A
- Web search fallback using Tavily API
- Trafilatura + NLP for answer extraction
- Guardrails for secure inputs/outputs
- DSPy-based feedback loop
- Streamlit frontend deployment

## 🧠 Sample Queries
### From Knowledge Base:
- Solve the quadratic equation x² - 5x + 6 = 0
- What is the derivative of x³?
- Integrate sin(x)dx

### Web Search Examples:
- What is the Riemann Hypothesis?
- Explain Z-score normalization
- Who invented Laplace Transform?

## 🔄 Human-in-the-Loop
If the AI answer is incorrect or unclear, human feedback is used to improve the system by adjusting prompt templates and response logic dynamically.

## 📊 Technologies Used
- Python, Streamlit
- Langchain, DSPy
- Qdrant VectorDB
- Serper/Tavily API
- Trafilatura
