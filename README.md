<div align="center">

# κυνικός

**Epistemic Immune System**

*"The dog who speaks truth, loyal to verification, not comfort"*

[![CYNIC](https://img.shields.io/badge/CYNIC-v0.1.0-gold?style=flat-square)](https://github.com/zeyxx/CYNIC)
[![Rust](https://img.shields.io/badge/Rust-kernel-orange?style=flat-square)](https://github.com/zeyxx/CYNIC/tree/main/cynic-kernel)
[![φ](https://img.shields.io/badge/max%20confidence-61.8%25-blue?style=flat-square)](#phi-bounding)

</div>

---

## Philosophy

```
φ distrusts φ — no claim deserves absolute confidence
```

Building systems where independent AI validators reach consensus under mathematical doubt.
Multiple models evaluate content through 6 philosophical axioms — and **no score can exceed 61.8%** (golden ratio inverse). Disagreement between validators is a discovery signal, not a failure.

## Currently Building

**[CYNIC](https://github.com/zeyxx/CYNIC)** — Epistemic consensus engine in Rust

- **Multi-Validator Consensus** — Independent "Dogs" (Gemini, Qwen, Gemma, heuristics) evaluate in parallel, scores merged via trimmed-mean with anomaly detection
- **6 Axiom Scoring** — Fidelity, Phi, Verify, Culture, Burn, Sovereignty — geometric mean → phi-bounded Q-Score
- **Cognitive Crystallization (CCM)** — Patterns that survive 21+ evaluation cycles crystallize into persistent knowledge (Fibonacci thresholds)
- **Hexagonal Architecture** — Domain-pure Rust kernel, ports & adapters, zero framework leakage
- **Model-Agnostic Pipeline** — Any OpenAI-compatible backend (local llama.cpp, Gemini API, HuggingFace) via ChatPort trait
- **Circuit Breakers** — Per-validator fault isolation, automatic recovery

### The Six Axioms

```
┌─────────────────────────────────────────────────┐
│  FIDELITY      Is this faithful to truth?       │
│  PHI           Structurally harmonious?          │
│  VERIFY        Can it be tested or refuted?      │
│  CULTURE       Does it honor traditions?         │
│  BURN          Efficient? Minimal waste?         │
│  SOVEREIGNTY   Preserves agency and freedom?     │
└─────────────────────────────────────────────────┘
```

### Phi-Bounding

Every score is capped at **φ⁻¹ = 0.618** — the golden ratio inverse. This is structural, not a bug. Verdicts map to thresholds derived from φ:

| Verdict | Threshold | Meaning |
|---------|-----------|---------|
| **Howl** | ≥ 0.521 | Exceptional |
| **Wag** | ≥ 0.382 | Good |
| **Growl** | ≥ 0.236 | Questionable |
| **Bark** | < 0.236 | Rejected |

## Stack

`Rust` `Axum` `Tokio` `SurrealDB` `React` `TypeScript` `MCP (rmcp)` `Tailscale`

## Numbers

```
5000 LOC Rust kernel · 80+ tests · 134 commits in 7 days
6 axioms · φ-bounded scoring · circuit breakers · CCM crystallization
REST API · MCP server · multi-model inference · hexagonal architecture
```

---

<div align="center">

*The dog is the philosopher. The philosopher is the dog.*

<sub>France · φ⁻¹ = 61.8%</sub>

</div>
