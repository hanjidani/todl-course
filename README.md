# 🎓 ToDL Course

**Theory of Deep Learning for Undergraduates** — a complete, self-paced curriculum that takes fresh BSc students with zero ML background to the research frontier.

> **Supervised by Dr. Mohammad Mahdi Mojahedian** (Sharif University of Technology) · Instructor: **Hossein Anjidani**

> **Philosophy:** maximum content diversity (books × papers) so students can use everything directly in their own research. No rush — **precision over speed.**

👉 **[Live website](https://hanjidani.github.io/todl-course/)** — same content, rendered with sidebar navigation, search, and diagrams.

---

## Why this course exists

1. **There is no reference textbook for deep-learning theory.** Classic ML books (Vershynin, Mohri, Shalev-Shwartz & Ben-David, Sra–Nowozin–Wright) stop at SVM-era foundations. This course combines them into a single path, spine-first with Arora's *Theory of Deep Learning* and Ye's *Geometry of Deep Learning*.
2. **Modern phenomena deserve rigorous treatment** — benign overfitting, NTK, neural collapse, score-based generative modeling, scaling laws — presented from the original papers, woven between book chapters.
3. **Research-ready output.** Every module ends with a reproduction workshop; every research team leaves with an open problem that has no answer in the literature.

## Course map

| Module | Name | Sessions | Pass criterion |
|---|---|---|---|
| M0 | Math, just enough | 1–4 | One-line Hoeffding proof + norm concentration in numpy |
| M1 | ML in 3 sentences (+ toolbox: trees, clustering) | 5–10 | Bias-variance by hand + derive the min-norm solution |
| M2 | Networks from scratch (+ GNN survey) | 11–17 | Hand-built 2-layer MLP + random-label experiment |
| M3 | Optimization (+ large-scale tradeoffs) | 18–24 | GD/SGD/Adam curves + measured SGD noise covariance |
| M4 | Nonconvex landscapes | 25–30 | "Symmetry ⇒ saddles" proof + loss-landscape picture |
| M5 | Rigorous generalization (+ multiclass, boosting, ranking) | 31–39 | VC of thresholds + a vacuous bound on a toy CNN |
| M6 | Interpolation mysteries | 40–47 | Benign-overfitting phase diagram + hard-margin simulation |
| M7 | Kernels & NTK | 48–55 | Empirical NTK on MNIST + "where NTK fails" answer |
| M8 | Beyond kernels | 56–63 | Neural-collapse simplex reproduction + lazy→feature sweep |
| M9 | Generative models | 64–75 | 2D diffusion + score-error rate test + why OT is its language |
| M10 | Transformers & scaling (+ attribution, RL) | 76–83 | Linear-transformer ICL reproduction + healthy skepticism |
| Capstone | Team projects | 6–8 weeks | Reproduction + a genuine research extension |

## What students read (books × papers)

**Books (6):** Arora et al., *Theory of Deep Learning* · Ye, *Geometry of Deep Learning* · Vershynin, *High-Dimensional Probability* (2nd ed.) · Shalev-Shwartz & Ben-David, *Understanding ML* · Mohri et al., *Foundations of ML* (2nd ed.) · Sra, Nowozin & Wright, *Optimization for ML* — plus surveys by Belkin ("Fit without fear") and Bartlett & Montanari, and Chewi–Niles-Weed–Rigollet's *Statistical Optimal Transport*.

**Papers (40+):** Zhang 2017 · Bartlett 2020 · Jacot 2018 · Arora 2019 · Papyan–Han–Donoho 2020 · Lu–Steinerberger · Hyvärinen 2005 · Song 2021 · Chen–Lee–Lu · Wibisono–Wu–Yang · Woodworth 2020 · Chizat–Bach · von Oswald 2022 · Kaplan 2020 · and more — see `docs/session-sequence`.

## Repository structure

```
README.md                 ← this landing page
docs/
├── book-chapters-1.md    ← chapter breakdown: Arora / Ye / SSBD
├── book-chapters-2.md    ← chapter breakdown: Vershynin / Mohri / Sra / surveys
├── course-map.md         ← modules, mastery criteria, pacing
├── session-sequence.md   ← 103 sessions, extensions interleaved (E1–E13), 4 split a/b pairs, Princeton block (S84–S97), COS511 track (S98–S99)
├── research-tracks.md    ← 3 research tracks + capstone ideas
├── notes.md              ← handwritten course notes (added as the course runs)
└── status.md             ← public status + contact
```

## Status

- ✅ Course design complete: chapter breakdown, module map, full session sequence
- 🔜 Course notes & session scripts (instructor's materials, being prepared)
- 🔜 Live session reports

> Note: the underlying book/paper **PDFs are kept out of this repository** (copyright). The planning, notes, and scripts live here.

---

*Instructor: Hossein Anjidani · [hosseinanjidani2@gmail.com](mailto:hosseinanjidani2@gmail.com) · Inspired by the NUS Theory-of-Deep-Learning reading group (Tan Kin Aun).*