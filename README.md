# Nano GPT From Scratch in Python

Hi, In this project I have implemented the decoder only transformer based Bigram Language Model for text generation task. I have used `William Shakespeare` writing to train the model. Entire code is in `Python` and `Pytorch` and it assumes a solid understanding of programming in `Python` and basic understanding of `Pytorch` module.



The flow of the project is following:
---
- Data Download
- Tokenization
- Data Loader
- Vanilla Bigram Model
- Intuition behind Self Attention
- Self head attention implementation
- Bigram Model with Self Attention
- Multi head attention implementation
- Feed Forward Layer attachement
- Bigram Model with transformer
- Optimization techniques
  - Dropout
  - Skip Connections
  - Layer Normalization
- Model Evaluation

Here, I have tried from a simple Bigram Labguage Model to a sophisticated Bigram LM by adding different techniques in the vanilla model. 

References
---
- <a href="https://arxiv.org/abs/1706.03762"> Attention Is All You Need </a>
- <a href="https://magazine.sebastianraschka.com/p/understanding-and-coding-self-attention">Understanding and Coding Self-Attention, Multi-Head Attention, Cross-Attention, and Causal-Attention in LLMs</a>
- <a href="https://www.youtube.com/watch?v=kCc8FmEb1nY"> Let's build GPT: from scratch, in code, spelled out by Andrej Karpathy</a>
