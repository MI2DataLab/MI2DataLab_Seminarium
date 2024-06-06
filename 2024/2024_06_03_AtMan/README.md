# AtMan: Understanding Transformer Predictions Through Memory Efficient Attention Manipulation

On this seminar presentation we will go through "AtMan: Understanding Transformer Predictions Through Memory Efficient Attention Manipulation" article related to XAI methods for Transformer-based models. XAI for large transformer models is demanding due to high computational costs of gradient calculation. To solve this problems authors proposed ATMAN method for text and image-text models. ATMAN is a modality-agnostic perturbation method that manipulates the attention mechanisms of transformers to produce relevance maps for the input with respect to the output prediction. Instead of using backpropagation, ATMAN applies a parallelizable token-based search method relying on cosine similarity neighborhood in the embedding space.

This presentation was based on [this paper](https://arxiv.org/abs/2301.08110)

