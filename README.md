# Build DeepSeek from Scratch

A hands-on guide to understanding and implementing the key architectural innovations behind DeepSeek — **Multi-Head Latent Attention (MLA)**, **Mixture-of-Experts (MoE)**, **Multi-Token Prediction**, and **RL-based training (GRPO)**.


### Repository Structure

The repository is organized by chapter. Each `chXX/` directory contains the `README.md` with a summary and links to relevant videos, and a subdirectory with the code listings (`.ipynb` notebooks) for that chapter.

- **/ch01/**: Introduction to the DeepSeek.
- **/ch02/**: The Road to MLA: Understanding the KV Cache Bottleneck.
- **/ch03/**: The DeepSeek Breakthrough: Multi-Head Latent Attention (MLA).
- **/ch04/**: Mixture-of-Experts (MoE) in DeepSeek.
- **/ch05/**: Multi-Token Prediction and FP8 Quantization.
- **/ch06/**: The DeepSeek Training Pipeline.
- **/ch07/**: Post Training: SFT and Reinforcement Learning. Includes the runnable [minimal GRPO + RLVR code](ch07/01_main-chapter-code/grpo_rlvr_minimal.py).
- **/ch08/**: Knowledge Distillation.


