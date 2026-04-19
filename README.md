# NLP Assignment 2

This repository contains a from-scratch neural NLP pipeline in PyTorch.

## What is included
- `i23-2606_Assignment2_DS-C.ipynb`: complete notebook (Parts 1 to 8)
- `report.pdf`: assignment report
- `embeddings/`: saved TF-IDF, PPMI, and Word2Vec embeddings
- `models/`: saved BiLSTM POS, BiLSTM NER, and Transformer classifier weights
- `data/`: CoNLL files for POS and NER

## How to run
1. Open the notebook `i23-2606_Assignment2_DS-C.ipynb`.
2. Run cells from top to bottom in order.
3. Generated artifacts are saved in `embeddings/`, `models/`, and `data/`.

## Final comparison result (Part 8.2)
- Transformer test accuracy: 0.7000
- Transformer macro-F1: 0.4465
- BiLSTM test accuracy: 0.5000
- BiLSTM macro-F1: 0.1333
- BiLSTM best validation epoch: 5
- Transformer best validation epoch: 17
- BiLSTM is faster per epoch (~2.80s vs ~19.2s)

## Notes
- Implementation avoids pretrained models and built-in PyTorch Transformer encoder classes, as required.
- The notebook contains plots, metrics, and analysis for each part.
