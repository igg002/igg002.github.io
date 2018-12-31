---
title:  "Life Invader"
subtitle: "Website"
author: "Sunwoo Jeong"
avatar: "img/authors/sunwoo.png"
image: "img/portfolio/life-invader-title-1-dark-1.jpg"
date:   2017-11-18 16:01:05
---

##### Role: Idea, Machine Learning Engineer

#### Related Search Recommendation
My role in this project was to make a system that recommends related keywords with what the user searched for. For example, when the user searches for "coat," the system will recommend keywords like "single, long, short, trench."

#### Word2Vec
I used machine learning, specifically a technique called Word2Vec to develop this system.

> Word2vec models are shallow, two-layer neural networks that are trained to reconstruct linguistic contexts of words.

In other words, Word2Vec represents linguistic words as numeric vectors, resulting in clustering words with similar meaning, usage, or context. By comparing the similarity between the keyword that the user searched for with other pre-vectorized words, the system selects words with the highest similarity and provides them to the user.

<center>
<img src="/img/portfolio/word2vec.png"/> 
<p><small>Visualization of a vector space mapped with word vectors</small></p>
</center>