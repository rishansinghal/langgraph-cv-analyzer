# 🧠 CVision: Intelligent Resume Evaluation System (LangGraph + Mistral)

> A modular multi-agent AI system designed to evaluate resumes against job descriptions with explainable decision-making and automated communication.

---

## 🚀 Overview

**CVision** is an AI-powered resume evaluation pipeline that simulates a structured hiring workflow using multiple collaborating agents.

Instead of relying on keyword matching, CVision uses **LLM-driven semantic reasoning** to:
- Understand candidate profiles
- Compare them against job requirements
- Generate actionable hiring decisions
- Draft professional HR communication

This project demonstrates **real-world AI system design using LangGraph orchestration + Mistral LLM**.

---

## 🧩 Core Idea

Traditional hiring systems:
❌ Keyword-based  
❌ Rigid filtering  
❌ No reasoning  

CVision:
✅ Context-aware understanding  
✅ Multi-agent reasoning  
✅ Explainable decisions  

---

## ⚙️ System Architecture

```
Input (CV + Job Description)
        ↓
[Agent 1] Resume Analyzer
        ↓
[Agent 2] Job Matcher
        ↓
[Agent 3] Decision Engine
        ↓
[Agent 4] Email Generator
        ↓
Final Output (Decision + Email)
```

---

## 🧠 Agent Responsibilities

### 🔍 Resume Analyzer
- Extracts candidate skills, experience, and context

### 🎯 Job Matcher
- Compares candidate profile with job requirements
- Evaluates alignment

### ⚖️ Decision Engine
- Generates:
  - Accept
  - Reject
  - Consider

### ✉️ Email Generator
- Produces professional HR-style responses

---

## ✨ Features

- Multi-agent workflow using LangGraph
- Semantic CV evaluation (not keyword-based)
- Explainable hiring decisions
- Automated email drafting
- Modular and extensible architecture

---

## 🛠️ Tech Stack

| Component | Technology |
|----------|-----------|
| Language | Python 3.10+ |
| LLM | Mistral |
| Framework | LangGraph |
| LLM Integration | LangChain |
| Env Config | python-dotenv |

---

## 📦 Installation

```bash
git clone https://github.com/your-username/cvision-ai.git
cd cvision-ai
pip install -r requirements.txt
```

---

## 🔑 Environment Setup

Create a `.env` file:

```
MISTRAL_API_KEY=your_api_key_here
```

---

## ▶️ Usage

Run the system:

```bash
python main.py
```

Or explore notebook:

```bash
jupyter notebook tutorial.ipynb
```

---

## 📊 Sample Output

```
Candidate Score: 78%

Decision: CONSIDER

Reason:
- Strong technical skills
- Moderate domain experience

Generated Email:
"Dear Candidate,
Thank you for applying..."
```

---

## 🌍 Use Cases

- Resume screening automation
- AI-based hiring assistants
- HR workflow optimization
- Educational projects for LLM systems

---

## 🔮 Future Scope

- Candidate ranking system
- Batch resume processing
- ATS integration
- Dashboard (Streamlit)
- Bias detection module

---

## 🎯 Learning Outcomes

- Multi-agent AI design
- LangGraph orchestration
- Prompt engineering
- LLM-based evaluation pipelines

---


## 💡 Project Highlight

This project demonstrates how **LLMs can be structured into deterministic workflows** using agent-based architectures — a key concept in modern AI systems.

---

⭐ If you found this useful, consider giving it a star!
