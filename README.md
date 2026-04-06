# Graph-Refined Convolutional Network for Multimedia Recommendation with Implicit Feedback

> A new GCN-based recommendation model, GRCN, which adaptively refines the structure of the interaction graph to discover and prune potential false-positive edges.

## Authors

**Yinwei Wei**\*, **Xiang Wang**, **Liqiang Nie**, **Xiangnan He**, **Tat-Seng Chua**

\* Corresponding author (weiyinwei at hotmail.com)

## Links

- **Paper**: [`ACM MM'20`](https://dl.acm.org/doi/10.1145/3394171.3413612) *(Note: Add the specific paper URL if needed)*
- **Code Repository**: [`GitHub`](https://github.com/iLearn-Lab/MM20-GRCN)

---

## Table of Contents

- [Updates](#updates)
- [Introduction](#introduction)
- [Highlights](#highlights)
- [Method / Framework](#method--framework)
- [Installation](#installation)
- [Dataset / Benchmark](#dataset--benchmark)
- [Usage](#usage)
- [Citation](#citation)

---



## Introduction

This is the official PyTorch implementation for the paper **Graph-Refined Convolutional Network for Multimedia Recommendation with Implicit Feedback** (ACM MM'20).

In this work, we focus on adaptively refining the structure of the interaction graph to discover and prune potential false-positive edges. Towards this end, we devise a new GCN-based recommendation model, **Graph-Refined Convolutional Network (GRCN)**, which adjusts the structure of the interaction graph adaptively based on the status of model training, instead of remaining with a fixed structure.

---

## Highlights

- Adaptively refines the bipartite interaction graph during training.
- Identifies and prunes potential false-positive edges to denoise implicit feedback.
- Supports flexible configurations for multimodal integration strategies (`mean`, `max`, `confid`), prediction fusion modes (`concat`, `mean`, `id`), and pruning operations (hard vs. soft).

---
