---
layout: default
title: Signals and Systems and Machine Learning
---

# <u>Shared Concepts Between Signals and Systems and Machine Learning</u>

* Like data, signals are represented as vectors, and like data passing through machine learning models, signals undergo linear and nonlinear transformations as they pass through signal processing chains.
* Linear regression is a simple model in machine learning, and it's also used to design linear and nonlinear signal processing blocks. However, the weights in signal processing blocks are found by solving the normal equation instead of by gradient descent.
* Just like machine learning models, signal processing blocks balance bias and variance.
* The fundamental performance metric in signals and systems is error vector magnitude (EVM), which measures the mean squared error between the reference signal (ground truth) and received signal (prediction).
* A filter is any block with memory, and memory is used in machine learning.
	* In gradient descent, momentum is mathematically equivalent to applying a first-order IIR lowpass filter to the gradient. This smooths out high-frequency components or sudden changes in the gradient, in much the same way signal filtering removes noise.
	* Conceptually, the standard RNN is like a first-order IIR filter, where each output depends on previous outputs and the current input. This memory enables the RNN to "remember" past tokens while processing the current token.
* To equalize a filtered signal, you project it onto the reference signal. This is exactly the same linear algebra concept behind cosine similarity and text embeddings.
* Hyperparameter tuning is used to improve machine learning models. It's also used in filter design to balance performance with hardware and software complexity. For example, for a simple lowpass filter, you can tune the cutoff frequency, the number of taps, and the bitwidth. If you want your filter to support multiple configurations, then you need software control logic. If you need dynamic programming, then you need both software and hardware support.
* Convolutional filters are a basic element of signal processing chains. Each convolutional filter in a CNN is like a matched filter in signal processing, except the weights are learned.
* Positional encoding in transformers map global information to slow sinusoids and local information to fast sinusoids. An OFDM waveform maps data (bits) to sinusoids of different frequencies.
* **Most importantly, both machine learning and signals and systems are engineering fields, and the same skills - experimentation, analysis, data visualization, and debugging - are valuable in both.**