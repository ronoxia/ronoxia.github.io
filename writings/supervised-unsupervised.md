---
layout: page
title: Supervised vs. Unsupervised Learning
permalink: /writings/supervised-unsupervised
last_modified: 2025-04-08
reading_time: 1 min
date: 2025-04-08
tags: [machine-learning,notes,supervised,unsupervised]
---



This is one of the first distinctions I learned in machine learning — and one I keep coming back to as I work with real-world data.

### Supervised Learning
In supervised learning, we start with **labeled data** — where each input already has a known outcome. The goal is to learn the mapping between inputs and outputs.

I’ve used:
- **Logistic regression** and **random forests** to classify genomic sequences
- **Regression models** to predict continuous outcomes from biological features

Supervised learning is powerful when you know what you’re looking for — and when your data labels are trustworthy (which isn’t always the case in biomedicine).

### Unsupervised Learning
In unsupervised learning, there are **no labels** — just patterns. The goal is to discover structure, groupings, or representations that make sense of the data on its own terms.

So far I’ve worked with:
- **K-means clustering** for exploratory pattern discovery
- **PCA** to reduce dimensionality in gene expression data

Unsupervised learning has helped me see what’s in the data *before* I start making assumptions — and sometimes surfaces questions I wouldn’t have thought to ask.

---

This note will grow as I gain more hands-on experience — especially as I move into semi-supervised learning and more complex models for biomedical signals.

---

### Related:
- [Machine Learning](/writings/machine-learning)
- [Genomic Datasets](/writings/genomic-datasets)
