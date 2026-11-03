# Mini Text Generator – Tiny Shakespeare

## Project Overview
A lightweight text-generation model trained on the Tiny Shakespeare dataset using a custom Byte-Pair Encoding (BPE) tokenizer and a decoder-only Transformer implemented in PyTorch.

## Architecture
- Custom BPE tokenizer
- Vocabulary: 1,000 tokens
- Transformer layers: 2
- Attention heads: 2
- Embedding dimensions: 128
- Context length: 64
- Dropout: 0.1

## Training Configuration
- Dataset: Tiny Shakespeare
- Train-validation split: 90:10
- Epochs: 5
- Batch size: 32
- Optimizer: AdamW
- Learning rate: 0.001

## Results
- Final training loss: 2.6669
- Final validation loss: 2.8009
- GPU: NVIDIA Tesla T4

## Project Outputs
- Trained model weights
- BPE tokenizer merges
- Training loss graph
- Generated text samples
- Training metrics

## Technologies
Python, PyTorch, NumPy, Matplotlib, Google Colab.

## Author
-Rohit Jagtap
-Pratik Pawade
-Sagar Desale
