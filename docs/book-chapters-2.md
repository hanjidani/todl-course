# Book chapters (2/2) — Vershynin, Mohri, Sra–Nowozin, surveys, Statistical OT

> Status legend: ✅ full coverage · ⚙️ selected sections · 🗣 student seminar · 🔬 research corner · 📋 teacher reference · ⏭️ out of scope.
> Chapter numbers follow the actual editions used (Vershynin **2nd edition 2026**).

## Vershynin, *High-Dimensional Probability* (2nd ed., 341p — the toolbelt)

| # | Chapter | Status | Module |
|---|---|---|---|
| Appetizer | Covering a set with probability | ⚙️ | M0 |
| 1 | Quick Refresher on Analysis and Probability | 📖 | M0 |
| 2 | Concentration of Sums (Hoeffding, Chernoff, subgaussian, Bernstein) | ✅ | M0 |
| 3 | Random Vectors in High Dimensions (norm concentration, PCA, kernel trick) | ✅ | M0/M7 |
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
| 7 | Boosting | ⏭️ | — |
| 8 | On-Line Learning (expert advice, on-line-to-batch) | ⚙️ | M3 |
| 9–10 | Multi-Class / Ranking | ⏭️ | — |
| 11 | Regression | 🔬 | M6 |
| 12–13 | Maxent / Conditional Maxent (logistic regression) | ⚙️ | M1 |
| 14 | Algorithmic Stability | 🔬 | M5 |
| 15 | Dimensionality Reduction (PCA, KPCA, JL) | 🔬 | — |
| 16–17 | Automata / Reinforcement Learning | ⏭️ | — |
| App A–E | Linear algebra, Convex opt, Probability, Concentration, Info theory | 📖 (+🔬) | M0 |

## Sra, Nowozin & Wright, *Optimization for ML* (509p — teacher's optimization reference)

| # | Chapter | Status | Module |
|---|---|---|---|
| 1 | Introduction (SVM, regularized optimization) | 📋 | — |
| 2 | Convex Opt. with Sparsity-Inducing Norms (proximal, coordinate, reweighted) | 🔬 | M6 |
| 3 | Interior-Point Cone Programming (LP/QP/SOCP/SDP) | ⏭️ | — |
| 4 | Incremental Gradient, Subgradient & Proximal Methods | ✅ | M3 |
| 5 | First-Order Methods for Nonsmooth Convex Large-Scale | ⚙️ | M3 |
| 6 | Cutting-Plane Methods in ML | ⏭️ | — |
| 7 | Dual Decomposition for Inference | 🔬 | — |
| 8 | Augmented Lagrangian Methods | 🔬 | — |
| 9–11 | remaining chapters | ⏭️ | — |

## Surveys & OT monograph (teacher's story maps + M9 backbone)

**Belkin, "Fit without fear" (51p)** — narrative spine for M5–M7:
§3 generalization/margins (🎓/🗣, incl. 1-NN & simplicial interpolation) · §3.7 double descent (🎓) · §3.8 min-norm predictors (✅) · §3.9–3.10 alignment & linearization (🎓) · §4 PL\* condition (🗣, M4) · §5 square loss/adversarial (⚙️).

**Bartlett & Montanari, "Deep learning: a statistical viewpoint" (116p, Acta Numerica 2021)** — 📋 teacher depth for M5/M6/M7: uniform convergence, implicit regularization, benign overfitting, efficient optimization, generalization in the linear regime, kernels with n≪d.

**Chewi–Niles-Weed–Rigollet, "Statistical Optimal Transport" (288p, Saint-Flour)** — ch1 Optimal transport & Wasserstein (🎓 M9) · ch2 Estimation of Wasserstein distances — WLLN, dyadic partitioning, dual chaining, rates (🎓 M9) · ch3 Estimation of transport maps (🗣 Track B) · ch4+ (🔬).