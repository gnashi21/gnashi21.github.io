---
title: "Bayesian Inference of Gene Regulatory Networks at Stochastic Steady State"
collection: publications
category: manuscripts
permalink: /publication/2026-01-bayesian-Inference-of-Gene
excerpt: 'This paper presents a Bayesian framework for inferring Gene Regulatory Networks, grounded in the biochemical reality of gene expression dynamics rather than purely statistical assumptions.'
date: 2026-01-10
venue: 'Journal of the Royal Society Interface (in press)'
#slidesurl: 'https://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://www.biorxiv.org/content/10.64898/2026.01.10.698684v1'
#bibtexurl: 'https://academicpages.github.io/files/bibtex1.bib'
citation: 'Gupta, A., Yoon, R., & Josić, K. (2026). Bayesian Inference of Gene Regulatory Networks at Stochastic Steady State. Journal of the Royal Society Interface (in press). Preprint: bioRxiv, 2026-01.'
---
Gene Regulatory Networks (GRNs) form the regulatory backbone that coordinates gene expression. The architecture of GRNs shapes their function and constrains the biochemical pathways through which information flows. Inferring the structure of regulatory interactions is thus essential for understanding biological systems, and designing targeted therapies. Despite substantial progress in GRN inference, most approaches – from statistical methods to deep learning – do not take into account fundamental biochemical processes that drive regulatory dynamics.
To address this shortcoming, here we present a novel Bayesian inference approach based on using the Chemical Langevin Equation (CLE) as a model of gene expression dynamics at stochastic equilibrium. Interactions in GRNs are sparse, and we thus use a regularized horseshoe prior enabling selective shrinkage of unsupported interactions while identifying strong regulatory edges. We evaluate our method using synthetic gene expression data, allowing for benchmarking against a known ground truth. Our approach allows us to infer kinetic parameters, identify network structure, and infer regulatory cycles without the need to observe transient dynamics. This Bayesian alternative to current methods thus provides both biological interpretability and structural identifiability in GRN inference.
