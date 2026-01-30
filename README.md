# 🚀 Gemma-3 Small Language Model (270M) – Built from Scratch

This repository contains the complete implementation of **Gemma-3 Small Language Model (SLM, \~270M parameters)** built entirely from scratch. The project demonstrates dataset preprocessing, tokenization, training pipeline design, and transformer-based architecture construction without relying on pre-built LLM frameworks.

## 📖 Project Overview

* **Objective:** Build a small language model capable of generating creative and coherent text.
* **Dataset:** [TinyStories](https://huggingface.co/datasets) – a synthetic dataset of short stories designed for simple language understanding.
* **Parameter Size:** \~270M (scaled from an initial target of 50–60M).

## 🔑 Key Features

* Implemented **Byte Pair Encoding (BPE) tokenization** from scratch.
* Created efficient **I/O batching pipeline** with memory-mapped storage (`train.bin`, `validation.bin`).
* Defined a **Transformer architecture** with embeddings, RMSNorm, RoPE, and attention mechanisms.
* Trained on TinyStories with **PyTorch** for reproducible and scalable experiments.
* Includes evaluation scripts for **perplexity measurement** and text generation.

## 📊 Results

* Achieved strong text generation on **TinyStories** with low perplexity.
* Demonstrated scalability from a small model (50M) to \~270M parameters.
