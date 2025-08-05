# Task 1: Applying Beam Search to a Pretrained LSTM-based NMT Model

## Project Overview

This project implements Beam Search decoding on a basic LSTM-based Neural Machine Translation (NMT) model for English to French translation.  
The main goal is to improve translation quality by applying **Beam Search** instead of greedy decoding.

GUI is not required.  
Accuracy and decoding logic are the main evaluation criteria.

---

## Model Details

- **Architecture:** Seq2Seq using LSTM encoder-decoder
- **Input Language:** English
- **Target Language:** French
- **Tokenizer:** Keras Tokenizer
- **Search Strategy:** Beam Search (beam width = 3)
- **Training Data:** 5 English-French sentence pairs (demo)

---

## Requirements

Install the required libraries using:

```bash
pip install -r requirements.txt

