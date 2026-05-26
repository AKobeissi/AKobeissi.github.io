---
layout: page
title: Retrieval Gap Analysis for Financial QA
description: Research project on measuring and reducing retrieval failures in RAG pipelines for long-document financial question answering.
importance: 1
category: research
github: https://github.com/AKobeissi/financebench-rag-experiments
---

This project studies retrieval failure modes in retrieval-augmented generation (RAG) systems for financial question answering. The goal is to identify where evidence is lost and improve end-to-end answer quality through retrieval-focused interventions.

## Focus areas

- Error decomposition for long-document retrieval
- Retrieval quality diagnostics and ablation studies
- Practical strategies to close the retrieval gap before generation

## Ongoing outcomes

- A reproducible evaluation pipeline for retrieval performance
- Quantitative analysis of retrieval-to-generation failure transfer
- A framework for testing retrieval improvements in realistic financial QA settings

## Poster

<a href="{{ '/assets/img/posters/rag_pipeline_poster.png' | relative_url }}" target="_blank" rel="noopener noreferrer"><img src="{{ '/assets/img/posters/rag_pipeline_poster.png' | relative_url }}" alt="RAG pipeline poster preview" style="max-width: 700px; width: 100%; height: auto;" /></a>

## Links

- GitHub: [financebench-rag-experiments](https://github.com/AKobeissi/financebench-rag-experiments)
- Paper (arXiv): [Decomposing Retrieval Failures in RAG for Long-Document Financial Question Answering](https://arxiv.org/abs/2602.17981)
- Poster (PNG): [RAG pipeline poster]({{ '/assets/img/posters/rag_pipeline_poster.png' | relative_url }})
