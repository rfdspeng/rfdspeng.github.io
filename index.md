---
layout: default
title: Home
---

**[GitHub]({{ site.github }})**

**[Resume]({{ site.resume }})**

**[LinkedIn]({{ site.linkedin }})**

# <u>From Signals and Systems to Machine Learning</u>

Hello! My name is **Ryan Tsai**, and I'm currently working as a data science consultant at [Beam Data](https://beamdata.ai/) after finishing the Machine Learning Engineering Program at [WeCloudData](https://weclouddata.com/). I worked as an RF hardware engineer, an RF systems engineer, and a modem systems engineer at Qualcomm for 10 years before deciding to switch careers.

I've noticed many parallels between signals and systems - my previous field - and machine learning:
* Like data, signals are represented as high-dimensional vectors, and like data passing through machine learning models, signals undergo successive linear and nonlinear transformations as they pass through signal processing chains.
* Linear regression is a simple model in machine learning, and it's also used to design linear and nonlinear signal processing blocks. However, the weights in signal processing blocks are typically found by solving the normal equation instead of by gradient descent.
* Just like machine learning models, signal processing blocks balance bias and variance.
* Most importantly, both fields require an engineer's mindset. The process of optimizing models and filters is the same - iterative testing, analysis, and adjustment based on quantitative metrics.

[Click here for the full list of shared concepts.](https://rfdspeng.github.io/pages/signals_and_systems)

# <u>Projects</u>

* **RAG Book Recommendation Chatbot** [(repo)](https://github.com/rfdspeng/ml_ai_portfolio/tree/main/book_recommender)
    * Indexed Goodreads book summaries into Qdrant vector database with OpenAI for text embedding
    * Developed FastAPI chatbot application with Qdrant vector search and OpenAI chat completion
    * Deployed containerized application to AWS EC2
* **Clinical Dialogue Summarization (supervised fine-tuning with Seq2Seq language model)** [(repo)](https://github.com/rfdspeng/ml_ai_portfolio/tree/main/text_summ)
    * Fine-tuned BART model, using low-rank adaptation, to summarize clinical dialogues, achieving 97% ROUGE-L on the training data but only 47% on the validation data.
    * Analyzed the dataset by embedding the dialogues and proved that the dataset is too small and noisy for generalization.
* **Histopathology Image Classification (supervised learning with CNN and vision transformer)** [(repo)](https://github.com/rfdspeng/ml_ai_portfolio/tree/main/mhist)
    * Employed image augmentation, class balancing, and transfer learning to achieve an AUC of 94.2% with ResNet-18 and 94.8% with ViT-Base on the test dataset, outperforming the research paper’s AUC of 92.7%.