# Extending the Context Length of Large Language Models

## Overview

Welcome to the repository for my MTech project on "Extending Context Length of Large Language Models." This project aims to explore and extend the context length of state-of-the-art language models, such as GPT-3, BERT, and Transformer-based architectures. By increasing the context length, we intend to enhance the capabilities of these models in understanding and generating longer and more coherent text.

## Background

Large language models have demonstrated remarkable performance in various natural language processing (NLP) tasks. However, they are limited by their fixed context window, typically around 512 to 2048 tokens. This limitation poses challenges in handling longer documents, conversations, or texts that require a broader context for meaningful understanding and generation.

This project addresses the challenge of extending the context length of these models, allowing them to process and generate text with larger contexts. Achieving this will open up opportunities for applications in document summarization, long-form content generation, and more.

## Project Goals

- Investigate existing literature, papers, and blogs related to context length extension in language models.
- Implement and experiment with different techniques and strategies for increasing the context length.
- Create a comprehensive set of code examples and resources to help the community extend context length in their NLP projects.

## Coding Languages and Models

This project primarily utilizes the following technologies and models:

- Python: The primary programming language for developing code and experiments.
- PyTorch and Hugging Face Transformers: Frameworks for building and fine-tuning language models.
- GPT-3, BERT, and Transformer Architectures: Large pre-trained language models that serve as the foundation for our research.

## Contents

This repository is organized into folders, each focusing on a specific aspect or technique related to context length extension:

- **Sinusoidal Positional Encoding in Transformers**: This section explores the use of Sinusoidal Positional Encoding, a classic technique used in transformers to add positional information to tokens. We'll delve into the details of how this encoding works and its impact on extending context length.

- **Rotary Positional Encoding**: In this section, we delve into Rotary Positional Encoding, a novel technique designed to improve positional encoding in transformers. We'll provide code examples and explanations to demonstrate how rotary embeddings can enhance context length capabilities.

- **Extending Context Length using Position Interpolation**: Technique 3 focuses on Position Interpolation, a method to extend the context length of language models. We'll discuss the theory behind position interpolation and provide practical implementations to effectively increase context length.

Feel free to explore these folders to understand and experiment with the various techniques we are investigating.


## References

Throughout this project, I have referred to several papers and blogs that provide valuable insights into the field of context length extension in language models. Here are some of the key references:

- [Attention Is All You Need](https://arxiv.org/abs/1706.03762): This seminal paper introduced the Transformer architecture, which is the foundation of many modern language models. It revolutionized natural language processing and laid the groundwork for context length extension techniques. We particularly draw inspiration from this paper's use of sinusoidal positional encoding.

- [RoFormer: Enhanced Transformer with Rotary Position Embedding](https://arxiv.org/abs/2104.09864): This paper presents RoFormer, a Transformer variant that incorporates Rotary Position Embedding to extend the context window. RoFormer has shown promising results in handling longer sequences of text, making it a crucial reference for our project.

- [Extending Context Window of Large Language Models via Positional Interpolation](https://arxiv.org/abs/2306.15595): This paper discusses practical techniques for extending the context window of large language models using positional interpolation. It offers insights and ideas that we have incorporated into our project's approach.

Please refer to these sources for in-depth explanations and background information on context length extension techniques in language models.

## Getting Started

To get started with this project, follow these steps:

1. Clone this repository to your local machine.
2. Explore the code examples in the individual technique folders.
3. Install the required dependencies mentioned in the project's `requirements.txt` file.
4. Experiment with different techniques and adapt them to your specific use cases.

## Contributions

Contributions to this project are welcome! If you have new ideas, techniques, or improvements related to context length extension in language models, feel free to submit pull requests.

## Contact

For any questions or inquiries related to this project, please contact me at ayushsingh@iisc.ac.in.

Happy coding and extending context length in language models!
