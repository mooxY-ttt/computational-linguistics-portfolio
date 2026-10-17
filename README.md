# Computational Linguistics Portfolio

This repository documents my practical exploration of Natural Language Processing (NLP) and computational methods applied to linguistic analysis. It serves as a supplementary portfolio for my application to the MA Linguistics with a Specialisation in Computational Linguistics programme at UCL.

## Project Index

### 1. Stylometric Analysis of Classic Literature
- **Objective**: Quantitative comparison of lexical features and stylistic patterns between different authors.
- **Tech Stack**: Python 3, Regular Expressions (`re`), `collections.Counter`, `matplotlib`.
- **Summary**: Programmatically fetches public domain texts from Project Gutenberg, performs regex-based text normalization, and visualizes word frequency distributions to identify distinct authorial signatures.
- **Notebook**: [`01_stylometric_analysis.ipynb`](./01_stylometric_analysis.ipynb)

### 2. Named Entity Recognition and Relation Extraction
- **Objective**: Extract structured relational data (Person-Organization links) from unstructured news text.
- **Tech Stack**: Python 3, `spaCy` (pre-trained `en_core_web_sm` model), `pandas`.
- **Summary**: Implements an NLP pipeline utilizing statistical NER and sentence-level co-occurrence analysis to infer semantic relationships. Transforms unstructured narrative into structured DataFrames suitable for downstream knowledge graph construction.
- **Notebook**: [`02_ner_relation_extraction.ipynb`](./02_ner_relation_extraction.ipynb)

## Methodology and Reflection
These projects demonstrate a progression from rule-based text processing to statistical NLP models. A key insight gained through this practical work is the limitation of simple co-occurrence heuristics for relation extraction, which often yields false positives in complex syntactic structures. Future iterations of these pipelines will explore dependency parsing and transformer-based architectures to capture deeper semantic dependencies.
