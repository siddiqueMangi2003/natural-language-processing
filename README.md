# Natural Language Processing Coursework

This repository contains five practical assignments completed for a Natural Language Processing course. The exercises cover classical text processing, word embeddings, language generation, named-entity recognition, and retrieval-augmented generation.

## Assignments

| Lab | Topic | Files |
| --- | --- | --- |
| 1 | Scikit-learn, text preprocessing, Zipf's law, classification, and sentiment analysis | `lab_1_2026.py` |
| 2 | Pre-trained and custom word embeddings, semantic change, WordNet retrofitting, and visualization | `lab_2_word_embeddings.py` |
| 3 | Trigram language modelling with backoff and GPT-2-based typo detection | `lab_3_natural_language_generation.py` |
| 4 | Named-entity recognition with BERT and Llama, including BERT fine-tuning on WikiANN | `lab_4_exercise.ipynb`, `lab_4_exercise_predictions.csv` |
| 5 | Retrieval-augmented generation over the rules of a new sport | `lab_5_rag_exercise_student.ipynb`, `lab_5_exercise_predictions.csv` |

## Lab 1: Text Processing and Classification

Lab 1 introduces common NLP workflows with scikit-learn and NLTK. It includes an exploration of Zipf's law, text preprocessing, feature extraction, classification, and sentiment analysis.

## Lab 2: Word Embeddings

Lab 2 works with pre-trained embeddings and trains Word2Vec models on COVID-related text. It compares embeddings across time periods, measures semantic change, applies WordNet-based retrofitting, and visualizes embeddings with PCA.

## Lab 3: Natural Language Generation

Lab 3 implements unigram, bigram, and trigram language models with a backoff strategy. It also uses GPT-2 token probabilities to identify possible spelling or grammatical errors through a probability-drop threshold.

The file is exported from Google Colab and contains `!` shell commands, so it should be run as a Colab notebook or adapted before execution as a standard Python script.

## Lab 4: Named-Entity Recognition

Lab 4 predicts entities for the first 64 English WikiANN examples. It compares a BERT NER model with prompted entity extraction using a Llama chat model and includes an exercise for fine-tuning BERT on WikiANN.

The accompanying CSV contains 64 prediction rows with the required model outputs.

## Lab 5: Retrieval-Augmented Generation

Lab 5 builds a small RAG pipeline over the rules of a new sport. The notebook covers index construction, retrieval, context-grounded answer generation, and submission prediction generation.

The accompanying CSV contains 25 prediction rows.

## Running the Assignments

These assignments were developed primarily for Google Colab. Depending on the lab, they may require packages and model resources such as:

- NLTK
- pandas
- scikit-learn
- gensim
- spaCy
- PyTorch
- Transformers
- Datasets

Some notebooks download datasets or pretrained models at runtime and may benefit from a GPU-enabled Colab session. Open each file first and follow its setup cells or installation commands.

## Repository Structure

```text
.
├── lab_1_2026.py
├── lab_2_word_embeddings.py
├── lab_3_natural_language_generation.py
├── lab_4_exercise.ipynb
├── lab_4_exercise_predictions.csv
├── lab_5_rag_exercise_student.ipynb
├── lab_5_exercise_predictions.csv
└── README.md
```
