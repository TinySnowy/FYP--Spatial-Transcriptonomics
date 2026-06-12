# FYP References

## Project Description

Spatial Transcriptomics (ST) resolves gene expression profiles while retaining spatial coordinates. However, ST data often suffers from high sparsity and dropout rates. This project aims to develop a **Graph-Conditioned Diffusion framework** to impute missing gene expression values. By leveraging both the continuous distribution of gene expression and the local spatial structures modeled via Graph Neural Networks (GNNs), the model will reconstruct high-fidelity transcriptomic maps. Student will research on data-driven graph-conditioning strategies, optimize the generative process to preserve biological boundaries, and conduct rigorous evaluation across different spatial platforms.

---

## Background Reading

### 1. Single-Cell Biology
**Textbook**: [Single-cell best practices](https://www.sc-best-practices.org/preamble.html)

Start with the introduction section, focusing on:
- Chapter 4: Fundamental data structures and frameworks
- Chapter 5: Multi-modal and spatial structures

These chapters cover the libraries and data structures commonly used in Python-based single-cell analysis.

Then read the Spatial omics section:
- Chapter 28: Single cell data resolved in space
- Chapter 33: Imputation

### 2. Graph Neural Networks
**Library**: [PyTorch Geometric (PyG)](https://pytorch-geometric.readthedocs.io/en/latest/get_started/introduction.html)

Start with the PyG tutorials linked above.

### 3. Diffusion Models
**Blog post**: [Tracing the principles behind modern diffusion models](https://iclr-blogposts.github.io/2026/blog/2026/tracing-principles-behind-modern-diffusion-models/)

---

## Papers to Implement

| Paper | Link | Notes |
|-------|------|-------|
| **gimVI** | [arxiv](https://arxiv.org/abs/1905.02269) | Easiest to read and implement. Start here. |
| **Tangram** | [Nature Methods](https://www.nature.com/articles/s41592-021-01264-7) | Biology journal — focus on the methods section at the end. |
| **stDiff** | [Briefings in Bioinformatics](https://academic.oup.com/bib/article/25/3/bbae171/7646375) | Diffusion model for ST. Most relevant to final project. |
