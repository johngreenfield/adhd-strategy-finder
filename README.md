# Project: ADHD Strategy Finder
## Introduction
This project is a prototype for the "Semantic Detective" track of the BigQuery AI Hackathon. Its mission is to solve a real-world problem by helping the neurodivergent community find relevant, crowd-sourced strategies for managing ADHD.

To demonstrate the architecture and value of a BigQuery-powered semantic search application, this notebook builds a fully functional prototype using a public Kaggle dataset. The workflow directly simulates BigQuery AI's capabilities:

- The `sentence-transformers` library is used to generate text embeddings, serving as a functional equivalent to BigQuery's `ML.GENERATE_EMBEDDING`.
- The `scikit-learn` similarity search is a direct stand-in for BigQuery's native `VECTOR_SEARCH` function.

This prototype proves the effectiveness of the approach. The next step would be to scale this proven logic by migrating it to BigQuery's serverless infrastructure to handle millions of documents in real-time.
