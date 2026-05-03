# Hinglish Sentiment Analysis

This project performs sentiment analysis on Hinglish (Hindi-English code-mixed) tweets using transformer models and an optimized ensemble approach.

## Overview
- Fine-tuned multiple transformer models (mBERT, XLM-R, MuRIL, etc.)
- Compared performance using accuracy and weighted F1-score
- Built a weighted ensemble using SLSQP optimization

## Results
- Best individual model (mBERT): F1 = 0.9018  
- Optimized ensemble: F1 = 0.9088  

## Files
- `hinglish-sentiment-analysis.ipynb` – implementation  
- `paper.pdf` – detailed methodology and results  
