# Temporal Gap Simulator – User Guidelines

## Quick Start

1. Open the page on your phone or computer.
2. You will see three sliders: **Tp (past)**, **Tf (future)** (visual only), and **Helix width (H)**.
3. The outcome area shows a random **0 or 1** based on the probability P(1).

---

## Understanding the Sliders

| Slider | Meaning | Effect when increased |
|--------|---------|----------------------|
| **Tp (1–9)** | Past strength, memory, learned experience | Higher → higher P(1) → faster decisions (shorter gap) |
| **Tf (1–9)** | Future potential (visual, not yet used in formula) | Reserved for future versions |
| **H (1–9)** | Helix width – number of parallel possibilities | Higher → lower P(1) → slower, more exploratory decisions |

---

## Reading the Output

- **P(1)** – probability that the random outcome will be 1.
- **Random outcome** – each time you move a slider, a new random sample is drawn. This mimics the quantum‑like “collapse” of possibility into reality.
- **Decision speed** – “fast” means the present gap is short (Tp > H); “slow” means the gap is long (Tp < H).

---

## Domain Presets

Use the dropdown to load pre‑configured settings:

- **VTOL** – high past, narrow helix → fast obstacle avoidance.
- **Economy** – balanced, moderate speed.
- **AI** – very high past, very narrow helix → deterministic inference.
- **Relationship** – high future, wide helix → slow, exploratory decisions.
- **Solar** – balanced with adaptive learning.

You can also **save your own preset** – click “Save preset”, give it a name, and it will be stored in your browser (IndexedDB).

---

## Practical Use Cases

| Scenario | Set Tp | Set H | Expected behaviour |
|----------|--------|-------|--------------------|
| **Drone collision avoidance** | 8 | 3 | Very fast decisions (P(1) high) |
| **Stock market trading** | 6 | 5 | Balanced, moderate speed |
| **Creative brainstorming** | 2 | 8 | Slow, exploratory (P(1) near 0.5) |
| **Emergency response** | 9 | 2 | Extremely fast, deterministic |

---

## Troubleshooting

- **The outcome does not change when I move sliders?**  
  Move any slider – a new random sample is drawn automatically.
- **I want to reset to default values.**  
  Click the **Reset** button.
- **How do I delete a saved preset?**  
  (Currently not implemented – will be added in V6.)

---

## Philosophy in Brief

The present moment is the only place where the past (Tp) and the future (Tf) meet. The width of the present (the “gap”) is determined by the balance between Tp and H. When Tp dominates, the gap is narrow – decisions are fast and predictable. When H dominates, the gap is wide – decisions are slow and creative.

**You are not just simulating probability. You are experiencing a model of consciousness itself.**

---

For deeper explanation, read the `README.md`.

By the waters of Enki – may your decisions be wise, whether fast or slow.
