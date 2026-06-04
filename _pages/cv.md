---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<style>
.cv { line-height: 1.5; }
.cv h2 {
  text-transform: uppercase;
  letter-spacing: 0.09em;
  font-size: 0.95em;
  font-weight: 700;
  color: #4a6b8a;
  border-bottom: 1px solid #e3e8ee;
  padding-bottom: 0.35em;
  margin-top: 2em;
  margin-bottom: 0.9em;
}
.cv h2:first-of-type { margin-top: 0.8em; }
.cv .entry {
  display: flex;
  justify-content: space-between;
  align-items: baseline;
  gap: 1.5em;
  margin-bottom: 0.35em;
}
.cv .entry .where { font-weight: 600; }
.cv .entry .when { white-space: nowrap; color: #8a93a0; font-size: 0.92em; }
.cv .role { font-style: italic; color: #5a6472; margin: 0 0 0.4em; }
.cv .desc { margin: 0.2em 0 1em; padding-left: 0; }
.cv .desc li { margin-bottom: 0.3em; }
.cv .lead { font-weight: 600; }
.cv .tags { margin: 0.2em 0 1.1em; }
.cv .tag {
  display: inline-block;
  background: #eef2f7;
  color: #38414d;
  border-radius: 999px;
  padding: 3px 12px;
  margin: 3px 4px 3px 0;
  font-size: 0.85em;
}
.cv .group-label { font-weight: 600; display: block; margin: 0.6em 0 0.3em; }
</style>

<div class="cv" markdown="0">

<h2>Education</h2>

<div class="entry"><span class="where">University of Houston</span><span class="when">Expected May 2027</span></div>
<p class="role">Ph.D. in Applied Mathematics &middot; Houston, TX</p>

<div class="entry"><span class="where">Lady Shri Ram College for Women, University of Delhi</span><span class="when">2020</span></div>
<p class="role">M.S. in Mathematics &middot; New Delhi, India</p>

<div class="entry"><span class="where">Janki Devi Memorial College, University of Delhi</span><span class="when">2018</span></div>
<p class="role">B.S. (Honors) in Mathematics &middot; New Delhi, India</p>

<h2>Research Experience</h2>

<div class="entry"><span class="where">Institute for Basic Science (IBS)</span><span class="when">Jun – Aug 2025</span></div>
<p class="role">Research Intern &middot; Daejeon, South Korea</p>
<ul class="desc">
  <li>Designed and implemented novel reinforcement-learning algorithms to adaptively tune HMC hyper-parameters (step size, target acceptance rate) for 5–100 dimensional Bayesian posterior sampling.</li>
  <li>Benchmarked the adaptive sampler against standard HMC and NUTS baselines in Python, demonstrating 100% convergence of posterior samples.</li>
  <li>Validated performance on the PosteriorDB benchmark across diverse Bayesian models and posterior geometries.</li>
</ul>

<div class="entry"><span class="where">University of Houston</span><span class="when">Fall 2023 – Present</span></div>
<p class="role">Graduate Research Assistant &middot; Houston, TX</p>
<ul class="desc">
  <li><span class="lead">Gene Regulatory Network inference —</span> Developed a Bayesian framework for small-scale GRNs (1–4 genes) using the Chemical Langevin Equation, inferring regulatory interactions, kinetic parameters, and feedback topology from stochastic steady-state gene expression.</li>
  <li><span class="lead">RL-driven adaptive Hamiltonian Monte Carlo —</span> Developing a curriculum-based reinforcement-learning framework to tune HMC sampling parameters; formalized hyper-parameter adaptation as a Markov Decision Process with rewards based on negative log posterior, entropy, and effective squared jump distance.</li>
  <li><span class="lead">Biocomputing —</span> Developing mathematical and stochastic models for an ongoing biocomputing project, supporting biologically grounded simulations and downstream computational analysis.</li>
</ul>

<h2>Skills</h2>

<span class="group-label">Mathematical &amp; Statistical Methods</span>
<div class="tags">
  <span class="tag">Bayesian Inference</span><span class="tag">Variational Inference</span><span class="tag">MCMC</span><span class="tag">Stochastic Processes</span><span class="tag">Reinforcement Learning</span><span class="tag">Stochastic Differential Equations</span><span class="tag">Probabilistic Graphical Models</span><span class="tag">Numerical Methods</span><span class="tag">Optimization</span><span class="tag">Gaussian Processes</span><span class="tag">Causal Inference</span>
</div>

<span class="group-label">Programming</span>
<div class="tags">
  <span class="tag">Python</span><span class="tag">MATLAB</span><span class="tag">R</span><span class="tag">Stan</span>
</div>

<span class="group-label">Libraries &amp; Frameworks</span>
<div class="tags">
  <span class="tag">PyMC</span><span class="tag">NumPy</span><span class="tag">SciPy</span><span class="tag">TensorFlow</span><span class="tag">PyTorch</span><span class="tag">scikit-learn</span><span class="tag">JAX</span><span class="tag">OpenAI Gym</span><span class="tag">Pandas</span><span class="tag">Matplotlib</span><span class="tag">Git</span>
</div>

<span class="group-label">Domain Knowledge</span>
<div class="tags">
  <span class="tag">Computational Biology</span><span class="tag">Systems Biology</span><span class="tag">Gene Regulatory Networks</span><span class="tag">Computational Neuroscience</span><span class="tag">Scientific Machine Learning</span>
</div>

<h2>Publications</h2>

<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

<h2>Teaching</h2>

<div class="entry"><span class="where">University of Houston</span><span class="when">Fall 2022 – Present</span></div>
<p class="role">Graduate Teaching Assistant &middot; Houston, TX</p>
<ul class="desc">
  <li>Courses: Calculus, Graph Theory, Statistics for Data Science, Numerical Methods.</li>
</ul>

<h2>Awards</h2>

<div class="entry"><span class="where">Graduate Tuition Fellowship, University of Houston</span><span class="when">2022 – Present</span></div>
<p class="role">Competitive merit-based funding for doctoral researchers</p>

<div class="entry"><span class="where">Academic Excellence Award, University of Delhi</span><span class="when">2018</span></div>

<h2>Service &amp; Leadership</h2>

<div class="entry"><span class="where">American Mathematical Society — UH Chapter</span><span class="when">2022 – Present</span></div>
<p class="role">Vice President (Fall 2025 – Present) &middot; Webmaster (2024 – 2025) &middot; Secretary (2022 – 2024)</p>

</div>
