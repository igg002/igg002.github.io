---
name: Life Invader
tools: [Python, Deep Learning, NLP]
image: /assets/img/projects/thumbnails/life-invader-tn.png
description: # A simple ML-powered search engine
---

##### Role: Product Designer, Machine Learning Engineer
##### Date: 2017.11
<br>

#### Related Search Recommendation
My role in this project was to make a system that recommends related keywords with what the user searched for. For example, when the user searches for "coat," the system will recommend keywords like "single, long, short, trench."

#### Word2Vec
I used machine learning, specifically a technique called Word2Vec to develop this system.

According to wikipedia,

> "Word2vec models are shallow, two-layer neural networks that are trained to reconstruct linguistic contexts of words."

In other words, Word2Vec represents linguistic words as numeric vectors, resulting in clustering words with similar meaning, usage, or context. By comparing the similarity between the keyword that the user searched for with other pre-vectorized words, the system selects words with the highest similarity and provides them to the user.