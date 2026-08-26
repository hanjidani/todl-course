---
layout: default
title: Session sequence
nav_order: 3
---

# Session sequence — 83 sessions, fully interleaved

> Each row = one session (2h equivalent). Extension sessions (E-tags) are **numbered inline** — they are real sessions added to the flow, not side notes. Reading assignments (📖 homework) are listed per module without a number.
> Roles: 🎓 in-class · 🗣 student seminar · 📖 homework · 🔬 research corner · 📋 teacher reference. Papers are interleaved between book chapters at the point where they belong.

## M0 — Math, just enough (1–4)

| # | Source | Topic |
|---|---|---|
| 1 | Vershynin 2e ch2 · 🎓 | Hoeffding, Chernoff, subgaussian/subexponential, Bernstein |
| 2 | Vershynin 2e ch3 · 🎓 | Norm concentration, random vectors, PCA |
| 3 | Ye ch1 (sel.) + Arora Basic Setup · 🎓 | Matrix/vector calculus, convex optimization, useful facts |
| 4 | Mohri App C–D + practice · 🎓📖 | Concentration in action (numpy) |

## M1 — ML basics (5–10)

| # | Source | Topic |
|---|---|---|
| 5 | SSBD ch1–2 · 🎓 | Gentle start + formal model (ERM/PAC) |
| 6 | SSBD ch8 + Mohri ch1 · 🎓 | Linear predictors, logistic, introduction |
| 7 | SSBD ch4 · 🎓 | Bias-variance (hand-drawn) |
| 8 | Arora ch2 + Ye ch2–3 · 🎓 | Min-norm interpolation, kernel regression, SVM |
| **9** | **E3 — SSBD ch21 · 🗣** | **Clustering fundamentals** |
| **10** | **E2 — SSBD ch17 · 🗣** | **Decision trees & ensemble practice** |

> 📖 E4 — SSBD ch24 (feature selection), reading with checklist after M1.

## M2 — Networks from scratch (11–17)

| # | Source | Topic |
|---|---|---|
| 11 | Ye ch5–6 + Arora ch3 · 🎓 | Networks, backprop, autodiff |
| 12 | SSBD ch18 · 🎓 | Network theory: representation, training |
| 13 | Cybenko 1989 + Telgarsky 2016 · 🗣 | Universal approximation, depth separation |
| 14 | **Zhang et al. 2017** · 🎓 | Live experiment: random labels (the mystery) |
| 15 | Ye ch7 (sel.) + Eldan–Shamir 2016 · 🎓🔬 | CNNs, depth |
| 16 | M2 seminar + review · 🗣 | — |
| **17** | **E8 — Ye ch8 · 🗣** | **Graph neural networks (architecture survey)** |

## M3 — Optimization (18–24)

| # | Source | Topic |
|---|---|---|
| 18 | Arora ch1 (pt 1) · 🎓 | GD, smoothness, rates |
| 19 | Arora ch1 (pt 2) + SSBD ch11 + Ye ch11 · 🎓 | Accelerated methods, convex learning, DL-optimization view |
| 20 | SSBD ch13 + Sra ch4 (sel.) · 🎓 | SGD, incremental/proximal |
| 21 | Sra ch5 (sel.) + SSBD ch20 + Mohri ch8 + reading slides ch2–3 · 🎓📖 | Nonsmooth first-order, online learning / OCO |
| 22 | SSBD ch12 + Arora ch11 (SDE-of-SGD) · 🎓🔬 | Stability/regularization; SGD noise |
| 23 | M3 seminar · 🗣 | — |
| **24** | **E12 — Sra ch13 (Bottou–Bousquet) · 🗣** | **Tradeoffs of large-scale learning** |

> 📖 E11 — Sra ch3, 7, 12, 15 (interior-point, cutting-plane, IPM-in-ML, improving first/second-order), reading with checklist after M3.

## M4 — Nonconvex landscapes (25–30)

| # | Source | Topic |
|---|---|---|
| 25 | Arora ch5 · 🎓 | Landscapes, saddles, SOSP |
| 26 | Arora ch6 · 🎓 | Perturbed GD, escaping saddles |
| 27 | Reading slides ch6 + Belkin §4 · 📖🗣 | PL\*, depth |
| 28 | Reading slides ch7 + Li et al. 2018 · 📖🎓 | Live: loss-landscape visualization |
| 29 | Keskar 2017 + Frankle–Carlin 2019 · 🗣 | Flat minima, lottery tickets |
| 30 | M4 seminar + review · 🗣 | — |

## M5 — Rigorous generalization (31–39)

| # | Source | Topic |
|---|---|---|
| 31 | Mohri ch2 + SSBD ch3 · 🎓 | PAC, uniform convergence |
| 32 | Mohri ch3 + SSBD ch5 · 🎓 | Rademacher, VC |
| **33** | **E13 — SSBD ch16 + ch28 + Mohri ch9 · ⚙️📖** | **Multiclass: lecture + advanced learnability reading** |
| 34 | SSBD ch10 + Mohri ch4 · 🎓 | Model selection, cross-validation |
| 35 | Arora ch4 + SSBD ch30 · 🎓 | Occam, compression, PAC-Bayes |
| 36 | Bartlett et al. 2019 + reading slides ch5 + Dziugaite–Roy 2017 · 🗣🔬 | Rademacher for nets, vacuous bounds |
| 37 | SSBD ch27 (FTLT proof) + M5 seminar · 🗣 | — |
| **38** | **E1 — SSBD ch9 + Mohri ch7 · 🗣** | **Boosting: AdaBoost, functional-gradient view, margin theory** |
| **39** | **E5 — Mohri ch10 · 🗣** | **Ranking: theory and algorithms** |

> 📖 E9 — SSBD ch7 (computational learnability), reading with checklist after M5.

## M6 — Interpolation mysteries (40–47)

| # | Source | Topic |
|---|---|---|
| 40 | Belkin §3.1–3.6 + SSBD ch19 · 🎓🗣 | Margins, 1-NN, simplicial interpolation |
| 41 | Belkin §3.7 + Belkin et al. 2019 · 🎓🗣 | Double descent |
| 42 | **Bartlett et al. PNAS 2020** · 🎓 | Min-norm, effective ranks (the payoff) |
| 43 | PNAS supplement (Thm S.14, §K) + Hastie et al. 2022 · 🔬🗣 | Spectral patterns, lower bounds |
| 44 | Arora ch7 · 🎓 | Algorithmic regularization |
| 45 | Soudry 2018 + Gunasekar 2017 + HaoChen 2021 · 🗣🔬 | Modern implicit bias |
| 46 | Belkin §3.9–3.11 + Ye ch12 + B–M §3 · 🎓📋 | Alignment, kernelization, generalization capability, outlook |
| 47 | Workshop: benign/harmful phase diagram + review · 🎓 | — |

## M7 — Kernels & NTK (48–55)

| # | Source | Topic |
|---|---|---|
| 48 | Mohri ch6 + SSBD ch15 + Vershynin ch3 (kernel trick) · 🎓 | Kernels, kernel ridge |
| 49 | Ye ch4 · 🎓 | RKHS, representer theorem |
| 50 | **Jacot et al. 2018** · 🎓 | NTK: limit, dynamics |
| 51 | **Arora et al. 2019** · 🎓 | Exact NTK, CNTK |
| 52 | Arora ch8 + reading slides ch9 · 🎓📖 | Ultra-wide nets, lazy training |
| 53 | Workshop · 🎓 | Empirical NTK on MNIST |
| 54 | Woodworth 2020 + Chizat–Bach 2020 · 🗣 | Lazy/rich — bridge to M8 |
| 55 | Mei et al. 2018 + Yang–Hu 2021 + B–M §5 · 🔬📋 | Depth, linear regime |

## M8 — Beyond kernels (56–63)

| # | Source | Topic |
|---|---|---|
| 56 | **Papyan–Han–Donoho 2020** + live experiment · 🎓 | NC1–NC4, terminal phase of training |
| 57 | **Lu–Steinerberger** + PNAS supplement · 🎓🔬 | ETF, variational analysis |
| 58 | Arora ch12 + Ye ch9 (normalization part) + reading slides ch13 · 🎓📖 | Normalization, scale invariance |
| 59 | Ioffe–Szegedy 2015 + Santurkar 2018 + Daneshmand 2020 · 📖🗣🔬 | Why batch norm works |
| 60 | Reading slides ch11 + Ye ch10 · 📖🎓 | Dropout, geometry of DNNs |
| 61 | Workshop · 🎓 | Lazy→feature sweep |
| 62 | Open discussion · 🎓 | Why does SGD reach the ETF? (open question) |
| 63 | M8 seminar + review · 🗣 | — |

## M9 — Generative models (64–75)

| # | Source | Topic |
|---|---|---|
| 64 | Arora ch13 + **ch15 (GANs)** + Ye ch13 · 🎓📖 | VAE, flows, GANs — the generative landscape |
| 65 | **Hyvärinen 2005** · 🎓 | Score matching |
| 66 | Sohl-Dickstein 2015 + Luo 2022 · 📖🎓 | Markov chains, ELBO/DDPM |
| 67 | **Song et al. 2021** · 🎓 | Score-based SDEs, probability flow |
| 68 | Chung et al. 2024 review + workshop · 📖🎓 | Survey + build 2D diffusion |
| 69 | **Chewi–Niles-Weed–Rigollet ch1** · 🎓 | Optimal transport, Wasserstein, Kantorovich |
| 70 | CNWR ch2 · 🎓 | Estimating Wasserstein, rates, chaining |
| 71 | Chen–Lee–Lu · 🗣 | Sampling guarantees |
| 72 | **Wibisono–Wu–Yang** · 🗣 | Minimax score-estimation rate |
| 73 | Workshop · 🎓 | Test the n^{−2/(d+4)} rate |
| 74 | Fan–Guan–Shen–Wu + Gatmiry–Kelner–Lee · 🔬 | Gradient flows, learning GMMs |
| 75 | M9 seminar + review · 🗣 | — |

## M10 — Transformers & scaling (76–83)

| # | Source | Topic |
|---|---|---|
| 76 | Ye ch9 + Arora ch14 + **Arora ch16 (self-supervised)** · 🎓 | Attention, transformers, self-supervised pretraining |
| 77 | Arora ch14 (scaling) + Kaplan et al. 2020 · 🎓 | Power laws (fitting exercise) |
| 78 | von Oswald 2022 + Garg 2022 · 🗣 | In-context learning ≈ GD |
| 79 | Olsson 2022 + workshop · 🗣🎓 | Induction heads, linear ICL |
| 80 | Hoffmann 2022 + Bahri 2021 · 🗣🔬 | Compute-optimal training, emergence (skepticism) |
| 81 | Final session + research roadmap · 🎓 | — |
| **82** | **E6 — Arora ch9 · 🗣** | **Credit attribution: influence functions, Shapley, saliency** |
| **83** | **E7 — Mohri ch17 · 🗣** | **Reinforcement learning crash course: MDP, planning, learning** |

## Track B — Advanced statistics seminar (parallel, B1–B6)

| # | Source | Topic |
|---|---|---|
| B1 | GMM-via-OT slides (teacher's model talk) · 🎓 | Moment-SOS, optimal transport |
| B2 | Ghosh et al. · 🗣 | Networks from Gaussian graphical models / free fields |
| B3 | Chaudhuri et al. · 🗣 | Empirical-likelihood ABC |
| B4 | Ghosh et al. · 🗣 | Bulk spectra of truncated covariance |
| B5 | CNWR ch3–4 · 🗣 | Transport-map estimation, rates |
| B6 | Students' final presentations · 🗣 | — |

> 📖 E10 — Mohri ch16 (learning automata and languages), reading inside Track B.

## Capstone (6–8 weeks, teams)

Reproduce one of the four [capstone projects](research-tracks.html) + a research extension; final 20-minute talk.

## Counting

- **83 numbered sessions** = 74 core lectures/seminars/workshops + **9 in-class extension sessions** (E1, E2, E3, E5, E6, E7, E8, E12, E13), all interleaved and numbered
- **4 reading assignments** (E4, E9, E10, E11) — 📖 homework with a 3-question checklist, no class slot
- Track B (6 seminars) runs in parallel · Capstone 6–8 weeks
- Every chapter of every book is covered (see [Book chapters I](book-chapters-1.html) & [II](book-chapters-2.html))