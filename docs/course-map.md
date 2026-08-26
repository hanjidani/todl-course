---
layout: default
title: Course map
nav_order: 2
has_children: false
---

# Course map — modules, mastery, pacing

> 13 modules, 74 sessions, plus Track B (parallel seminar) and a 6–8 week capstone. Pace is **module-based, not hour-based**: pass the mastery criterion, then move on.

## Module flow

```mermaid
flowchart LR
    M0["M0 · Math"] --> M1["M1 · ML basics"] --> M2["M2 · Networks"] --> M3["M3 · Optimization"] --> M4["M4 · Landscapes"]
    M4 --> M5["M5 · Generalization"] --> M6["M6 · Interpolation"] --> M7["M7 · Kernels and NTK"]
    M7 --> M8["M8 · Beyond kernels"] --> M9["M9 · Generative"] --> M10["M10 · Transformers"]
    TB["Track B · Statistics"] -. parallel .-> M9
    M10 --> CAP["Capstone"]
    M9 --> CAP
    M7 -. "lazy/rich bridge" .-> M8
    style M0 fill:#eef,stroke:#99b
    style CAP fill:#efe,stroke:#9b9
```

<script src="https://cdn.jsdelivr.net/npm/mermaid@10.9.8/dist/mermaid.min.js"></script>
<script>
  (function () {
    var nodes = document.querySelectorAll("code.language-mermaid");
    if (nodes.length === 0) { return; }
    if (window.mermaid) { mermaid.initialize({ startOnLoad: false }); }
    window.addEventListener("load", function () {
      if (window.mermaid) { mermaid.run({ nodes: nodes }); }
    });
  })();
</script>

## Modules & mastery criteria

| Mod | Name | Sessions | Mastery criterion (must-pass) |
|---|---|---|---|
| M0 | Math, just enough | 1–4 | One-line Hoeffding proof + norm concentration in numpy |
| M1 | ML in 3 sentences | 5–8 | Bias-variance by hand + derive the min-norm solution |
| M2 | Networks from scratch | 9–14 | Hand-built 2-layer MLP + random-label experiment (Zhang 2017) |
| M3 | Optimization | 15–20 | GD/SGD/Adam curves + measured SGD noise covariance |
| M4 | Nonconvex landscapes | 21–26 | "Symmetry ⇒ saddles" proof + loss-landscape visualization |
| M5 | Rigorous generalization | 27–32 | VC of thresholds + a **vacuous** bound on a toy CNN |
| M6 | Interpolation mysteries | 33–40 | Benign/harmful phase diagram + hard-margin simulation |
| M7 | Kernels & NTK | 41–48 | Empirical NTK on MNIST + a reasoned "where NTK fails" answer |
| M8 | Beyond kernels | 49–56 | NC1–NC4 simplex reproduction + lazy→feature width sweep |
| M9 | Generative models | 57–68 | 2D diffusion + score-error rate test + "why OT is its language" |
| M10 | Transformers & scaling | 69–74 | Linear-transformer ICL reproduction + healthy skepticism on emergence |
| Track B | Advanced statistics seminar | B1–B6 | One 30-minute presentation, hand-built slides |
| Capstone | Team projects | 6–8 weeks | Reproduction + genuine research extension |

## Course storyline

The sequence is one continuous argument, told in four acts:

1. **Act I — Build the machine (M0–M3).** Math that is *just enough* → what a learning machine is → build a network with your own hands → understand the optimizer that drives it. Session 12 plants the mystery that the course will resolve: *a network fits pure noise perfectly and still generalizes.*
2. **Act II — Why does it work? (M4–M6).** Nonconvex landscapes and why escaping them is easy in practice → the rigorous language of generalization (PAC, VC, Rademacher) → then the resolution of the mystery: double descent, benign overfitting, and implicit bias. Session 12's hook pays off in session 35.
3. **Act III — What does a trained network look like? (M7–M8).** The kernel regime: infinite width makes a network a linear, convex object (NTK) → then the turn: real networks exit the kernel regime, learn features, and collapse into a rigid simplex geometry (neural collapse).
4. **Act IV — Frontiers (M9–M10).** Generative modeling as score + optimal transport → transformers: in-context learning turns out to be gradient descent in disguise — closing the loop back to Act I. Track B runs alongside for the statistical foundations, and the extension sessions E1–E13 complete every remaining chapter of every book at the point where its prerequisites exist.

## Hard prerequisite chains (do not jump)

- SSBD/Mohri basics → M5 → M6 (interpolation needs rigorous generalization language)
- Kernels (M7, sessions 41–42) **before** NTK (43–44)
- NTK (M7) before lazy-vs-rich (47) and before neural collapse (M8)

## Per-module structure

Every module ends with a **student seminar session** — papers are assigned 2 weeks ahead and presented by the students (15–20 min + 10 min discussion each).

## Seminars

Seminars (marked 🗣 in the [session sequence](session-sequence.html)) are **student-led sessions**: the presenter explains one paper — the problem, the main claim, the proof idea, and why it matters — pen-first, while the class asks questions and the instructor fills gaps only where needed. Several students present per session, so each module covers 3–6 papers beyond the lectures.

### How seminar papers were chosen

Seminar assignments were selected deliberately (not randomly from the literature), following five rules:

1. **Prerequisite guarantee** — a paper is assigned only after every tool it needs was built in earlier sessions. The sequence never jumps: e.g., Jacot (NTK) only after kernels & RKHS; Bartlett et al. 2020 (benign overfitting) only after PAC/Rademacher.
2. **Canonical and clean** — each paper is the originating or clearest statement of one course theme: expressivity → Cybenko · depth → Telgarsky · implicit bias → Soudry / Gunasekar · lazy-vs-rich → Woodworth / Chizat–Bach · collapse geometry → Lu–Steinerberger · score-estimation rates → Wibisono–Wu–Yang · in-context learning → von Oswald / Garg · induction heads → Olsson.
3. **Complementarity per module** — theory and experimental papers are paired (e.g., M2: Cybenko + Telgarsky + Zhang's random-label experiment; M6: Belkin/Hastie phenomena + Soudry/Gunasekar theory).
4. **Feasibility for beginners** — statements are self-contained, the required math was already built inside the course, and the experiments are reproducible on a laptop CPU. Genuinely hard statistical papers (gradient flows for empirical Bayes, learning GMMs via diffusion) are deliberately **not** seminar material — they live in the 🔬 research corner.
5. **Research payoff** — seminar papers feed the [research tracks](research-tracks.html): each one leaves an open question that capstone teams can attack (e.g., *why does SGD reach the simplex ETF?*, *score-estimation rates on manifold-supported data?*).