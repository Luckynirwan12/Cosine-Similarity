# 📌 Cosine Similarity with TF-IDF
This project uses TF-IDF (Term Frequency-Inverse Document Frequency) and cosine similarity to measure how similar two or more text documents are.

## 🧠 How It Works
- TF-IDF Vectorization

  Each document is converted into a numerical vector using `TfidfVectorizer` from `scikit-learn`.

  TF-IDF assigns weights to words based on:

  - How frequently they appear in a document (Term Frequency)

  - How unique they are across all documents (Inverse Document Frequency)

- Cosine Similarity
After vectorization, the similarity between documents is measured using `cosine_similarity()`, which calculates the cosine of the angle between two vectors:

   - A score of `1.0` means the documents are identical.

   - A score closer to `0.0` means they are very different.

## ✅ Why TF-IDF + Cosine Similarity?
- Helps detect similar content even if exact words differ

- Commonly used in:

   - Plagiarism detection

   - Document clustering

   - Search engines

   - Recommendation systems

## 🛠 Libraries Used
- `TfidfVectorizer` — Converts text to TF-IDF vectors

- `cosine_similarity` — Measures similarity between those vectors

