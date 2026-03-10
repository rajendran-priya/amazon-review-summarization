# Amazon Review Summarization

This project evaluates extractive and generative summarization models on the Amazon Product Reviews dataset.

## Goals
- Build a preprocessing pipeline for Amazon reviews
- Compare TextRank, a transformer model (e.g., T5/BART), and an LLM (e.g., LLaMA/Mistral)
- Evaluate summaries using ROUGE, BLEU, and BERTScore

## Structure
- `notebooks/` – Colab/Jupyter notebooks for experiments
- `data/` – Sampled Amazon reviews (not committed if large)
- `src/` – Reusable Python scripts (later)

## Environment
Main libraries: `pandas`, `numpy`, `transformers`, `torch`, `rouge-score`, `sacrebleu`, `bert-score`.
