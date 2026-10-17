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

### 3. Exploratory Corpus Analysis Workflow (R)
- **Objective**: To demonstrate proficiency in academic statistical computing and tidy data principles for text analysis.
- **Tech Stack**: R, `tidyverse`, `tidytext`, `ggplot2`.
- **Summary**: This is a workflow demonstration rather than a full-scale research project. It utilizes the `tidytext` framework to tokenize a classic literary text, filter stop words, and calculate term frequencies. The output is a reproducible HTML report showcasing publication-quality data visualization, highlighting my readiness for corpus linguistics methodologies.
- **View Report**: [`03_corpus_linguistics_r.html`](./03_corpus_linguistics_r/03_corpus_linguistics_r.html)

## Methodology and Reflection
This portfolio demonstrates a multi-paradigm approach to computational linguistics. The Python projects focus on modern, statistical NLP pipelines and information extraction, highlighting my readiness for deep learning and NLP engineering coursework. The R project demonstrates my proficiency in academic statistical computing, tidy data manipulation, and corpus linguistics methodologies. 

A key insight gained across these projects is the trade-off between rule-based heuristics (e.g., regex, simple co-occurrence) and statistical models. Future work will focus on integrating dependency parsing and transformer-based architectures to resolve complex syntactic dependencies and coreference.
