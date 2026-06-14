<div align="center">
  <img src="https://raw.githubusercontent.com/snath-ai/.github/main/assets/lar-logo.png" width="180" alt="Lár Engine" />
  <h1>Lár Engine</h1>
  <p><strong>The "Glass Box" Agent Orchestration Framework.</strong></p>
  
  <a href="https://snath.ai">
    <img src="https://img.shields.io/badge/Website-snath.ai-0052CC?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Website" />
  </a>
  <a href="https://docs.snath.ai">
    <img src="https://img.shields.io/badge/Documentation-Official-339933?style=for-the-badge&logo=readthedocs&logoColor=white" alt="Documentation" />
  </a>
</div>

---

# Snath AI

Open-source cognitive architecture for transparent, self-improving AI systems.

We build the infrastructure layer — the execution engine, the routing
primitives, the memory architecture, the compliance backbone — for AI systems
that operate in environments where failure has real consequences.

Everything published here is Apache 2.0. The research is open. The architecture
is open. The audit trails are the point.

---

## Research

Five papers establishing the formal foundations of the Lár architecture:

| # | Paper | DOI | Published |
|---|---|---|---|
| 1 | **Divergence Is Not Noise:** Multi-Stream Routing Without Modal Fusion and the Safety-Learning Equivalence | [10.5281/zenodo.20525227](https://doi.org/10.5281/zenodo.20525227) | Jun 2026 |
| 2 | **Universal Cognitive Routing:** A Forward-Compatible Architecture for Heterogeneous AI Systems | [10.5281/zenodo.20453093](https://doi.org/10.5281/zenodo.20453093) | Jun 2026 |
| 3 | **The Lár Training Loop:** Routing Flags as Gradient Signals, Self-Curating Curriculum, LoRA Adapter Integration, Sketched Isotropic Gaussian Regularization, and Annotation-Free Continual Learning | [10.5281/zenodo.20613758](https://doi.org/10.5281/zenodo.20613758) | Jun 2026 |
| 4 | **The Encoder Is Not the Memory:** World-Grounded Difficulty Representations for Encoder-Invariant and Predictive Continual Learning | [10.5281/zenodo.20614051](https://doi.org/10.5281/zenodo.20614051) | Jun 2026 |
| 5 | **Physics Assumption Violations:** Label-Free Detection via Concept-Space Routing in Deployed Robotic Systems | [10.5281/zenodo.20682615](https://doi.org/10.5281/zenodo.20682615) | Jun 2026 |

The central result across the series: **the invariants that make a routing
system safe are mathematically identical to the invariants that make
inter-model disagreement a valid, label-free training curriculum.** Safety
and learning are not a trade-off. They are the same mechanism — and it holds
from vision-language pairs to physical robotic dynamics.

---

## Repositories

### [snath-ai/lar](https://github.com/snath-ai/lar) — The Glass-Box Agent Engine
Deterministic, define-by-run graph execution. 13 EU AI Act compliance
primitives. Three HMAC-signed audit artefacts on every run. 21 CFR Part 11
aligned. The only open-source agent framework that produces forensic evidence
a regulator can actually inspect.

### [snath-ai/Lar-JEPA](https://github.com/snath-ai/Lar-JEPA) — Ten-ABC Cognitive Architecture
Ten Abstract Base Classes. 33 formal invariants. `AbstractDivergenceRouter`
(V1–V6) routes by geometric divergence between independent latent streams —
content-blind by invariant. Domain isomorphism proven across crystal physics,
geophysics, computer networks, medical imaging, and quantitative finance.
One architecture. No domain-specific modification required.

### [snath-ai/snath-robotics](https://github.com/snath-ai/snath-robotics) — Physical World Validation
End-to-end validation of the V1–V6 routing contract on genuine physical
dynamics. MuJoCo Walker2d-v5: 83% COMMIT on normal terrain, 95% PAV
detection on ice terrain, 65% divergence reduction after one DMN cycle —
zero labels at inference, adaptation, or fleet propagation.

### [snath-ai/DMN](https://github.com/snath-ai/DMN) — Bicameral Memory Architecture
A biologically-inspired Default Mode Network for persistent AI memory.
3-tier architecture (Hot/Warm/Cold). Background consolidation during idle
periods. The Dream Loop solves catastrophic forgetting architecturally,
not with prompt tricks.

---

## The Self-Improving Loop
**Route → Flag disagreement → Build D_hard curriculum
→ Train LoRA adapter → Improve routing → repeat**

No human labels in the critical path. The routing invariants that prevent
bad decisions are the same invariants that identify the most valuable
training examples. The system improves itself using its own uncertainty
as the curriculum.

---

## Principles

- Never use an LLM to police another LLM. Use code.
- An approval is a cryptographic signature of a specific state, not a flag.
- Determinism is not a constraint. It is the product.
- Domain-agnostic by proof, not by claim.

---

## Community

- **[Issues](https://github.com/snath-ai/lar/issues)** — bugs and feature requests
- **[Discussions](https://github.com/snath-ai/lar/discussions)** — architecture patterns and ideas
- **[Docs](https://docs.snath.ai)** — documentation and guides

---

<div align="center">
  <p>Apache 2.0 · <a href="https://snath.ai">snath.ai</a> · <a href="https://docs.snath.ai">docs.snath.ai</a></p>
</div>
