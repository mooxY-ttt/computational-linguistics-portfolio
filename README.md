# Stylometric Analysis of Classic Literature

## Project Overview
This project explores the application of foundational Natural Language Processing (NLP) techniques to quantitatively analyze and compare the stylistic features of different authors. It serves as a practical demonstration of bridging linguistic inquiry with computational methods.

## Technical Stack
- **Language**: Python 3
- **Libraries**: 
  - `re` (Regular expressions for text normalization)
  - `collections.Counter` (Frequency analysis)
  - `matplotlib` (Data visualization)
- **Environment**: Google Colab

## Data Source
- *Alice's Adventures in Wonderland* by Lewis Carroll
- *The Hound of the Baskervilles* by Arthur Conan Doyle
- Texts were retrieved via HTTP requests directly from the Project Gutenberg open-source library.

## Linguistic Observations
Quantitative analysis of the cleaned text reveals distinct stylistic patterns:
1. Conan Doyle's text shows a higher relative frequency of concrete nouns and action verbs (e.g., "man", "door", "said"), aligning with the plot-driven nature of detective fiction.
2. Carroll's text, while also dialogue-heavy, features a distinct distribution of character-specific and fantastical vocabulary (e.g., "queen", "mock").

This demonstrates how basic frequency-based methods can provide objective starting points for stylometric analysis.

## Limitations and Future Improvements
The current tokenization relies on basic Regular Expressions, which may not accurately handle complex contractions (e.g., "don't") or morphological variations. Future iterations of this project will integrate advanced NLP libraries (e.g., spaCy or NLTK) to implement Part-of-Speech (POS) tagging and Lemmatization, enabling more granular syntactic and semantic analysis.

## How to Run
This project is hosted on Google Colab. You can view and execute the code directly by clicking the badge below:

[![Open In Colab](https://colab.research.google.com/drive/1qlom0do2ZMaP0HqEjF65ioSklb94Ofo7#scrollTo=SLv7CVAWY1R8&line=32&uniqifier=1)](https://colab.research.google.com/) 
