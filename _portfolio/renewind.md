---
title: "ReneWind — Wind Turbine Failure Prediction"
excerpt: "Compared 12 progressive neural network architectures (TensorFlow/Keras, later PyTorch) for wind-turbine generator failure prediction, including a custom Focal Loss implementation. Best model: 0.99 accuracy / 0.98 precision / 0.95 F1."
collection: portfolio
---

Compared 12 progressive neural network architectures (TensorFlow/Keras, later reimplemented in PyTorch to deepen understanding) for wind-turbine generator failure prediction — baseline → dropout regularization → class-weighting for ~9x imbalance → SGD vs. Adam → BatchNorm → a custom Focal Loss implementation written from scratch. Best model: 0.99 accuracy / 0.98 precision / 0.95 F1 on validation.

**Stack:** TensorFlow, Keras, PyTorch
