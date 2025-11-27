***Reviewer Recommendation System***

A system that recommends suitable academic reviewers for research papers using SPECTER embeddings, PeerRead dataset, and cosine similarity.


***Summary***

This project loads research papers, cleans the text, generates scientific embeddings, builds reviewer expertise profiles, and recommends reviewers based on similarity.
It also performs conflict-of-interest checks and workload balancing.


***Features***

  -Load and preprocess PeerRead dataset

  -Generate SPECTER scientific embeddings

  -Build reviewer expertise profiles

  -Compute similarity using cosine similarity

  -Conflict-of-interest filtering

  -Balanced reviewer assignment

***Models and Methods***

  -SPECTER (allenai/specter) – scientific paper embeddings

  -Cosine Similarity – reviewer ranking
  

***Workflow***

 -Load dataset

  -Clean title and abstract

  -Generate SPECTER embeddings

  -Aggregate author vectors into reviewer profiles

  -Rank reviewers by similarity

  -Apply conflict-of-interest checks

  -Apply workload limits




***Installation***
```
pip install datasets==2.19.0 pandas sentence-transformers scikit-learn

```

***Repository Structure***
```
README.md
NLPmainacademic.ipynb
requirements.txt
```
