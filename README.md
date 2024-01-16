This project is associated with Arizona State University, released under CSE 574: Planning/Learning Methods AI course. For access to the complete source code, please contact me at my [email](mailto:asroideva@gmail.com) address.

# Enhancing Question Generation with Novel Reward Functions: Evaluation and Comparison
Duration: Sept 2023 - Nov 2023

## Overview
The primary objective of this project is to investigate existing reward functions in the context of question generation with large language models and subsequently develop novel reward functions. By fine tuning a base LLM through Reinfocement Learning, the project aims to enhance the quality of question generation using reward functions. This study examines and compares these new approaches to see how well they work and what improvements they bring.

## Project Details:
Architecture:
- Pretrained SQuADv2 model
- PPO (Proximal Policy Optimization) instead of SCST (Self-Critical Sequence Training)

Hyperparameters:
- Batch Size: 512
- Total Batches: 50 out of 170
- Learning Rate: 5e-5
- Generation Kwargs: "min_new_tokens": 1, "max_new_tokens": 32

Dataset:
- [SQuADv2](https://pytorchnlp.readthedocs.io/en/latest/_modules/torchnlp/datasets/squad.html)

# Skills
- LLMs (Large Language Models)
- Fine tuning
- Data Analysis
- Deep Learning
- Reinforcement Learning

# References
- [paper](https://dl.acm.org/doi/pdf/10.1145/3471158.3472240)





