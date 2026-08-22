<div align="center">

# Reinforcement Learning

### From Markov Chains to Q-Learning

Practical, numerical Jupyter notebooks for building reinforcement-learning
intuition one concept at a time.

[![Jupyter](https://img.shields.io/badge/Jupyter-Explore_the_curriculum-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](#learning-path)
[![License](https://img.shields.io/badge/License-MIT-2563EB?style=for-the-badge)](LICENSE)

</div>

---

## What is this repository?

This repository is a small, progressive reinforcement-learning curriculum. The
notebooks favor transparent calculations, tiny environments, and worked examples
so you can see how each update rule changes an agent's estimates and behavior.

## Learning path

| Stage | Topic | Core idea |
|---:|---|---|
| 1 | [`markov_chains`](01_markov_chains/) | Model states and transition dynamics |
| 2 | [`value_functions`](02_value_functions/) | Estimate expected returns and solve small MDPs |
| 3 | [`policy_iteration`](03_policy_iteration/) | Alternate policy evaluation and improvement |
| 4 | [`monte_carlo_control`](04_monte_carlo_control/) | Learn action values from sampled episodes |
| 5 | [`q_learning`](05_q_learning/) | Learn off-policy TD control from bootstrapped targets |

Start at Stage 1 if reinforcement learning is new to you, or jump directly to the
folder matching the concept you want to practice.

## What you will practice

- Markov chains, rewards, returns, and value functions.
- Value iteration and policy iteration in small environments.
- Monte Carlo prediction and control.
- Temporal-difference reasoning and Q-learning updates.
- Translating equations into compact NumPy implementations.

## Quick start

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install jupyter numpy
jupyter lab
```

Open a topic folder and run its notebooks in order. For Q-learning, begin with
[`01_q_learning_exercises.ipynb`](05_q_learning/01_q_learning_exercises.ipynb),
then compare your work with
[`02_q_learning_full_solution.ipynb`](05_q_learning/02_q_learning_full_solution.ipynb).

## Conventions

Repository paths use lowercase snake_case for predictable terminal and
cross-platform behavior. Notebook headings preserve the conventional names of
the algorithms and environments they explain.
