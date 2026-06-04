---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
.rss-board {
  float: right;
  width: 300px;
  max-width: 42%;
  margin: 0.3em 0 1.2em 1.8em;
  border: 1px solid #d6dbe1;
  border-radius: 6px;
  overflow: hidden;
  font-family: "SFMono-Regular", Consolas, "Liberation Mono", Menlo, monospace;
  box-shadow: 0 1px 3px rgba(0,0,0,0.06);
}
.rss-board__bar {
  background: linear-gradient(#fb923c, #ee802f);
  color: #fff;
  padding: 8px 14px;
  font-weight: 700;
  letter-spacing: 0.04em;
  font-size: 0.9em;
  display: flex;
  align-items: center;
  gap: 8px;
}
.rss-board__bar .dot {
  width: 9px; height: 9px; border-radius: 50%;
  background: #fff; box-shadow: 0 0 0 3px rgba(255,255,255,0.35);
}
.rss-board__feed {
  max-height: 320px;
  overflow-y: auto;
  margin: 0;
  padding: 0;
  list-style: none;
  background: #fbfcfd;
}
.rss-board__feed li {
  padding: 10px 14px;
  border-bottom: 1px solid #eef1f4;
  font-size: 0.82em;
  line-height: 1.45;
}
.rss-board__feed li:last-child { border-bottom: none; }
.rss-board__feed .date {
  display: block;
  color: #2f62ee;
  font-weight: 700;
  margin-bottom: 2px;
}
.rss-board__feed .item { color: #3a424c; }
.rss-board__feed .item a { font-family: inherit; }

/* On phones: drop the float and move the board BELOW the about text */
@media (max-width: 768px) {
  .about-wrap { display: flex; flex-direction: column; }
  .about-wrap .about-text { order: 1; }
  .about-wrap .rss-board {
    order: 2;
    float: none;
    width: auto;
    max-width: none;
    margin: 2em 0 0;
  }
}
</style>

<div class="about-wrap" markdown="0">

<div class="rss-board">
  <div class="rss-board__bar"><span class="dot"></span> What I am doing</div>
  <!-- To add an update: copy a <li> line, change the date and text. Newest goes on top. -->
  <ul class="rss-board__feed">
    <li><span class="date">2026-06</span><span class="item">Attending Workshops <strong>Vice President</strong> of the AMS UH Student Chapter.</span></li>
    <li><span class="date">2026-01</span><span class="item">Our paper <em>“Bayesian Inference of Gene Regulatory Networks at Stochastic Steady State”</em> was accepted (in press) at the <strong>Journal of the Royal Society Interface</strong>.</span></li>
    <li><span class="date">2025-09</span><span class="item">Began my term as <strong>Vice President</strong> of the AMS UH Student Chapter.</span></li>
  </ul>
</div>

<div class="about-text" markdown="1">

I am a Ph.D. candidate in Applied Mathematics at the University of Houston, driven by a curiosity about how complex systems organize, adapt, and regulate themselves. My work lies at the intersection of probability, computation, and biology, where I develop mathematically grounded models for stochastic systems and data-driven inference. I am particularly interested in Bayesian methods, reinforcement learning for scientific computing, and the emerging area of biocomputing — exploring how biological systems can inform new computational paradigms.

My research spans two main directions.

- In one line of work, I develop Bayesian frameworks for inferring gene regulatory networks, recovering how genes interact and regulate one another using stochastic models of gene expression.
- In another, I investigate how reinforcement learning can be used to adapt and improve Hamiltonian Monte Carlo, enhancing the efficiency and stability of high-dimensional Bayesian inference.

Together, these projects reflect my broader goal of building interpretable, scalable algorithms for scientific discovery.

Outside of research, I enjoy dancing, cooking, reading fiction, traveling, and occasionally unwinding with a good Netflix series. I value both analytical rigor and creative expression — whether I’m building mathematical models, experimenting in the kitchen, or getting lost in a compelling story.

</div>

</div>
