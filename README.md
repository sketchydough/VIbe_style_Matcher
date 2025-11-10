# VIbe_style_Matcher

This project recommends fashion products based on the “vibe” of a user’s query. Using text embeddings from OpenAI or Sentence Transformers, it computes cosine similarity between the user’s query (like “cozy pastel vibe” or “energetic urban chic”) and product descriptions. The system then ranks and returns the top 3 most relevant products, along with a similarity score and a metric indicating if the match is “good” or “poor”.

Key Features:

Uses embeddings to understand natural language queries.

Ranks products using cosine similarity.

Logs similarity metrics for easy evaluation.

Visualizes query latency for performance monitoring.

Tech Stack:

Python, Pandas, NumPy, Matplotlib

Sentence Transformers or OpenAI embeddings

Scikit-learn (cosine similarity)

Use Case:
Helps e-commerce platforms recommend fashion items to users based on descriptive, vibe-oriented search queries rather than just keywords.
