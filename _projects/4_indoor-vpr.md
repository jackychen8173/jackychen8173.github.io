---
layout: page
title: Indoor VPR with DINOv2
description: Visual place recognition using self-supervised learning
img: 
importance: 2
category: school
github: # add repo link
---

Evaluation of DINOv2 foundation model for indoor visual place recognition, comparing zero-shot retrieval performance against VGGT geometric re-ranking on the NYC Indoor VPR dataset.

## Overview

This project explored using DINOv2, a self-supervised vision transformer, for indoor place recognition tasks. The goal was to evaluate whether modern foundation models can perform zero-shot visual place recognition without task-specific fine-tuning.

## Tech Stack

- **Python** - Implementation language
- **DINOv2** - Vision foundation model (Meta AI)
- **PyTorch** - Deep learning framework
- **NYC Indoor VPR Dataset** - Benchmark dataset

## Methodology

**Zero-Shot Retrieval**
- Extracted DINOv2 embeddings from indoor images
- Computed cosine similarity for place matching
- Evaluated top-k retrieval accuracy

**Geometric Re-ranking (VGGT)**
- Applied VGGT spatial verification
- Analyzed improvement over pure embedding similarity
- Diagnosed limited improvement due to top_k_rerank=10 constraint

**Attempted Fine-tuning**
- Explored training optimization strategies
- Addressed slow training performance issues

## Results

- DINOv2 demonstrated strong zero-shot retrieval capabilities
- VGGT re-ranking showed limited improvement due to parameter constraints
- Results archived and documented for reproducibility

## Collaborator

Eric Kim, Henry Chen

## What I Learned

- Working with large vision foundation models
- Visual place recognition evaluation metrics
- Geometric verification techniques
- Optimization strategies for transformer fine-tuning
- Research experimentation and documentation

<!-- Add visualizations:
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/vpr-results.png" title="Retrieval results" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
-->