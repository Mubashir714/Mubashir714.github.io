---
title: "Efficient CLIP Distillation"
collection: portfolio
permalink: /portfolio/efficient-clip-distillation
order: 4
# date: 2024-05-01
---

**Technologies:** PyTorch, OpenAI CLIP, ViT-B/32, Contrastive Learning, CUDA

Distilled a **lightweight student CLIP model** from a larger teacher model to enable efficient multimodal (text-image) retrieval, addressing the practical challenge of deploying CLIP-based systems where compute and memory are constrained.

**Key contributions:**
- Designed a **contrastive training pipeline** to transfer knowledge from a larger ViT-B/32-based teacher model into a smaller, more efficient student architecture.
- Developed **text–image alignment methods** to ensure the distilled model produced stable, semantically meaningful embeddings despite its reduced size.
- Leveraged CUDA-accelerated training to iterate efficiently across multiple distillation configurations.

This project explored the trade-off between **model efficiency and retrieval quality**, contributing toward making powerful multimodal models more practical to deploy in resource-constrained environments.

[Google Colab](https://colab.research.google.com/drive/1UxNSTNPi6E15sQWHryyu71OSKj7SrR3S)