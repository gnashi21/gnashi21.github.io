---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D. in Applied Mathematics, University of Houston, expected May 2027
* M.S. in Mathematics, Lady Shri Ram College for Women, University of Delhi, 2020
* B.S. (Honors) in Mathematics, Janki Devi Memorial College, University of Delhi, 2018

Research experience
======
* Summer 2025: Research Intern
  * Institute for Basic Science (IBS), Daejeon, South Korea
  * Designed and implemented novel reinforcement-learning algorithms to adaptively tune HMC hyper-parameters (step size, target acceptance rate) for 5–100 dimensional Bayesian posterior sampling.
  * Benchmarked the adaptive sampler against standard HMC and NUTS baselines in Python, demonstrating 100% convergence of posterior samples.
  * Validated performance on the PosteriorDB benchmark across diverse Bayesian models and posterior geometries.

* Fall 2023 – Present: Graduate Research Assistant
  * University of Houston, Houston, TX
  * **Gene Regulatory Network inference:** Developed a Bayesian framework for small-scale GRNs (1–4 genes) using the Chemical Langevin Equation, inferring regulatory interactions, kinetic parameters, and feedback topology from stochastic steady-state gene expression.
  * **RL-driven adaptive Hamiltonian Monte Carlo:** Developing a curriculum-based reinforcement-learning framework to tune HMC sampling parameters, improving convergence and efficiency in high-dimensional Bayesian inference; formalized hyper-parameter adaptation as a Markov Decision Process with rewards based on negative log posterior, entropy, and effective squared jump distance.
  * **Biocomputing:** Developing mathematical and stochastic models for an ongoing biocomputing project, supporting biologically grounded simulations and downstream computational analysis.

Skills
======
* **Mathematical & statistical methods:** Bayesian inference, variational inference, MCMC, stochastic processes, reinforcement learning, stochastic differential equations, probabilistic graphical models, numerical methods, optimization, Gaussian processes, causal inference
* **Programming:** Python (advanced), MATLAB, R, Stan
* **Libraries & frameworks:** PyMC, NumPy, SciPy, TensorFlow, PyTorch, scikit-learn, OpenAI Gym, Pandas, JAX, Matplotlib, Git
* **Domain knowledge:** Computational biology, systems biology, gene regulatory networks, computational neuroscience, scientific machine learning

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Teaching
======
* Fall 2022 – Present: Graduate Teaching Assistant, University of Houston
  * Courses: Calculus, Graph Theory, Statistics for Data Science, Numerical Methods

Awards
======
* Graduate Tuition Fellowship, University of Houston (2022–Present) — competitive merit-based funding for doctoral researchers
* Academic Excellence Award, University of Delhi (2018)

Service and leadership
======
* American Mathematical Society, UH Chapter — Vice President (Fall 2025–Present), Webmaster (2024–2025), Secretary (2022–2024)
