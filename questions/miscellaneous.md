# GenAI & Agentic AI Interview Questions

A curated repository of interview questions covering Retrieval-Augmented Generation (RAG), Agentic AI, LLMs & Prompting, and Python/SQL coding challenges.

---

## 🤖 GenAI & RAG

*   **Pipeline Architecture:** Walk me through your RAG pipeline — from ingestion to retrieval to generation.
*   **Chunking Strategy:** How do you handle chunking? What chunk size works best?
*   **Vector DB Comparison:** Why ChromaDB? When would you choose Pinecone over it?
*   **Evaluation Metrics:** How do you evaluate RAG performance? (e.g., RAGAS, TruLens, human eval).
*   **Failure Modes:** What are the typical failure modes of RAG? (e.g., bad retrieval $\rightarrow$ bad generation, hallucination).

---

## 🧠 Agentic AI

*   **Definition:** What is an AI Agent? How is it fundamentally different from a simple sequential LLM call?
*   **Multi-Agent Design:** How do you design, coordinate, and manage a multi-agent system?
*   **Tooling & Execution:** How do you handle autonomous tool calling, function parsing, and decision-making?
*   **Orchestration Frameworks:** What frameworks have you used? (e.g., LangChain, LangGraph, CrewAI, AutoGen).
*   **Agent Evaluation:** How do you reliably evaluate an agent's performance, routing logic, and loop termination?

---

## 💬 LLMs & Prompting

*   **Prompt Architecture:** What is the difference between a system prompt and a user prompt?
*   **State Management:** How do you handle conversation memory/context windows with stateless LLMs?
*   **Reasoning Techniques:** What is Chain-of-Thought (CoT) prompting? When and why do you use it?
*   **Hyperparameter Tuning:** Why would you use a lower temperature (e.g., `temperature = 0.3`) for deterministic tasks like code generation?
*   **Security & Guardrails:** How do you prevent adversarial prompt injection and jailbreaking?

---

## 🐍 Python & SQL Coding

### 1. Identify Duplicates in Python
Write a function to check if a list contains duplicates.

```python
def has_duplicates(lst: list) -> bool:
    # Your code here
    pass