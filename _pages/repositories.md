---
layout: page
permalink: /software/
title: Software
description: Research code accompanying my papers.
nav: true
nav_order: 3
_styles: >
  .software-grid { display: grid; grid-template-columns: repeat(2, minmax(0, 1fr)); gap: 1rem; margin-top: 1.4rem; }
  .software-card { border: 1px solid var(--global-divider-color); border-radius: 0.35rem; padding: 1.1rem 1.2rem;
  background: var(--global-card-bg-color); }
  .software-card h3 { font-size: 1.08rem; font-weight: 600; line-height: 1.35; margin: 0 0 0.65rem; }
  .software-card p { font-size: 0.96rem; margin-bottom: 0.85rem; }
  .software-tags { display: flex; flex-wrap: wrap; gap: 0.4rem; margin-bottom: 0.85rem; }
  .software-tags span { border: 1px solid var(--global-divider-color); border-radius: 999px; color: var(--global-text-color-light);
  font-size: 0.75rem; padding: 0.12rem 0.52rem; }
  .software-links { display: flex; gap: 1rem; font-weight: 600; }
  @media (max-width: 767.98px) {
  .software-grid { grid-template-columns: 1fr; gap: 0.85rem; }
  .software-card { padding: 1rem; }
  .software-card h3 { font-size: 1rem; }
  .software-card p { font-size: 0.92rem; line-height: 1.55; }
  }
---

Code that accompanies my papers. For all of my public repositories, see my [GitHub profile](https://github.com/TianminX).

<div class="software-grid">
  <article class="software-card">
    <h3>Open Set Conformal Classification</h3>
    <p>
      Reference implementation of conformal prediction sets for classification with rare and previously unseen labels. It includes conformal tests for
      new classes inspired by the Good Turing estimator, selective sample splitting with reweighting, and scripts to reproduce the simulations and the
      CelebA experiments.
    </p>
    <div class="software-tags"><span>Python</span><span>Jupyter</span><span>Conformal inference</span></div>
    <div class="software-links">
      <a href="https://github.com/TianminX/open-set-conformal-classification">GitHub</a>
      <a href="https://arxiv.org/abs/2510.13037">Paper</a>
    </div>
  </article>

  <article class="software-card">
    <h3>Structured Conformal Inference for Matrix Completion</h3>
    <p>
      Code for building joint confidence regions for groups of missing entries in matrix completion, with experiments on group recommender systems using
      MovieLens data. The repository is hosted on Ziyi Liang's GitHub.
    </p>
    <div class="software-tags"><span>Python</span><span>Jupyter</span><span>Matrix completion</span></div>
    <div class="software-links">
      <a href="https://github.com/ZiyiLiang/simultaneous-matrix-completion">GitHub</a>
      <a href="https://doi.org/10.1080/01621459.2026.2658287">Paper</a>
    </div>
  </article>
</div>
