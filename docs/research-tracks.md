# Research tracks & capstone

The course is designed so that everything students meet in class is directly usable in research. After the course (or in parallel for strong students), teams pick a track.

## Track A — Generalization & interpolation

- **Reading path:** Bartlett et al. 2020 (PNAS) → Soudry et al. 2018 → Woodworth et al. 2020 → Belkin survey → Dziugaite & Roy 2017.
- **Reproduce:** the benign/harmful phase diagram in linear regression.
- **Open problem:** *What are benign-overfitting conditions for nonlinear networks?*

## Track B — Generative models & optimal transport

- **Reading path:** Hyvärinen 2005 → Song et al. 2021 → Wibisono–Wu–Yang → Chewi–Niles-Weed–Rigollet (ch. 2–3) → Chen–Lee–Lu.
- **Reproduce:** the minimax score-estimation rate test (n^{−2/(d+4)}).
- **Open problem:** *Score-estimation rates for data supported on manifolds?* (curse of dimensionality revisited)

## Track C — Training dynamics & feature learning

- **Reading path:** Jacot et al. 2018 → Chizat & Bach 2020 → Woodworth et al. 2020 → Lu–Steinerberger → SDE approximation of SGD (Arora book ch. 11).
- **Reproduce:** the lazy→feature width sweep on MNIST.
- **Open problem:** *Why does SGD converge to the simplex ETF?* (dynamical proof still missing — also relevant to model-change/risk-attribution theory.)

## Capstone projects (6–8 weeks, teams of 2–3)

1. **Neural-collapse simplex in a toy net** — verify NC1–NC4 numerically (within-class variance → 0, ETF geometry); CPU-feasible.
2. **Lazy vs feature regime sweep** — vary width/init scale on MNIST; measure weight displacement ‖W_t−W₀‖, kernel alignment, test accuracy; map the Chizat–Bach/Woodworth transition.
3. **Benign-overfitting phase diagram** — synthetic linear regression with eigen-decaying covariance; sweep SNR, ridge, eigenstructure; reproduce the BLLT benign/harmful boundary.
4. **Score-error scaling in a tiny diffusion model** — train a score net on 2D/3D data; estimate score error vs n and d; check the n^{−2/(d+4)} optimal rate (Wibisono–Wu–Yang); bonus: sampling error vs step size (Chen–Lee–Lu).

**Capstone rule:** each team reproduces one theoretical claim **and** adds one "research extension" — a question the literature does not answer — presented in a 20-minute talk.