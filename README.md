# Amazon Review Summarization

This project evaluates extractive and generative summarization models on the Amazon Product Reviews dataset.

## Goals
- Build a preprocessing pipeline for Amazon reviews
- Compare TextRank, a transformer model (e.g., T5/BART), and an LLM (e.g., LLaMA/Mistral)
- Evaluate summaries using ROUGE, BLEU, and BERTScore

## Structure
- `notebooks/` – Jupyter notebooks for experiments
- `dataset/` –  dataset link
- `scripts/` – Python scripts 
- `outputs/` – dumped csv files

## Environment
Main libraries: `pandas`, `numpy`, `transformers`, `torch`, `rouge-score`, `sacrebleu`, `bert-score`.
