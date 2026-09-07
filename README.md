# Supply_Chain_Disruptions_Copilot

An **agentic AI-powered Supply Chain Disruption Copilot** designed to help organizations detect supply chain disruptions, understand their impact, identify root causes, and explore potential recovery strategies.

The project combines **LLMs, knowledge graphs, vector search, and agentic orchestration** to move beyond disruption detection toward actionable decision support.

> **Detect → Understand → Plan → Simulate → Explain**

## 🚀 What Problem Are We Solving?

Supply chain disruptions can originate from events such as:

* 🏭 Manufacturing plant shutdowns
* 🌊 Natural disasters
* 🚢 Logistics and transportation disruptions
* 📦 Supplier failures
* 🌍 Geopolitical or regional events

The challenge is not simply detecting that a disruption occurred.

The bigger question is:

**"What does this disruption mean for my supply chain, and what should I do next?"**

This project explores how AI agents can help answer that question.

## 🧠 How It Works

The copilot follows an agentic workflow:

```text
Disruption / Event
       ↓
Disruption Detection
       ↓
Impact Analysis
       ↓
Root Cause Analysis
       ↓
Recovery Planning
       ↓
What-if Simulation
       ↓
Explanation
```

Each stage contributes to building a more complete picture of the disruption and its potential consequences.

## 🏗️ Architecture

The initial prototype uses:

* **LangGraph** — Agent orchestration
* **LLM / GenAI** — Reasoning and decision support
* **Neo4j** — Supply chain knowledge graph
* **Qdrant** — Vector database for semantic retrieval
* **Sentence Transformers** — Embeddings
* **FastAPI** — Backend API
* **React + TypeScript + Vite** — Frontend
* **Cytoscape.js** — Supply chain graph visualization

### Agent Flow

```text
                ┌──────────────────────┐
                │  Disruption Event    │
                └──────────┬───────────┘
                           ↓
                ┌──────────────────────┐
                │ Disruption Detection │
                └──────────┬───────────┘
                           ↓
                ┌──────────────────────┐
                │   Impact Analysis    │
                └──────────┬───────────┘
                           ↓
                ┌──────────────────────┐
                │   Root Cause Agent   │
                └──────────┬───────────┘
                           ↓
                ┌──────────────────────┐
                │ Recovery Planner     │
                └──────────┬───────────┘
                           ↓
                ┌──────────────────────┐
                │ What-if Simulation   │
                └──────────┬───────────┘
                           ↓
                ┌──────────────────────┐
                │    Explainer Agent   │
                └──────────────────────┘
```

## 🔍 Example

A semiconductor manufacturing plant becomes unavailable due to flooding.

The copilot can:

1. Detect the disruption
2. Identify affected suppliers and downstream dependencies
3. Estimate the potential impact
4. Analyze the disruption's root cause
5. Identify alternative suppliers or recovery paths
6. Simulate potential recovery scenarios
7. Explain the recommended path and its expected impact

The goal is to provide **traceable, explainable decision support**, rather than simply generating a recommendation.

## 🎯 Key Idea

Traditional supply chain analytics often answer:

> **"What happened?"**

This project explores a more proactive question:

> **"What could happen next, and what are my options?"**

That is where we see the potential of combining **agentic AI + knowledge graphs + RAG + simulation** for supply chain decision intelligence.

## 🛠️ Project Status

🚧 **Initial Prototype / Experimental**

This repository represents the initial version of the project and is actively evolving.

Current focus areas include:

* Agent orchestration
* Supply chain graph reasoning
* Retrieval-augmented analysis
* Recovery planning
* What-if scenario simulation
* Explainability and traceability

## 🔮 Future Direction

The longer-term vision is to evolve the copilot from **disruption detection** toward **decision intelligence**:

```text
Detect
  ↓
Understand
  ↓
Predict
  ↓
Generate Recovery Options
  ↓
Simulate What-if Scenarios
  ↓
Compare Alternatives
  ↓
Recommend + Explain
```

Ultimately, the objective is to help supply chain teams **evaluate recovery paths before acting on them**.

## 🤝 Contributions & Feedback

This is an experimental project and feedback is welcome.

If you're working in **Supply Chain, AI/ML, Agentic AI, Operations Research, or Decision Intelligence**, I'd particularly love to hear your thoughts on:

* What additional signals should the copilot consider?
* How should recovery recommendations be validated?
* What would make the system trustworthy enough for real-world decision-making?

---

**Built as an exploration of Agentic AI for Supply Chain Resilience and Decision Intelligence.**
