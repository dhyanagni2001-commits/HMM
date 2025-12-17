# Hidden Markov Models (HMM)

This project implements **Hidden Markov Model (HMM)** inference algorithms from scratch and applies them to **Part-of-Speech (POS) tagging**. The implementation focuses on dynamic programming–based inference and sequence decoding using the Viterbi algorithm.

---

## Project Overview
- Implements core HMM inference algorithms
- Applies HMMs to sentence tagging (POS tagging)
- Uses frequency-based parameter estimation
- Handles unseen words during inference

---

## Implementation Details
All implementation is done in:
- `hmm.py` – HMM inference algorithms
- `tagger.py` – POS tagging using HMM

Only these files are modified and graded.

---

## Features Implemented

### HMM Inference Algorithms
- Forward algorithm
- Backward algorithm
- Sequence probability computation
- Posterior state probability
- State transition likelihood
- Viterbi decoding (most likely state sequence)

### POS Tagging
- HMM parameter estimation from training data
- Sentence tagging using Viterbi
- Handling unseen words with smoothing

---

## How to Run
```bash
python hmm_test_script.py
