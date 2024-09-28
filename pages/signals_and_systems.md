---
layout: default
title: Signals and Systems and Machine Learning
---

# Work in progress

* **Signals are universally represented as vectors**, and they undergo linear and nonlinear transformations through signal processing chains
* **Convolutional filters are a basic element of signal processing chains.** Each convolutional filter in a CNN is like a matched filter in signal processing, except the weights are learned.
* **Linear regression** is commonly used for modeling nonlinear systems (which involves feature engineering) and for designing linear filters, but the weights are found by solving the normal equation instead of gradient descent
* A **standard RNN** is like a first-order IIR filter
* **Positional encoding** in transformers is like how an OFDM signal maps information to sinusoids of different frequencies (orthogonal tones)
* Applying momentum to gradient descent is like applying a first-order IIR filter to the gradient
* Inner product/projection for attention
* Cosine similarity for word embeddings
* Overfitting - number of parameters vs. dataset size; bias and variance
* Quantization of models