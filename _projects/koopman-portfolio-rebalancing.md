---
layout: page
title: Koopman Dynamics for Portfolio Rebalancing
description: Learning sparse Koopman representations to improve long-horizon portfolio dynamics modeling and rebalancing.
importance: 3
category: research
github: https://github.com/AKobeissi/koopman-mpc-portfolio-rebalancing
---

This project studies Koopman-based latent dynamics modeling for financial time series and portfolio control. The codebase implements sparse Koopman autoencoder variants to better model nonlinear market dynamics while preserving stable long-horizon prediction behavior.

## Summary

- Implements multiple Koopman autoencoder variants (including sparse and LISTA-based encoders)
- Evaluates long-horizon rollout quality under several re-encoding strategies
- Supports reproducible training/evaluation pipelines and structured metrics exports

## Poster

<a href="{{ '/assets/pdf/posters/koopman-dynamics-poster.pdf' | relative_url }}" target="_blank" rel="noopener noreferrer">
  <img
    src="{{ '/assets/img/posters/koopman-dynamics-poster.png' | relative_url }}"
    alt="Koopman dynamics poster preview"
    style="max-width: 700px; width: 100%; height: auto;"
  >
</a>

## Links

- GitHub: [koopman-mpc-portfolio-rebalancing](https://github.com/AKobeissi/koopman-mpc-portfolio-rebalancing)
- Reference material: [Project README](https://github.com/AKobeissi/koopman-mpc-portfolio-rebalancing#readme)
- Notebook/demo: [Koopman learning notebook](https://github.com/AKobeissi/koopman-mpc-portfolio-rebalancing/blob/main/notebooks/Koopman_learning.ipynb)
- Poster (PDF): [Koopman dynamics poster]({{ '/assets/pdf/posters/koopman-dynamics-poster.pdf' | relative_url }})
