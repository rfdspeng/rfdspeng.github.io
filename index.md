---
layout: default
title: Home
---

**[GitHub]({{ site.github }}), [Resume]({{ site.resume }}), [LinkedIn]({{ site.linkedin }})**

# <u>From Signals and Systems to Machine Learning</u>

Hello! My name is **Ryan Tsai**, and I'm a **machine learning and AI engineering student** enrolled in the Machine Learning Engineering bootcamp at WeCloudData. I'm a **career switcher - I have 10 years of experience as a systems engineer** for commercial cellular (4G and 5G) modem chipsets at Qualcomm and at Zeku.

**My previous work experience has been incredibly helpful for learning ML and doing ML projects.**

**There are many shared or analogous concepts between signals and systems and machine learning:**
* Signals are universally represented as vectors, and they undergo linear and nonlinear transformations through signal processing chains
* Convolutional filters are a basic element of signal processing chains. Each convolutional filter in a CNN is like a matched filter in signal processing, except the weights are learned.
* Linear regression is commonly used for modeling nonlinear systems (which involves feature engineering) and for designing linear filters, but the weights are found by solving the normal equation instead of gradient descent

**Just like in ML, hyperparameter tuning is critical for designing filters and other signal processing blocks.** For example, when I designed an upsampling digital filter chain for an RF transmitter, I employed an iterative process to tune the filter models, filter lengths, coefficient bitwidths, etc. to meet target metrics like EVM and image suppression and soft targets like hardware complexity.

**Here are some of my skills**, and please take a look at my [resume]({{ site.resume }}) and my projects to see how I've applied them:
* Programming languages: Python, MATLAB
* Machine learning frameworks: PyTorch, Scikit-learn, TorchMetrics, CUDA
* Data analysis and visualization: NumPy, pandas, Matplotlib
* Tools: Git, Conda, Spyder, Jupyter

# <u>Projects</u>

* **Histopathology Image Classification (supervised learning with CNN and vision transformer)**: Classify histopathology images of colorectal polyps as benign or precancerous [(view report and code)](https://rfdspeng.github.io/pages/mhist)