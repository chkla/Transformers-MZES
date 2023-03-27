# 🤖 Transformer-Based Language Models (Input Talk @ Method Bits, MZES, UMannheim)
Welcome to the transformer-based Language Models (LM) talk! You can find the slides for the talk here [![Google Slides](https://img.shields.io/badge/Slides-yellow?logo=google-slides)](https://docs.google.com/presentation/d/1py8jRKvNZXCrCCwtAtwgewMHEDM7d1iKI7E4cA_sgt0/edit?usp=sharing). In this talk, we will explore the power of transformer-based LMs and how they can be used for various research tasks.

This is a talk on Transformer-based Language Models, covering a range of topics including what language models are, why we need a new architecture for them, the components that make the Transformer architecture so powerful, the differences between Transformer-based Language Models, how to train a state-of-the-art transformer model for various research tasks, and the limits and open challenges of these new types of Language Models. Related questions for this talk:
<details><summary>🤔 *What are Language Models?*</summary>
<br>
Language models are a type of machine learning model that can predict the probability of a sequence of words in a given context.
</details>
<details><summary>🚀 *Why do we need a new architecture (Transformer) for Language Models?*</summary>
<br>
The Transformer architecture was introduced to overcome the limitations of previous models, such as Recurrent Neural Networks (RNNs) and Long Short-Term Memory (LSTM) networks, in capturing long-term dependencies in text.
</details>
<details><summary>🔧 *What components make transformer architecture so powerful?*</summary>
<br>
The Transformer architecture is made up of several key components, including self-attention mechanisms, multi-head attention, and feed-forward neural networks.
</details>
<details><summary>🤖 *What are the differences between transformer-based Language Models?*</summary>
<br>
There are several different types of transformer-based language models, including autoregressive models like GPT-2 and GPT-3, and encoder-decoder models like BERT and RoBERTa.
</details>
<details><summary>🤓 *How can we train a SotA transformer model for various research tasks?*</summary>
<br>
In this workshop, we will provide hands-on sessions with Colab for implementing a language model for supervised topic classification, a domain adaptation approach, and a zero-shot NLI classification with an existing model.
</details>
<details><summary>🤯 *What are the limits and open challenges of these new types of Language Models?*</summary>
<br>
Despite their impressive performance on various tasks, transformer-based language models still face challenges such as data bias, explainability, and ethical concerns.
</details>


### 📝 Workshop Structure
* Introduction to Language Models
* Transformer Architecture and Components
* Differences between Transformer-Based Language Models
* Hands-on sessions to train LMs
* Limits and Open Challenges

### 🤓 Hands-on Sessions
This workshop includes three hands-on sessions using Google Colab:
* Supervised Topic Classification [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]([https://colab.research.google.com/drive/1K9zkPIUBPCWaVgg4duuYKirOrxAID0wG?usp=sharing](https://colab.research.google.com/drive/1jK_hD6XJDCEHnWj7yHyCOo8fmqjR3yx0?usp=sharing)): In this session, we will learn how to train a supervised topic classification model using a pre-trained transformer-based language model.
* Domain Adaptation [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]([https://colab.research.google.com/drive/1K9zkPIUBPCWaVgg4duuYKirOrxAID0wG?usp=sharing](https://colab.research.google.com/drive/1gaZU9pTCaNyzGdZJEL7sGvq07SsSEY38?usp=sharing)): In this session, we will learn how to fine-tune an existing language model to a specific domain by leveraging transfer learning techniques.
* Zero-Shot NLI Classification [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]([https://colab.research.google.com/drive/1K9zkPIUBPCWaVgg4duuYKirOrxAID0wG?usp=sharing](https://colab.research.google.com/drive/1Big34S9VkknUnhccQR3v-Zo5-JVUhdAv?usp=sharing)): In this session, we will learn how to use an existing transformer-based language model for zero-shot NLI classification (using the model trained by [Laurer et al. 2022](https://huggingface.co/MoritzLaurer/mDeBERTa-v3-base-mnli-xnli)).

### 🦜 Limitations and Open Challenges
As with any technology, Transformer-based Language Models have limitations and open challenges that need to be addressed (see [Bender et al. 2021](https://dl.acm.org/doi/10.1145/3442188.3445922)). Some of the current limitations and open challenges include:
* Environmental impact 🌳 💨
* Ethical considerations around the use of large-scale language models
* Ensuring the models are robust and not easily fooled 👺 by adversarial attacks
* The need for more diverse and inclusive training data 📚 to reduce biases in the models
* Data privacy and security 🔒
* Developing methods for more efficient training and inference with these large-scale models 👩🏾‍🎓
* Model Interpretability 🔎

### 📚 Additional Resources
* [HuggingFace Transformers Library](https://huggingface.co) ([Wolf et al. 2020](https://aclanthology.org/2020.emnlp-demos.6.pdf))
* On the Dangers of Stochastic Parrots: Can Language Models Be Too Big? 🦜 [Bender et al. 2021](https://dl.acm.org/doi/10.1145/3442188.3445922)

### 🤖 Authors
Christopher Klamm

#### 📝 License
_This workshop is licensed under the MIT License._
