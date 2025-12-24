# Audio-Text Search using Phoneme 3-grams

This project implements audio-text search robustness to ASR errors using
phoneme 3-gram indexing and cosine similarity.

Two clean text documents and two ASR-like documents with realistic errors
are indexed using phoneme trigrams derived from CMU Pronouncing Dictionary.
A clean query is converted to phoneme trigrams and matched against the
documents using cosine similarity.

The notebook contains the full implementation, results table, and visualization.

