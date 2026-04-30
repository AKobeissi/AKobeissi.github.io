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

## Links

- GitHub: [koopman-mpc-portfolio-rebalancing](https://github.com/AKobeissi/koopman-mpc-portfolio-rebalancing)
- Reference material: [Project README](https://github.com/AKobeissi/koopman-mpc-portfolio-rebalancing#readme)
- Notebook/demo: [Koopman learning notebook](https://github.com/AKobeissi/koopman-mpc-portfolio-rebalancing/blob/main/notebooks/Koopman_learning.ipynb)
