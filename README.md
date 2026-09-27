# 🤖 Agentic AI & LangGraph — Interactive Learning Hub

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![No Dependencies](https://img.shields.io/badge/dependencies-zero-brightgreen?style=flat)](.)
[![License: MIT](https://img.shields.io/badge/License-MIT-purple?style=flat)](LICENSE)

> **An interactive, self-contained web application for learning Agentic AI, LangChain, RAG, and LangGraph** — built from the complete course curriculum by [Akarsh Vyas](https://www.youtube.com/@SheryiansAI) at Sheryians AI School.

---

## 🎯 What Is This?

A **premium, single-file learning hub** (zero dependencies, zero install, zero backend) that transforms dense course notes into **interactive experiences**:

- 🌡️ **Temperature Simulator** — Adjust T and watch Softmax probabilities shift live
- 📐 **Cosine Similarity Lab** — Drag 2D vectors on a canvas, see similarity update in real-time
- ⚖️ **MMR λ Explorer** — Tune the Maximal Marginal Relevance lambda parameter
- 🔄 **ReAct Loop Animator** — Step-by-step Thought → Action → Observation simulation
- 🕸️ **LangGraph Graph Animator** — Animated multi-agent state graph
- ✂️ **Chunk Visualizer** — See how chunk_size & chunk_overlap split a document
- 🚀 **6 Project Walkthroughs** — Complete execution flow for every course project
- 🧠 **15-Question Quiz** — Instant feedback with detailed explanations

---

## 🛠️ Tech Stack

| Layer | Technology | Why |
|---|---|---|
| **Structure** | HTML5 (semantic) | Universal, zero dependencies |
| **Styling** | Vanilla CSS (custom properties) | Glassmorphism, micro-animations, full control |
| **Logic** | Vanilla JavaScript ES6+ | No build step, instant load, lightweight |
| **Fonts** | Google Fonts (Inter + JetBrains Mono) | Premium typography |
| **Canvas** | HTML5 Canvas API | Draggable cosine similarity visualizer |
| **Math** | Native JS `Math.exp`, `Math.hypot` | Softmax, dot product, cosine sim calculations |
| **Animations** | CSS `@keyframes` + JS `setInterval` | ReAct loop, RAG flow, LangGraph animator |

**What is NOT used:** React, Vue, Angular, Tailwind, npm, webpack, any CDN library, or any backend.

---

## 📁 Repository Structure

```
langchain-langgraph-course/
├── index.html          ← Complete interactive learning app (single file)
├── README.md           ← This file
└── LICENSE             ← MIT License
```

---

## 🚀 How to Run

**Option 1 — Just open it:**
```bash
# No install needed. Just double-click index.html in your file explorer
# Or open it in any modern browser (Chrome, Firefox, Edge, Safari)
```

**Option 2 — Serve locally:**
```bash
# Python (built-in)
python -m http.server 8080

# Node.js (npx)
npx serve .
```

Then open `http://localhost:8080` in your browser.

---

## 📚 Course Coverage

| Module | Topic | Interactive Feature |
|---|---|---|
| **1.1** | LLM Anatomy & Tokenization | Four Eras of AI cards |
| **1.2** | Temperature, Top-P, Top-K | 🌡️ Live Softmax simulator |
| **1.3** | Prompt Engineering | Accordion with 5 structural blocks |
| **1.4** | LangChain & LCEL | Pipe operator chain visualization |
| **2.1** | Why RAG? | Animated pipeline flow |
| **2.2–2.3** | Chunking & Splitting | ✂️ Interactive chunk visualizer |
| **2.4** | Vector Embeddings | 📐 Draggable 2D canvas lab |
| **2.5–2.6** | Vector Stores & RAG Chain | Chroma / FAISS / Pinecone comparison |
| **2.7** | MMR Advanced Retrieval | ⚖️ λ parameter explorer with chunk ranking |
| **3.1–3.2** | Tools & Function Calling | 5-step loop breakdown |
| **3.3–3.4** | ReAct Framework | 🔄 Animated Thought→Action→Observation |
| **4.3** | LangGraph Architecture | 🕸️ Animated StateGraph |
| **4.1–4.2** | Multi-Agent Topologies | 6 topology cards with detail panels |
| **Projects** | 6 Course Projects | Tabbed walkthrough with execution flows |
| **Module 6** | 6-Step Agent Blueprint | Step matrix with descriptions |
| **All** | Key Formulas | 4-formula cheatsheet + .pkl perf table |
| **All** | Knowledge Check | 🧠 15-question quiz with explanations |

---

## 🎓 Course Reference

| Resource | Link |
|---|---|
| **Course Video** | [Complete Agentic AI Course with LangGraph](https://www.youtube.com/watch?v=ytsHs-KZHVI) |
| **Instructor** | [Akarsh Vyas — Sheryians AI School](https://www.youtube.com/@SheryiansAI) |
| **GitHub (Course Code)** | [AkarshVyas/Agentic-AI-youtube](https://github.com/AkarshVyas/Agentic-AI-youtube) |

---

## 📐 Key Formulas Implemented

```
1. Softmax with Temperature:   P(wᵢ) = exp(zᵢ/T) / Σ exp(zⱼ/T)

2. Cosine Similarity:          CosineSim(A,B) = (A·B) / (||A|| × ||B||)

3. MMR:                        argmax[ λ·Sim₁(dᵢ,q) − (1−λ)·max Sim₂(dᵢ,dⱼ) ]

4. ReAct Loop:                 Input → (Thought → Action → Observation)* → Answer
```

---

## 🧠 Projects Covered

| # | Project | Key Concepts |
|---|---|---|
| 1 | Sequential Content Pipeline | Linear StateGraph, 3-node pipeline |
| 2 | Parallel Safety Analyzer | Fan-out, Annotated Reducer, parallel branches |
| 3 | College RAG Assistant | Conditional edges, FAISS, multi-PDF retrieval |
| 4 | LinkedIn Post Generator | Iterative loop, TavilySearch tool, reviewer |
| 5 | Human-in-the-Loop | `interrupt()`, `Command(resume=...)`, MemorySaver |
| 6 | AI Video RAG Assistant | YouTube transcript, .pkl caching, timestamp nav |

---

## 📄 License

MIT License — feel free to use, modify, and distribute for educational purposes.

---

<div align="center">
  <strong>Built with ❤️ using pure HTML, CSS & JavaScript — zero frameworks, zero dependencies.</strong>
</div>
