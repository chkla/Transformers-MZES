# 🤖 Transformer-Based Language Models (Input Talk @ Method Bits, MZES, UMannheim)
Welcome to the transformer-based Language Models (LMs) talk! You can find the slides of the talk here [![Google Slides](https://img.shields.io/badge/Slides-yellow?logo=google-slides)](https://docs.google.com/presentation/d/1eUmChBbDBaENQWVBBmytAiB7xpioPz2325-znhxB4xs/edit?usp=sharing). In this talk, we covering a winde range of topics including what language models are, why we need a new architecture for them, the components that make the Transformer architecture so powerful, the differences between Transformer-based Language Models, how to train a state-of-the-art transformer model for various research tasks, and the limits and open challenges of these new types of Language Models. Questions for this talk:

<details><summary>🤔 *What are Language Models?*</summary>
<br>
Language models are a specific type of machine learning model designed to predict the likelihood of word sequences in a given context. They are crucial in a variety of natural language processing tasks such as machine translation, speech recognition, and text generation.
</details>
<details><summary>🚀 *Why do we need a new architecture (Transformer) for Language Models?*</summary>
<br>
The Transformer architecture was developed to address the limitations of previous models like Recurrent Neural Networks (RNNs) and Long Short-Term Memory (LSTM) networks. These earlier models struggled with capturing long-term dependencies in text due to their sequential nature. Transformers, with their parallel processing capabilities and innovative self-attention mechanisms, excel at handling longer-range dependencies and offer significant performance improvements.
</details>
<details><summary>🔧 *What components make the Transformer architecture so powerful?*</summary>
<br>
The Transformer architecture's power comes from several key components, such as self-attention mechanisms that weigh the importance of words within a context, multi-head attention that allows the model to focus on different aspects of the input simultaneously, and feed-forward neural networks that process and generate the output. These components, combined with positional encoding, enable the architecture to handle large-scale language modeling tasks effectively.
</details>
<details><summary>🤖 *What are the differences between transformer-based Language Models?*</summary>
<br>
There are various types of transformer-based language models, each with unique characteristics. Autoregressive models like GPT-2 and GPT-3 generate text by predicting one word at a time, while encoder-decoder models like BERT and RoBERTa use masked language modeling to pre-train on large corpora before fine-tuning for specific tasks. These models differ in their architecture, training data, and objectives, resulting in different strengths and weaknesses.
</details>
<details><summary>🤓 *How can we train a state-of-the-art Transformer model for various research tasks?*</summary>
<br>
To train a state-of-the-art Transformer model for research tasks, we will provide hands-on sessions using Google Colab. These sessions will cover implementing a language model for supervised topic classification, a domain adaptation approach, and zero-shot NLI classification with an existing pre-trained model. By following these sessions, you will gain practical experience in fine-tuning Transformer models for various tasks.
</details>
<details><summary>🤯 *What are the limits and open challenges of these new types of Language Models?*</summary>
<br>
Transformer-based language models still face several challenges. These include data bias, which may result in biased predictions, limited explainability that makes it difficult to understand model decisions, and ethical concerns surrounding their potential misuse. Other challenges include computational resource requirements, the need for large-scale training data, and difficulty in handling tasks that require common sense or deep reasoning.
</details>


### 📝 Roadmap
* Introduction to Language Models
* Transformer Architecture and Components
* Differences between Transformer-Based Language Models
* Hands-on sessions with HuggingFace 🤗
* Limits and Open Challenges

### 🤓 Hands-on Sessions
This workshop includes three hands-on sessions using Google Colab:
* Supervised Classification [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1mxfxJ9rEMyxWP-L0aJL4JB0WhCPeFQxM?usp=sharing): In this session, we will learn how to use pre-trained transformer-based language model with HuggingFace 🤗 Pipelines.
* Fine-Tuning a pre-trained Language Model [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1R_pwYcaw3INGyf6hM9gNt_E_UGWp6BoN?usp=sharing) or the [Tutorial on BERT an Explainable AI](https://www.mzes.uni-mannheim.de/socialsciencedatalab/article/bert-explainable-ai/#bert-training) by Küpfer/Meyer (2023) : In this session, we will learn how to fine-tune an existing language model to a specific task.
* Optional: Zero-Shot Classification [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1n8no7qfckIP-IrF2RNS8_AdRy0dok6bu?usp=sharing): You can also check out the Tutorial by [Laurer et al. 2022](https://colab.research.google.com/drive/1-y7o-QRWp-OwGMe64CxQwQk2-o2jZFm3?usp=sharing) on how to train an existing transformer-based language model for zero-shot NLI classification.

### 🦜 Limitations and Open Challenges
As with any technology, Transformer-based Language Models have limitations and open challenges that need to be addressed (see [Strubell et al. 2019](https://aclanthology.org/P19-1355.pdf), [Bender et al. 2021](https://dl.acm.org/doi/10.1145/3442188.3445922), [Gebru et al. 2022](https://arxiv.org/pdf/1803.09010.pdf), [Levy et al. 2022](https://arxiv.org/pdf/2210.10045.pdf), etc.). Some of the current limitations and open challenges:
* Environmental impact 🌳 💨
* Ethical considerations around the use of large-scale language models
* Ensuring the models are robust and not easily fooled 👺 by adversarial attacks
* The need for more diverse and inclusive training data 📚 to reduce biases in the models
* Data privacy and security 🔒
* Developing methods for more efficient training and inference with these large-scale models 👩🏾‍🎓
* Model Interpretability 🔎
* ... and many more!

## 📚 Additional Resources/ Tools/ Literature
### Literature
* Alammar (2023) "What a time for language models" [[Blog](https://jayalammar.substack.com/p/what-a-time-for-language-models?utm_source=twitter&utm_campaign=auto_share&r=27wcsl)]
* Walsh (2021) "The BERT for Humanists Project" [[Blog](http://www.bertforhumanists.org)]
* Strubell et al. (2019) "Energy and Policy Considerations for Deep Learning in NLP" [[Paper](https://aclanthology.org/P19-1355.pdf)]
* Devlin et al. (2019) "BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding" [[Paper](https://aclanthology.org/P19-1355.pdf)]
* Bender et al. (2021) "On the Dangers of Stochastic Parrots: Can Language Models Be Too Big?" 🦜 [[Paper](https://dl.acm.org/doi/10.1145/3442188.3445922)]
* Brown et al. (2020) "Language Models are Few-Shot Learners" [[Paper](https://arxiv.org/pdf/2005.14165.pdf)]
* Wang et al. (2022) "SELF-INSTRUCT: Aligning Language Model with Self Generated Instructions" [[Paper](https://arxiv.org/pdf/2212.10560.pdf)]
* Gilardi et al. (2023) "ChatGPT Outperforms Crowd-Workers for Text-Annotation Tasks" [[Paper](https://arxiv.org/pdf/2303.15056.pdf)]
* Dai et al. (2023) "AugGPT: Leveraging ChatGPT for Text Data Augmentation" [[Paper](https://arxiv.org/pdf/2302.13007.pdf)]
* Reiss (2023) "Testing the Reliability of ChatGPT for Text Annotation and Classification: A Cautionary Remark" [[Paper](https://www.dropbox.com/s/3z7okruhft74o1a/ChatGPT_Reliability_0405.pdf?dl=0)]
* Kuzman et al. (2023) "ChatGPT: Beginning of an End of Manual Linguistic Data Annotation? Use Case of Automatic Genre Identification" [[Paper](https://www.semanticscholar.org/reader/31f44f0f2124c54e47f4df54dec63118232c25da)]
* Luccioni et al. (2022) "ESTIMATING THE CARBON FOOTPRINT OF BLOOM, A 176B PARAMETER LANGUAGE MODEL" [[Paper](https://arxiv.org/pdf/2211.02001.pdf)]
* Levy et al. (2022): "SAFETEXT: A Benchmark for Exploring Physical Safety in Language Models" [[Paper](https://arxiv.org/pdf/2210.10045.pdf)]
* Bubeck et al. (2023) "Sparks of Artificial General Intelligence: Early experiments with GPT-4" [[Paper](https://arxiv.org/pdf/2303.12712.pdf)]
* ... and many more!

### Tools
* [OpenAi/ChatGPT-Retrieval-Plugins](https://github.com/openai/chatgpt-retrieval-plugin) e.g., Retrieval Plugin that has access to the UN Annual Reports from 2018 to 2022 [Video](https://cdn.openai.com/chat-plugins/retrieval-gh-repo-readme/Retrieval-Final.mp4)
* [HuggingFace Transformers Library](https://huggingface.co) ([Wolf et al. 2020](https://aclanthology.org/2020.emnlp-demos.6.pdf))
* WandB "A platform helps you streamline your ML workflow from end to end" [[Web](https://wandb.ai/home)]
* LangChain (2023) "Framework for developing applications" [[Code](https://github.com/hwchase17/langchain)]
* Taori et al. (2023) "Alpaca: A Strong, Replicable Instruction-Following Model" [[Paper](https://crfm.stanford.edu/2023/03/13/alpaca.html)]
* ... and many more!

### Additional Ressources
* Standards/ Guidelines ➡️ https://github.com/chkla/NLP-Standards

#### 👤 Author
Christopher Klamm

#### 📝 License
_This talk is licensed under the MIT License._
