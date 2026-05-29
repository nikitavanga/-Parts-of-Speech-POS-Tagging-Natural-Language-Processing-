# -Parts-of-Speech-POS-Tagging-Natural-Language-Processing-

This project aims to create a system that could automatically identify the part of speech, noun, verb, adjective, etc., for any given English word. This is a crucial task in Natural Language Processing (NLP) with applications in sentiment analysis, machine translation, and more. 
I built and evaluated three machine learning models: Logistic Regression, Logistic Regression with PCA (Principal Component Analysis) for dimensionality reduction, and Logistic Regression with Word2Vec for incorporating semantic information.





# Context-Aware POS & Linguistic Intelligence Platform

## Overview

This project began as a machine learning-based Part-of-Speech (POS) Tagging system using:

- Logistic Regression
- Logistic Regression + PCA
- Logistic Regression + Word2Vec

The original research achieved:

| Model | Accuracy | F1 Score |
|---------|---------|---------|
| Logistic Regression | 48.09% | 43.67% |
| Logistic Regression + PCA | 48.85% | 42.42% |
| Logistic Regression + Word2Vec | 63.36% | 49.15% |

The project is now being upgraded into a modern NLP platform utilizing contextual language models, transformer architectures, linguistic analysis, explainability, and real-time inference.

---

## Project Goals

Build a Context-Aware Linguistic Intelligence Platform capable of:

- POS Tagging
- Contextual Disambiguation
- Dependency Parsing
- Lemmatization
- Explainable NLP
- Transformer-based Token Classification
- Sentence Complexity Analysis
- Ambiguity Detection

---

## Example

Input:

I will book a flight tomorrow.

Output:

book → VERB

Input:

I read a book yesterday.

Output:

book → NOUN

The same word receives different POS labels depending on context.

---

## Current Architecture

```text
app/
api/
configs/
data/
docs/
models/
notebooks/
src/
tests/