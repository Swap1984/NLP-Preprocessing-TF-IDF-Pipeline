# TF-IDF-vectorization
An end‑to‑end NLP project demonstrating text cleaning, tokenization, TF‑IDF vectorization, and creation of custom trainable word embeddings. 
⭐ Key Learnings from This Project
🔹 1. Text Cleaning Pipeline Matters
We can learn how preprocessing steps—lowercasing, stopword removal, punctuation cleanup, lemmatization—directly influence vocabulary size and embedding quality.

🔹 2. Tokenization Controls Downstream Performance

 We learned how NLTK tokenization works and how contractions, rare words, and token frequency affect final representation.

🔹 3. TF-IDF Reveals Word Importance

WE can see how TF-IDF:

Reduces noise by down-weighting common words

Highlights context-specific terms

Creates sparse but meaningful document vectors

🔹 4. Word Embeddings Encode Semantic Meaning

By training your own GloVe embeddings, we can see how:

Co-occurrence statistics build relationships between words

Word vectors capture semantic similarity

Dimensionality impacts accuracy vs. computation speed

🔹 5. Building an Embedding Matrix

IT unveals mapping tokens → indices → vectors, learning how unseen or rare tokens affect the embedding matrix.

🔹 6. Combining TF-IDF + GloVe Improves Representation

Even though trained locally, we saw:

TF-IDF highlights word importance

GloVe provides semantic depth

Combined features outperform pure BoW

🔹 7. Vectorization Enables Real ML Tasks

The outputs can plug into downstream models such as:

SVM

Logistic Regression

Neural networks

Clustering algorithms

🔹 8. Debugging ML Pipelines Is a Critical Skill

We have gained hands-on practice fixing:

NLTK lookup errors

Shape mismatches in embedding matrices

Vocabulary differences between TF-IDF and embeddings

Missing GloVe vector errors

Overall this project gave me a good insight to tokenisation.
