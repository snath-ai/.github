<!--
This is the "shop window" for your entire Snath.ai company.
It's the first thing developers will see when they visit https://www.google.com/url?sa=E&source=gmail&q=github.com/snath-ai.
-->

<!-- 1. The Header & Slogan -->

<p align="center">
<!-- This points to the logo you just added to the 'assets' folder -->
<img src="https://www.google.com/search?q=https://raw.githubusercontent.com/snath-ai/.github/main/assets/snath-logo.png" width="120" alt="Snath.ai Logo">
<h1 align="center">Welcome to Snath.ai</h1>
<p align="center">
<b>We're building the "Glass Box" platform for AI you can actually trust.</b>
</p>
</p>

<!-- 2. The "Small Buttons" (Badges) - Your Social Proof -->

<p align="center">
<a href="https://www.google.com/search?q=https://pypi.org/project/lar-engine/">
<img alt="PyPI - Version" src="https://www.google.com/search?q=https://img.shields.io/pypi/v/lar-engine%3Fstyle%3Dfor-the-badge%26color%3Dblue">
</a>
<a href="https://www.google.com/search?q=https://pypi.org/project/lar-engine/">
<img alt="PyPI - Downloads" src="https://www.google.com/search?q=https://img.shields.io/pypi/dm/lar-engine%3Fstyle%3Dfor-the-badge%26color%3Dblueviolet">
</a>
<a href="https://www.google.com/search?q=https://github.com/snath-ai/lar/blob/main/LICENSE">
<img alt="PyPI - License" src="https://www.google.com/search?q=https://img.shields.io/pypi/l/lar-engine%3Fstyle%3Dfor-the-badge%26color%3Dgreen">
</a>
<a href="https://www.google.com/search?q=https://twitter.com/snathai"> <!-- TODO: Make sure you've registered @snathai on Twitter/X -->
<img alt="Follow on X" src="https://www.google.com/search?q=https://img.shields.io/twitter/follow/snathai%3Fstyle%3Dfor-the-badge%26logo%3Dx">
</a>
</p>

Our Philosophy: The "Glass Box" vs. The "Black Box"

The current generation of AI agents are "black boxes." When they fail, it's a mystery. Debugging them is a nightmare of guesswork, and auditing them is impossible.

We are building the "glass box" alternative.

Our products are built on the Lár Engine, an open-source, "define-by-run" framework. lar is a simple, "dumb" engine that runs one node at a time and logs every single state change. This isn't a "magic" AgentExecutor; it's a deterministic "assembly line."

This "glass box" philosophy means you can build agents that are:

100% Auditable: Get a complete "flight log" (history) for every run.

Easy to Debug: Instantly see which node failed and why (e.g., "Step 4: LLMNode - 429 Rate Limit").

Reliable: Build robust, multi-agent "assembly lines" and self-correcting loops that you can actually trust in production.

Our Projects

We're building the future of reliable AI in public.

1. The Engine (Open-Source)

This is the core of everything we do. It's the "PyTorch for Agents."

lar (The Lár Engine): The open-source, "glass box" framework. It's the tiny, powerful engine for building your agents.

pip install lar-engine

Give it a ⭐ to support the mission!

2. The "Killer Demos" (See lar in Action)

These are live, interactive Streamlit apps built with lar.

rag-demo (Live Demo): A self-correcting RAG agent that uses a local FAISS database and a "Critique Loop" to refine its own answers.

See the code snath-ai/rag-demo

customer-support-demo (Live Demo): A multi-agent orchestrator that uses a "Triage Agent" to route tasks to specialized "Billing" or "Tech Support" agents.

See the code snath-ai/customer-support-demo

3. The Product (Commercial)

Snath.ai: Our commercial, closed-source platform (currently in development). Snath.ai is the "Datadog for AI Agents"—a scalable, multi-user dashboard for deploying, auditing, and managing your lar agents in production.

snath-app (Frontend): (Private) The React/Vite frontend for the Snath.ai platform.

snath-api (Backend): (Private) The FastAPI backend that runs lar agents at scale.