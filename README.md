# Build LLM from Scratch – Research Based Assessment

This project implements a decoder-only Transformer-based Large Language Model (LLM) from scratch using PyTorch.

The model was trained on text datasets collected from Project Gutenberg and multiple experiments were performed to study transformer training dynamics and architectural behavior.

## Experiments Performed

- Baseline Transformer Training
- Learning Rate and Epoch Analysis
- Transformer Layer Analysis
- Attention Head Analysis
- Ablation Studies
  - Without Layer Normalization
  - Without Residual Connections
  - Without Feed Forward Network

## Technologies Used

- Python
- PyTorch
- Google Colab
- Transformer Architecture
- Matplotlib
- Tiktoken Tokenizer

## Files

- `Exp1-Exp2.ipynb` → Baseline, Experiment 1 and Experiment 2
- `Exp3-Exp4.ipynb` → Experiment 3 and Experiment 4

## Key Findings

- Increasing transformer depth improves representation learning up to an optimal point.
- Multi-head attention improves contextual understanding.
- Residual connections are critical for stable transformer training.
- Larger models tend to overfit on smaller datasets.

## Author

Soham Ghorpade
