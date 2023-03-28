# 🤖 Transformer-Based Language Models (Input Talk @ Method Bits, MZES, UMannheim)
Welcome to the transformer-based Language Models (LMs) talk! You can find the slides of the talk here [![Google Slides](https://img.shields.io/badge/Slides-yellow?logo=google-slides)](https://docs.google.com/presentation/d/1py8jRKvNZXCrCCwtAtwgewMHEDM7d1iKI7E4cA_sgt0/edit?usp=sharing). In this talk, we covering a winde range of topics including what language models are, why we need a new architecture for them, the components that make the Transformer architecture so powerful, the differences between Transformer-based Language Models, how to train a state-of-the-art transformer model for various research tasks, and the limits and open challenges of these new types of Language Models. Questions for this talk:
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
In this talk, we will provide hands-on sessions with Colab for implementing a language model for supervised topic classification, a domain adaptation approach, and a zero-shot NLI classification with an existing model.
</details>
<details><summary>🤯 *What are the limits and open challenges of these new types of Language Models?*</summary>
<br>
Despite their impressive performance on various tasks, transformer-based language models still face challenges such as data bias, explainability, ethical concerns and many more.
</details>


### 📝 Workshop Structure
* Introduction to Language Models
* Transformer Architecture and Components
* Differences between Transformer-Based Language Models
* Hands-on sessions with HuggingFace 🤗
* Limits and Open Challenges

### 🤓 Hands-on Sessions
This workshop includes three hands-on sessions using Google Colab:
* Supervised Classification [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1mxfxJ9rEMyxWP-L0aJL4JB0WhCPeFQxM?usp=sharing): In this session, we will learn how to use pre-trained transformer-based language model with HuggingFace 🤗 Pipelines.
* Fine-Tuning a pre-trained Language Model [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1R_pwYcaw3INGyf6hM9gNt_E_UGWp6BoN?usp=sharing) or the [Tutorial on BERT an Explainable AI](https://www.mzes.uni-mannheim.de/socialsciencedatalab/article/bert-explainable-ai/#bert-training) by Küpfer/Meyer (2023) : In this session, we will learn how to fine-tune an existing language model to a specific task.
* Optional: Zero-Shot Classification [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]([https://colab.research.google.com/drive/1jK_hD6XJDCEHnWj7yHyCOo8fmqjR3yx0?usp=sharing](https://colab.research.google.com/drive/1n8no7qfckIP-IrF2RNS8_AdRy0dok6bu?usp=sharing)): You can also check out the Tutorial by [Laurer et al. 2022]([https://huggingface.co/MoritzLaurer/mDeBERTa-v3-base-mnli-xnli](https://colab.research.google.com/drive/1-y7o-QRWp-OwGMe64CxQwQk2-o2jZFm3?usp=sharing)) on how to train an existing transformer-based language model for zero-shot NLI classification.

### 🦜 Limitations and Open Challenges
As with any technology, Transformer-based Language Models have limitations and open challenges that need to be addressed (see [Bender et al. 2021](https://dl.acm.org/doi/10.1145/3442188.3445922)). Some of the current limitations and open challenges:
* Environmental impact 🌳 💨
* Ethical considerations around the use of large-scale language models
* Ensuring the models are robust and not easily fooled 👺 by adversarial attacks
* The need for more diverse and inclusive training data 📚 to reduce biases in the models
* Data privacy and security 🔒
* Developing methods for more efficient training and inference with these large-scale models 👩🏾‍🎓
* Model Interpretability 🔎

### 📚 Additional Resources/ Tools
* [HuggingFace Transformers Library](https://huggingface.co) ([Wolf et al. 2020](https://aclanthology.org/2020.emnlp-demos.6.pdf))
* On the Dangers of Stochastic Parrots: Can Language Models Be Too Big? 🦜 [Bender et al. 2021](https://dl.acm.org/doi/10.1145/3442188.3445922)
* [OpenAi/ChatGPT-Retrieval-Plugins](https://github.com/openai/chatgpt-retrieval-plugin) e.g., Retrieval Plugin that has access to the UN Annual Reports from 2018 to 2022 [Video](https://cdn.openai.com/chat-plugins/retrieval-gh-repo-readme/Retrieval-Final.mp4)

### 👤 Author
Christopher Klamm

#### 📝 License
_This talk is licensed under the MIT License._
