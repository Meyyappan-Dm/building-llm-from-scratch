# 🧠 Building a Transformer-based Language Model from Scratch

This project is a minimal, educational implementation of a Transformer-based Language Model (like GPT) using PyTorch — built from scratch without relying on high-level libraries.
Inspired by Sebastian Raschka’s LLM lectures.

## 🚀 What I Built

- ✅ Custom tokenizer integration (using `tiktoken`)
- ✅ PyTorch dataset and dataloader with sliding-window tokenization
- ✅ GPT-style Transformer model with:
        - Multi-head self-attention
        - LayerNorm and GELU activation
        - Position embeddings
- ✅ Training loop with train/validation evaluation
- ✅ Text generation from a seed prompt
- ✅ Loss plotting and learning visualization

## Dependencies
      Python 3.8+
      PyTorch
      tiktoken
      matplotlib

## Future Work
     Load and fine-tune pretrained GPT weights
    
     Implement Top-k or nucleus sampling
    
     Add support for multi-GPU training
    
     Improve tokenization using custom BPE or SentencePiece
