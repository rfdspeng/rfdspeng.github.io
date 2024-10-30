---
layout: default
title: Signals and Systems and Machine Learning
---

# <u>Shared Concepts Between Signals and Systems and Machine Learning</u>

* Signals are universally represented as vectors, and they undergo linear and nonlinear transformations through signal processing chains
* Convolutional filters are a basic element of signal processing chains. Each convolutional filter in a CNN is like a matched filter in signal processing, except the weights are learned.
* Linear regression is commonly used for modeling nonlinear systems (which involves feature engineering) and for designing linear filters, but the weights are found by solving the normal equation instead of by gradient descent. Signal processing systems are also suscesptible to overfitting and underfitting. Generalization was a concern - number of filter taps for equalization, notch filter settings for different spur levels, 
* Linear regression/EVM
* Hyperparameter tuning
* In gradient descent, momentum is mathematically equivalent to applying a first-order IIR filter to the gradient
* Conceptually, the standard RNN is like a first-order IIR filter
* **Positional encoding** in transformers is like how an OFDM signal maps information to sinusoids of different frequencies (orthogonal tones)
* Inner product/projection for attention
* Cosine similarity for word embeddings
* Quantization of models
* Thinking like an engineer, analysis, debugging, math