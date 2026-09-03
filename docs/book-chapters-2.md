---
layout: default
title: Book chapters II
nav_order: 5
---

# Book chapters (2/2) — Vershynin, Mohri, Sra–Nowozin, surveys, Statistical OT

> **Program:** 104 sessions · 13 modules · 11+ books × 75+ papers — [full sequence](session-sequence.html)

> Status legend: ✅ full coverage · ⚙️ selected sections in class · 🗣 student seminar · 📖 assigned reading · 🔬 research corner · 📋 teacher material.
> **No out-of-scope topics:** every chapter has an assignment — main modules, extension sessions E1–E13 (see [session sequence](session-sequence.html)), or the research corner.
> Chapter numbers follow the actual editions used (Vershynin **2nd edition 2026**).

## Vershynin, *High-Dimensional Probability* (2nd ed., 341p — the toolbelt)

| # | Chapter | Status | Module |
|---|---|---|---|
| Appetizer | Covering a set with probability | ⚙️ | M0 |
| 1 | Quick Refresher on Analysis and Probability | ✅ | M0 (S00) |
| 2 | Concentration of Sums (Hoeffding, Chernoff, subgaussian, Bernstein) | ✅ | M0 (S01) |
| 3 | Random Vectors in High Dimensions (norm concentration, PCA, kernel trick) | ✅ | M0 (S02) + M7 (session 48, kernel trick) |
| 4 | Random Matrices (nets, subgaussian matrices, covariance estimation) | ⚙️ | M6 |
| 5 | Concentration Without Independence (Lipschitz, JL, matrix Bernstein) | 🔬 | — |
| 6 | Quadratic Forms (Hanson–Wright, symmetrization) | 🔬 | M6 |
| 7 | Random Processes (Slepian, Sudakov–Fernique, Gaussian width) | 🔬 | M9 |
| 8 | Chaining (Dudley, empirical processes, VC, generic chaining) | ⚙️ | M5 + 🔬 M9 |
| 9 | Deviations of Random Matrices on Sets (M\*, sparse recovery) | 🔬 | — |

## Mohri et al., *Foundations of Machine Learning* (2nd ed., 505p — the rigor layer)

| # | Chapter | Status | Module |
|---|---|---|---|
| 1 | Introduction | ✅ | M1 |
| 2 | The PAC Learning Framework | ✅ | M5 |
| 3 | Rademacher Complexity and VC-Dimension | ✅ | M5 |
| 4 | Model Selection (ERM/SRM, CV, regularization) | ✅ | M5 |
| 5 | Support Vector Machines | ⚙️ | M1 |
| 6 | Kernel Methods (PDS, representer, sequence kernels) | ✅ | M7 |
| 7 | Boosting | 📖 | E1 (with SSBD ch9 seminar) |
| 8 | On-Line Learning (expert advice, on-line-to-batch) | ⚙️ | M3 (session 21) |
| 9 | Multi-Class Classification | 📖 | E13 (session 33) |
| 10 | Ranking | 🗣 | E5 (session 39) |
| 11 | Regression | 🔬 | M6 |
| 12–13 | Maxent / Conditional Maxent (logistic regression) | ⚙️ | M1 |
| 14 | Algorithmic Stability | 🔬 | M5 |
| 15 | Dimensionality Reduction (PCA, KPCA, JL) | 🔬 | — |
| 16 | Learning Automata and Languages | 📖 | optional self-study |
| 17 | Reinforcement Learning | 🗣 | E7 (session 83) |
| App A–E | Linear algebra, Convex opt, Probability, Concentration, Info theory | 📖 (+🔬) | M0 |

## Sra, Nowozin & Wright, *Optimization for ML* (509p — full 18-chapter coverage)

| # | Chapter | Status | Module |
|---|---|---|---|
| 1 | Introduction (SVM, regularized optimization) | 📋 | teacher prep (M3) |
| 2 | Convex Opt. with Sparsity-Inducing Norms (proximal, coordinate, reweighted) | 🔬 | M6 |
| 3 | Interior-Point Cone Programming (LP/QP/SOCP/SDP) | 📖 | E11 (reading, after M3) |
| 4 | Incremental Gradient, Subgradient & Proximal Methods (Bertsekas) | ✅ | M3 |
| 5 | First-Order Methods for Nonsmooth Large-Scale, I: General Purpose (Juditsky–Nemirovski) | ⚙️ | M3 |
| 6 | First-Order Methods for Nonsmooth Large-Scale, II: Utilizing Structure (Juditsky–Nemirovski) | ⚙️ | M3 |
| 7 | Cutting-Plane Methods in ML (Franc, Sonnenburg, Werner) | 📖 | E11 (reading, after M3) |
| 8 | Introduction to Dual Decomposition for Inference (Sontag, Globerson, Jaakkola) | 🔬 | — |
| 9 | Augmented Lagrangian Methods for Learning/Selecting/Combining Features (Tomioka et al.) | 🔬 | — |
| 10 | The Convex Optimization Approach to Regret Minimization | 📖 | M3 (OCO depth) |
| 11 | Projected Newton-type Methods in Machine Learning | 🔬 | — |
| 12 | Interior-Point Methods in Machine Learning | 📖 | E11 (reading, after M3) |
| 13 | The Tradeoffs of Large-Scale Learning (Bottou–Bousquet) | 🗣 | E12 (session 24) |
| 14 | Robust Optimization in Machine Learning | 🔬 | — |
| 15 | Improving First- and Second-Order Methods | 📖 | E11 (reading, after M3) |
| 16 | A Bandit View on Noisy Optimization | 🔬 | — |
| 17 | Optimization Methods for Sparse Inverse Covariance Selection | 🔬 | — |
| 18 | A Pathwise Algorithm for Covariance Selection | 🔬 | — |

## Surveys & OT monograph (teacher's story maps + M9 backbone)

**Belkin, "Fit without fear" (51p)** — narrative spine for M5–M7:
§3 generalization/margins (🎓/🗣, incl. 1-NN & simplicial interpolation) · §3.7 double descent (🎓) · §3.8 min-norm predictors (✅) · §3.9–3.10 alignment & linearization (🎓) · §4 PL\* condition (🗣, M4) · §5 square loss/adversarial (⚙️).

**Bartlett & Montanari, "Deep learning: a statistical viewpoint" (116p, Acta Numerica 2021)** — 📋 teacher depth for M5/M6/M7: uniform convergence, implicit regularization, benign overfitting, efficient optimization, generalization in the linear regime, kernels with n≪d.

**Chewi–Niles-Weed–Rigollet, "Statistical Optimal Transport" (288p, Saint-Flour)** — ch1 Optimal transport & Wasserstein (🎓 M9) · ch2 Estimation of Wasserstein distances — WLLN, dyadic partitioning, dual chaining, rates (🎓 M9) · ch3 Estimation of transport maps (🔬 research corner) · ch4+ (🔬).