---
title: "Portfolio"
permalink: /portfolio/
author_profile: true
---

{% include base_path %}

Personal and coursework ML/AI projects, kept separate from professional work since these are learning projects, not production deliverables.

### [ReneWind — Wind Turbine Failure Prediction](#)

Compared 12 progressive neural network architectures (TensorFlow/Keras, later reimplemented in PyTorch to deepen understanding) for wind-turbine generator failure prediction — baseline → dropout regularization → class-weighting for ~9x imbalance → SGD vs. Adam → BatchNorm → a custom Focal Loss implementation written from scratch. Best model: 0.99 accuracy / 0.98 precision / 0.95 F1 on validation.

**Stack:** TensorFlow, Keras, PyTorch

### [HelmNet — Workplace Safety Helmet Classifier](#)

Built a workplace safety-helmet image classifier, comparing a from-scratch CNN against three VGG-16 transfer-learning variants (TensorFlow/Keras). All reached near-perfect metrics; selected the data-augmented variant specifically for robustness to messier real-world camera conditions, not because the benchmark numbers demanded it.

**Stack:** TensorFlow, Keras, CNN, VGG-16 Transfer Learning

### [Medical Assistant — RAG Question Answering](#)

Built a full retrieval-augmented question-answering pipeline over a medical reference manual: LangChain chunking (512 tokens, 50 overlap), sentence-transformer embeddings, a persisted ChromaDB vector store, top-k similarity retrieval, and local Mistral-7B-Instruct inference (GGUF-quantized, via llama.cpp) — evaluated with an LLM-as-judge methodology scoring retrieval and generation quality.

**Stack:** LangChain, ChromaDB, Sentence-Transformers, Mistral-7B, llama.cpp

### [AWS SageMaker — Bike-Rental Demand Prediction](#)

Built an end-to-end SageMaker pipeline: S3 data staging, training via the built-in XGBoost algorithm, an automatic hyperparameter tuning job (eta, gamma, min_child_weight, subsample), and deployment to a live real-time endpoint — validated with batch inference against held-out test data.

**Stack:** AWS SageMaker, XGBoost, boto3, S3

### [ttgrasp — DataFrame Profiling Utility](https://github.com/jilani20/ttgrasp)

A personal train/test DataFrame-profiling utility (Apache-2.0, 100% Python), published to PyPI and used across coursework projects for quick dataset inspection. Currently validating a bugfix via a release candidate on TestPyPI (0.0.9rc0) ahead of the next production release.

**Stack:** Python, PyPI packaging
