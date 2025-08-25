# Financial Mathematics University Course

This repository contains a collection of Jupyter notebooks and code from my university course in Financial Mathematics. The projects focus on the computational and stochastic aspects of quantitative finance, implementing key models and numerical methods from scratch.

## Core Concepts Explored

*   **Random Number Generation:** Foundations of simulation using various pseudo-random number generators.
*   **Stochastic Process Generation:** Simulating paths for fundamental processes like Geometric Brownian Motion (GBM).
*   **CRR Model (Cox-Ross-Rubinstein):** A binomial options pricing model for discrete-time option valuation.
*   **Variance Reduction Techniques:** Implementing methods like Antithetic Variates and Control Variates to improve the efficiency of Monte Carlo simulations.
*   **Option Pricing:** Numerical valuation of European and American options using different models.
*   **Monte Carlo Simulation:** Using random sampling to price derivative securities and estimate financial quantities.
*   **Black-Scholes Model:** Analytical solution for European option pricing and analysis of the Greeks.

## Repository Structure

| Folder | Description |
| :--- | :--- |
| [`/random_number_generation`](./random_number_generation) | Contains notebooks on implementing and testing various pseudo-random number generators (e.g., Linear Congruential Generator). |
| [`/stochastic_processes`](./stochastic_processes) | Code for generating and visualizing paths of stochastic processes like Brownian Motion and Geometric Brownian Motion. |
| [`/binomial_models`](./binomial_models) | Implementations of the Cox-Ross-Rubinstein (CRR) binomial tree model for option pricing. |
| [`/monte_carlo`](./monte_carlo) | Core Monte Carlo simulations for financial pricing, including basic estimators. |
| [`/variance_reduction`](./variance_reduction) | Notebooks demonstrating variance reduction techniques (Antithetic, Control Variates) applied to Monte Carlo option pricing. |
| [`/black_scholes`](./black_scholes) | Analytical Black-Scholes option pricing formula, calculation of Greeks, and comparative analyses. |
| [`/exotic_options`](./exotic_options) | Code for pricing path-dependent options (like Asian or Barrier options) using Monte Carlo and other methods. |
| [`/term_project`](./term_project) | Final course project applying the learned concepts to a more complex financial problem. |
| [`/data`](./data) | Folder for storing any sample market data or pre-generated results used in the notebooks. |
| [`/utilities`](./utilities) | Helper modules and functions (e.g., for pricing payoffs, calculating statistics) used across other notebooks.

## Technologies Used

*   **Python** (NumPy, SciPy, Matplotlib, Pandas)
*   **Jupyter Notebook**

---

*This repository is for educational purposes, documenting my learning journey in financial mathematics.*
