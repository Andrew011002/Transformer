# Transformer

### Description
A sequence to sequence transformer model built from scratch using PyTorch for English to German language translation.

## Motivation
In my time understanding and implementing Artificial Intelligence (AI) & Machine Learning (ML) techniques, I stumbled across the Neural Network, the Convolutional Neural Network (CNN), and the previously popular Long Short-Term Memory (LSTM) architecture. All of these models amazed me because of their capabilities for tasks like image classification, natural language processing (NLP), and even training agents to out perform humans in games through reinforcement learning. I had thought this was where AI & ML reached its submit until I stumbled across the famous [Attention Is All You Need Paper](https://arxiv.org/abs/1706.03762). When I had read and dissected the paper, I was blown away at the potential of the architecture and the future for the newer field of Deep Learning (DL). The paper itself was a breakthrough in DL and pathed the way for extremely powerful Large Language Models (LLM) like: GPT-2 & 3, BERT, XLNET, and as of the time of writing this, ChatGPT which shockingly human-like. The culmination of these models inspired me to undertake the difficult task of building one from scratch. While the challenge was difficult, as well as time consuming, building the original sequence to sequence transformer model gave me a deeper understanding of Self-Attention and its possible applications outside of NLP (e.g. vision networks, diffusion models, etc.). In the end, I hope I can share my version of the transformer and also help you understand the pieces that make it powerful.

## Transformer Explained
The transformer architecture can look complex and hard to comprehend at a glance. In this section, I will break down each part to make it easier to digest and show you just how it works. Before I continue, I assume you are familiar with concepts and terms such as: matrix operations, forward propagation, backward propagation, activation functions, loss functions, gradient descent, optimizers, and neural networks. I also assume you have some experience with programming in python, working with PyTorch, and some background in NLP.

To begin, the transformer is a Deep Neural Network (DNN) that uses the self-attention mechanism to learn how words relate to one another within a sequence based on their meaning (embeddings), their meaning based on their position in the sequence (positional encodings), and their meaning in respect to the words around it (similarity scores). Its approach of this not only yields its superb results, but also resolves some of the pitfalls of the LSTM and sequence based CNN.

### Learning Longer Dependencies
Before the transformer, Recurrent Neural Networks (RNN) were very popular for NLP tasks. In short, a RNN is a DNN that uses internal memory to process sequential data based on the current input previous states, and previous hidden states. This was great for processing shorter text sequence based data, but as the sequences grew in length, their ability to learn relationships within the sequences diminished. Considering we humans can interpret long sequences of text, it's clear this is a downside of RNNs. [(more on RNNs from this article)](https://medium.com/analytics-vidhya/undestanding-recurrent-neural-network-rnn-and-long-short-term-memory-lstm-30bc1221e80d). A solution to this issue gave rise to the aforementioned LSTM. The LSTM is a derivative of the RNN that still uses recurrence but adds gates that act as a filter for information. These gates moderate what information should be kept and forgetten as the network processes sequential data. This architecture solved the issue with learning longer dependecies, but only up to a certain magnitude. The architecutre still struggled with learning even longer sequences and because it retained sequential data processing with added complexity, training became more expensive and time consuming [(more on LSTMs from this article)](https://towardsdatascience.com/the-fall-of-rnn-lstm-2d1594c74ce0). 



## Installation

Open your terminal, then copy & paste the command in your desired directory location

```bash
git clone https://github.com/Andrew011002/
```

## Running
How to run the file

## Contributing
If you find bugs or issues in the code, feel free the make a pull request or open an issue. You can also email me: andrewholmes011002@gmai.com or tweet at me @AndrewNerdimo

## Contact
[LinkedIn](https://www.linkedin.com/in/andrewmicholmes/) <br />
[Twitter](https://twitter.com/AndrewNerdimo)
