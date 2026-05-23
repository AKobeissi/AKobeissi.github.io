---
layout: page
title: PGM for Vehicle Route Optimization with Reinforcement Learning
description: A project at the intersection of probabilistic graphical models and RL for vehicle routing.
importance: 2
category: research
github: https://github.com/AKobeissi/pgm-reinforcement-learning
---

This project explores how **probabilistic graphical models (PGMs)** and **reinforcement learning (RL)** can be combined for vehicle route optimization. The codebase includes baseline and advanced RL implementations, route visualizations, and benchmarking artifacts.

- **What I built:** end-to-end experiments for route planning policies, including environment design and training/evaluation loops
- **Core idea:** use probabilistic structure and RL objectives to improve route quality under operational constraints
- **Outputs:** reproducible experiments, training diagnostics, and route/vehicle-load plots

## Poster

<a href="{{ '/assets/pdf/posters/pgm-vehicle-routing-poster.pdf' | relative_url }}" target="_blank" rel="noopener noreferrer">
  <img src="{{ '/assets/img/posters/pgm-vehicle-routing-poster.png' | relative_url }}" alt="PGM vehicle routing poster preview" style="max-width: 700px; width: 100%; height: auto;" />
</a>

## Links

- **GitHub:** [AKobeissi/pgm-reinforcement-learning](https://github.com/AKobeissi/pgm-reinforcement-learning)
- **Reference paper:** [Towards Reinforcement Learning over State and Temporal Abstractions for Vehicle Routing Applications](https://arxiv.org/pdf/1805.00909)
- **Poster (PDF):** [PGM vehicle routing poster]({{ '/assets/pdf/posters/pgm-vehicle-routing-poster.pdf' | relative_url }})
- **Poster/script:** [benchmark/poster.py](https://github.com/AKobeissi/pgm-reinforcement-learning/blob/main/benchmark/poster.py)
