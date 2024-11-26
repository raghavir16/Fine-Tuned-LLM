# Fine-Tuned-LLM

This repository contains a large language model (LLM) fine-tuned to solve advanced physics problems using data derived from the University of Nottingham's undergraduate physics curriculum. The model is optimized using quantization and LoRA for improved computational efficiency, particularly on NVIDIA A100 GPUs.

Project Overview

Dataset: A custom dataset created from the University of Nottingham's undergraduate-level physics curriculum.
Preprocessing: Data cleaning and preparation techniques to ensure model readiness.
Model: Fine-tuned Numina Math TIR 7B LLM from Hugging Face to solve physics problems and generate executable Python code.
Optimization: Used quantization and LoRA to address computational constraints and enhance training efficiency.
Evaluation: Performance evaluated using NLP-based reasoning, including TF-IDF and cosine similarity metrics to assess solution accuracy against a reference answer key.

