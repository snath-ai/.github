<p align="center">
  <img src="https://raw.githubusercontent.com/snath-ai/.github/main/assets/snath-logo.png" width="120" alt="Snath.ai Logo" />
</p>

<h1 align="center">Snath.ai</h1>
<p align="center"><em>Building transparent, auditable, and production‑ready AI systems.</em></p>

<p align="center">
  <a href="https://pypi.org/project/lar-engine/">
    <img alt="PyPI - Version" src="https://img.shields.io/pypi/v/lar-engine?style=for-the-badge&color=blue">
  </a>
  <a href="https://pypi.org/project/lar-engine/">
    <img alt="PyPI - Downloads" src="https://img.shields.io/pypi/dm/lar-engine?style=for-the-badge&color=blueviolet">
  </a>
  <a href="https://github.com/snath-ai/lar/blob/main/LICENSE">
    <img alt="Github - License" src="https://img.shields.io/github/license/snath-ai/lar?style=for-the-badge&color=green">
  </a>
  <a href="https://www.linkedin.com/company/snathai/">
    <img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-snathai-0077B5?style=for-the-badge&logo=linkedin">
  </a>
</p>

---

## 🚀 Our Philosophy: From “Black Box” to “Glass Box” AI

Most agent frameworks today behave like black boxes—hard to debug, impossible to audit, and unpredictable under load.

**Snath.ai is building the *glass box* alternative.**

At the core of everything is the **Lár Engine**: a minimal, deterministic, define‑by‑run execution engine that processes one node at a time and logs every state transition. No hidden abstractions. No magic. Total transparency.

This approach enables:

- **Full auditability:** Every run produces a complete, structured “flight log.”
- **Effortless debugging:** Identify exactly which node failed, when, and why.
- **Production reliability:** Build robust multi‑agent pipelines, self‑correcting loops, and deterministic workflows.

---

## 🧠 The Lár Engine (Open Source)

<p align="center">
  <img src="https://raw.githubusercontent.com/snath-ai/.github/main/assets/lar-logo.png" width="90" alt="Lár Logo" />
</p>

Lár is the lightweight engine that powers all Snath.ai agents.

- Define‑by‑run, stepwise orchestration  
- Deterministic execution  
- Structured logs for every state mutation  
- Simple primitives that work like “PyTorch for agents”

Install:

```
pip install lar-engine
```

If you find it useful, ⭐ the repo to support the project.

---

## 🧪 Demo Applications (“Killer Demos”)

Explore how Lár enables transparent and reliable agent workflows:

### **🔍 RAG Demo**
A self‑correcting retrieval‑augmented generation pipeline backed by FAISS and an automatic critique‑improve loop.

### **🎧 Customer Support Demo**
A multi‑agent orchestration system with a Triage Agent routing tasks to specialized Billing and Tech Support agents.

---

## 🏢 Snath.ai Platform (Commercial)

We’re building **Snath.ai**, a production platform for deploying, monitoring, and managing Lár‑powered agents at scale.

- Multi‑tenant dashboard  
- Real‑time auditing  
- Flight‑log inspection & analytics  
- Enterprise‑grade execution environment  

Components (private):

- **snath‑app** — React/Vite frontend  
- **snath‑api** — FastAPI backend orchestrating Lár agents at scale  

---

For updates, follow us on **LinkedIn** and ⭐ star the repositories to support our mission of making AI truly **transparent, trustworthy, and production‑ready**.