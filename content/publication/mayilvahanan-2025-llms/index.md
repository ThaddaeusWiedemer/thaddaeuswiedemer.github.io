---
title: "LLMs on the Line: Data Determines Loss-to-Loss Scaling Laws"
abstract: "Scaling laws guide the development of large language models (LLMs) by offering estimates for the optimal balance of model size, tokens, and compute. More recently, loss-to-loss scaling laws that relate losses across pretraining datasets and downstream tasks have emerged as a powerful tool for understanding and improving LLM performance. In this work, we investigate which factors most strongly influence loss-to-loss scaling. Our experiments reveal that the pretraining data and tokenizer determine the scaling trend. In contrast, model size, optimization hyperparameters, and even significant architectural differences, such as between transformer-based models like Llama and state-space models like Mamba, have limited impact. Consequently, practitioners should carefully curate suitable pretraining datasets for optimal downstream performance, while architectures and other settings can be freely optimized for training efficiency."
authors:
  - Prasanna Mayilvahanan
  - admin
  - Sayak Mallick
  - Matthias Bethge
  - Wieland Brendel
date: 2025-02-17
publication: ICML 2025
publication_types:
- paper-conference
# url_pdf: https://arxiv.org/pdf/2502.12120
url_pdf: https://openreview.net/forum?id=IVUjRWnU6c
url_code: https://github.com/brendel-group/llm-line
url_project: https://brendel-group.github.io/llm-line/
---