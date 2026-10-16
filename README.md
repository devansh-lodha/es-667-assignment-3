# ES 667 Deep Learning: Assignment 3

Small multimodal experiments (20 marks).

**[Open assignment3.ipynb in Google Colab](https://colab.research.google.com/github/devansh-lodha/es-667-assignment-3/blob/main/assignment3.ipynb)**

## Questions

1. Q1: Contrastive Image-Text Alignment (4 marks)
   - Implement symmetric CLIP loss using tensor operations and `torch.logsumexp`.
   - Evaluate alignment and temperature scaling across $\tau \in \{0.01, 0.1, 1.0\}$.
2. Q2: Multimodal Image Retrieval with Frozen Embeddings (4 marks)
   - Implement top-5 semantic image search over a 17-image gallery using frozen `google/embeddinggemma-2`.
   - Evaluate queries for present objects, fine-grained visual details, and absent items.
3. Q3: Vision-Language Model Adaptation (8 marks)
   - Run single-step forward pass diagnostics and deterministic greedy generation with `HuggingFaceTB/SmolVLM-256M-Instruct`.
   - Compare handwritten digit recognition before and after fine-tuning the vision-to-language connector for 100 steps.
4. Q4: Concept Bottleneck Routing and Intervention (4 marks)
   - Implement a linear concept classification head and perform a test-time concept intervention.

## Instructions

- Open `assignment3.ipynb` in Google Colab using the link above and save a copy to your Google Drive.
- Select `Runtime -> Change runtime type -> T4 GPU`.
- Run all cells sequentially from top to bottom, completing the five functions marked with `YOUR CODE HERE` and the short written explanations.
- Keep all random seeds, model revisions, dataset splits, and training hyperparameters unchanged.
- Submit your completed notebook with all outputs and plots visible.
