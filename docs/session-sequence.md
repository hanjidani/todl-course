---
layout: default
title: Session sequence
nav_order: 3
---

# Session sequence — 74 core sessions + extensions

> Each row = one session. Roles: 🎓 in-class · 🗣 student seminar · 📖 homework · 🔬 research corner · 📋 teacher reference. Papers are interleaved between book chapters at the point where they belong.

## M0 — Math (1–4)

| # | Source | Topic |
|---|---|---|
| 1 | Vershynin 2e ch2 · 🎓 | Hoeffding, Chernoff, subgaussian/subexponential, Bernstein |
| 2 | Vershynin 2e ch3 · 🎓 | Norm concentration, random vectors, PCA |
| 3 | Ye ch1 (sel.) + Arora Basic Setup · 🎓 | Matrix/vector calculus, convex optimization, useful facts |
| 4 | Mohri App C–D + practice · 🎓📖 | Concentration in action (numpy) |

## M1 — ML basics (5–8)

| # | Source | Topic |
|---|---|---|
| 5 | SSBD ch1–2 · 🎓 | Gentle start + formal model (ERM/PAC) |
| 6 | SSBD ch8 + Mohri ch1 · 🎓 | Linear predictors, logistic, introduction |
| 7 | SSBD ch4 · 🎓 | Bias-variance (hand-drawn) |
| 8 | Arora ch2 + Ye ch2–3 · 🎓 | Min-norm interpolation, kernel regression, SVM |

## M2 — Networks from scratch (9–14)

| # | Source | Topic |
|---|---|---|
| 9 | Ye ch5–6 + Arora ch3 · 🎓 | Networks, backprop, autodiff |
| 10 | SSBD ch18 · 🎓 | Network theory: representation, training |
| 11 | Cybenko 1989 + Telgarsky 2016 · 🗣 | Universal approximation, depth separation |
| 12 | **Zhang et al. 2017** · 🎓 | Live experiment: random labels |
| 13 | Ye ch7 (sel.) + Eldan–Shamir 2016 · 🎓🔬 | CNNs, depth |
| 14 | M2 seminar + review · 🗣 | — |

## M3 — Optimization (15–20)

| # | Source | Topic |
|---|---|---|
| 15 | Arora ch1 (pt 1) · 🎓 | GD, smoothness, rates |
| 16 | Arora ch1 (pt 2) + SSBD ch11 + Ye ch11 · 🎓 | Accelerated methods, convex learning, DL-optimization view |
| 17 | SSBD ch13 + Sra ch4 (sel.) · 🎓 | SGD, incremental/proximal |
| 18 | Sra ch5 (sel.) + SSBD ch20 + Mohri ch8 + reading slides ch2–3 · 🎓📖 | Nonsmooth first-order, online learning / OCO |
| 19 | SSBD ch12 + Arora ch11 (SDE-of-SGD) · 🎓🔬 | Stability/regularization; SGD noise |
| 20 | M3 seminar · 🗣 | — |

## M4 — Nonconvex landscapes (21–26)

| # | Source | Topic |
|---|---|---|
| 21 | Arora ch5 · 🎓 | Landscapes, saddles, SOSP |
| 22 | Arora ch6 · 🎓 | Perturbed GD, escaping saddles |
| 23 | Reading-group slides ch6 + Belkin §4 · 📖🗣 | PL\*, depth |
| 24 | Reading-group slides ch7 + Li et al. 2018 · 📖🎓 | Live: loss-landscape visualization |
| 25 | Keskar 2017 + Frankle–Carlin 2019 · 🗣 | Flat minima, lottery tickets |
| 26 | M4 seminar + review · 🗣 | — |

## M5 — Rigorous generalization (27–32)

| # | Source | Topic |
|---|---|---|
| 27 | Mohri ch2 + SSBD ch3 · 🎓 | PAC, uniform convergence |
| 28 | Mohri ch3 + SSBD ch5 · 🎓 | Rademacher, VC |
| 29 | SSBD ch10 + Mohri ch4 · 🎓 | Model selection, cross-validation |
| 30 | Arora ch4 + SSBD ch30 · 🎓 | Occam, compression, PAC-Bayes |
| 31 | Bartlett et al. 2019 + reading slides ch5 + Dziugaite–Roy 2017 · 🗣🔬 | Rademacher for nets, vacuous bounds |
| 32 | SSBD ch27 (FTLT proof) + M5 seminar · 🗣 | — |

## M6 — Interpolation mysteries (33–40)

| # | Source | Topic |
|---|---|---|
| 33 | Belkin §3.1–3.6 + SSBD ch19 · 🎓🗣 | Margins, 1-NN, simplicial interpolation |
| 34 | Belkin §3.7 + Belkin et al. 2019 · 🎓🗣 | Double descent |
| 35 | **Bartlett et al. PNAS 2020** · 🎓 | Min-norm, effective ranks |
| 36 | PNAS supplement (Thm S.14, §K) + Hastie et al. 2022 · 🔬🗣 | Spectral patterns, lower bounds |
| 37 | Arora ch7 · 🎓 | Algorithmic regularization |
| 38 | Soudry 2018 + Gunasekar 2017 + HaoChen 2021 · 🗣🔬 | Modern implicit bias |
| 39 | Belkin §3.9–3.11 + Ye ch12 + B–M §3 · 🎓📋 | Alignment, kernelization, generalization capability, outlook |
| 40 | Workshop: benign/harmful phase diagram + review · 🎓 | — |

## M7 — Kernels & NTK (41–48)

| # | Source | Topic |
|---|---|---|
| 41 | Mohri ch6 + SSBD ch15 + Vershynin ch3 (kernel trick) · 🎓 | Kernels, kernel ridge |
| 42 | Ye ch4 · 🎓 | RKHS, representer theorem |
| 43 | **Jacot et al. 2018** · 🎓 | NTK: limit, dynamics |
| 44 | **Arora et al. 2019** · 🎓 | Exact NTK, CNTK |
| 45 | Arora ch8 + reading slides ch9 · 🎓📖 | Ultra-wide nets, lazy training |
| 46 | Workshop · 🎓 | Empirical NTK on MNIST |
| 47 | Woodworth 2020 + Chizat–Bach 2020 · 🗣 | Lazy/rich — bridge to M8 |
| 48 | Mei et al. 2018 + Yang–Hu 2021 + Bartlett–Montanari §5 · 🔬📋 | Depth, linear regime |

## M8 — Beyond kernels (49–56)

| # | Source | Topic |
|---|---|---|
| 49 | **Papyan–Han–Donoho 2020** + live experiment · 🎓 | NC1–NC4, terminal phase of training |
| 50 | **Lu–Steinerberger** + PNAS supplement · 🎓🔬 | ETF, variational analysis |
| 51 | Arora ch12 + Ye ch9 (normalization part) + reading slides ch13 · 🎓📖 | Normalization, scale invariance |
| 52 | Ioffe–Szegedy 2015 + Santurkar 2018 + Daneshmand 2020 · 📖🗣🔬 | Why batch norm works |
| 53 | Reading slides ch11 + Ye ch10 · 📖🎓 | Dropout, geometry of DNNs |
| 54 | Workshop · 🎓 | Lazy→feature sweep |
| 55 | Open discussion · 🎓 | Why does SGD reach the ETF? (open question) |
| 56 | M8 seminar + review · 🗣 | — |

## M9 — Generative models (57–68)

| # | Source | Topic |
|---|---|---|
| 57 | Arora ch13 + **ch15 (GANs)** + Ye ch13 · 🎓📖 | VAE, flows, GANs — the generative landscape |
| 58 | **Hyvärinen 2005** · 🎓 | Score matching |
| 59 | Sohl-Dickstein 2015 + Luo 2022 · 📖🎓 | Markov chains, ELBO/DDPM |
| 60 | **Song et al. 2021** · 🎓 | Score-based SDEs, probability flow |
| 61 | Chung et al. 2024 review + workshop · 📖🎓 | Survey + build 2D diffusion |
| 62 | **Chewi–Niles-Weed–Rigollet ch1** · 🎓 | Optimal transport, Wasserstein, Kantorovich |
| 63 | CNWR ch2 · 🎓 | Estimating Wasserstein, rates, chaining |
| 64 | Chen–Lee–Lu · 🗣 | Sampling guarantees |
| 65 | **Wibisono–Wu–Yang** · 🗣 | Minimax score-estimation rate |
| 66 | Workshop · 🎓 | Test the n^{−2/(d+4)} rate |
| 67 | Fan–Guan–Shen–Wu + Gatmiry–Kelner–Lee · 🔬 | Gradient flows, learning GMMs |
| 68 | M9 seminar + review · 🗣 | — |

## M10 — Transformers & scaling (69–74)

| # | Source | Topic |
|---|---|---|
| 69 | Ye ch9 + Arora ch14 + **Arora ch16 (self-supervised)** · 🎓 | Attention, transformers, self-supervised pretraining |
| 70 | Arora ch14 (scaling) + Kaplan et al. 2020 · 🎓 | Power laws (fitting exercise) |
| 71 | von Oswald 2022 + Garg 2022 · 🗣 | In-context learning ≈ GD |
| 72 | Olsson 2022 + workshop · 🗣🎓 | Induction heads, linear ICL |
| 73 | Hoffmann 2022 + Bahri 2021 · 🗣🔬 | Compute-optimal training, emergence (skepticism) |
| 74 | Final session + research roadmap · 🎓 | — |

## Track B — Advanced statistics seminar (parallel, B1–B6)

| # | Source | Topic |
|---|---|---|
| B1 | GMM-via-OT slides (teacher's model talk) · 🎓 | Moment-SOS, optimal transport |
| B2 | Ghosh et al. · 🗣 | Networks from Gaussian graphical models / free fields |
| B3 | Chaudhuri et al. · 🗣 | Empirical-likelihood ABC |
| B4 | Ghosh et al. · 🗣 | Bulk spectra of truncated covariance |
| B5 | CNWR ch3–4 · 🗣 | Transport-map estimation, rates |
| B6 | Students' final presentations · 🗣 | — |

## Capstone (6–8 weeks, teams)

Reproduce one of the four [capstone projects](research-tracks.html) + a research extension; final 20-minute talk.

## Extension sessions (E1–E13) — full-book coverage

The extension sessions guarantee **every chapter of every book** is covered — nothing is out of scope. They slot into the core sequence at the marked positions.

| # | Source | Topic | Role | Slot |
|---|---|---|---|---|
| E1 | SSBD ch9 + Mohri ch7 | Boosting: AdaBoost, functional-gradient view, margin theory | 🗣 | after M5 (32) |
| E2 | SSBD ch17 | Decision trees & ensemble practice | 🗣 | after M1 (8) |
| E3 | SSBD ch21 | Clustering fundamentals | 🗣 | after M1 (8) |
| E4 | SSBD ch24 | Feature selection | 📖 | after M1 (8) |
| E5 | Mohri ch10 | Ranking: theory and algorithms | 🗣 | after M5 (32) |
| E6 | Arora ch9 | Credit attribution: influence functions, Shapley, saliency | 🗣 | after M10 (74) |
| E7 | Mohri ch17 | Reinforcement learning crash course: MDP, planning, learning | 🗣 | after M10 / Track B |
| E8 | Ye ch8 | Graph neural networks | 🗣 | after M2 (14) |
| E9 | SSBD ch7 | Computational learnability (runtime of learning) | 📖 | after M5 (32) |
| E10 | Mohri ch16 | Learning automata and languages | 📖 | Track B |
| E11 | Sra ch3, 7, 12, 15 | Interior-point, cutting-plane, IPM-in-ML, improving first/second-order | 📖 | after M3 (20) |
| E12 | Sra ch13 | Tradeoffs of large-scale learning (Bottou–Bousquet) | 🗣 | after M3 (20) |
| E13 | SSBD ch16 + ch28 + Mohri ch9 | Multiclass: in-class lecture + advanced learnability reading | ⚙️📖 | inside M5 (after 28) |