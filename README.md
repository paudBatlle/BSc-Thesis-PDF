# BSc Thesis
Repo containing the paper of my Bachelor's Thesis.

### Abstract

As Large Language Models (LLMs) grow, computational costs for training and inference increase significantly. Parameter Efficient Fine-Tuning (PEFT) techniques reduce costs by minimizing parameter modifications during re-training. However, fine-tuning often involves private data, risking data leakage or unauthorized access. This research explores adapter-based fine-tuning, a PEFT method adding small trained linear layers, evaluating performance and privacy preservation. Using a 1.6B open-source model and private commercial data, adapters are trained on the full dataset, incremental portions, and non-overlapping subsets to investigate learning capabilities and potential for obtaining varied knowledge from one base model. Benchmarking on standard datasets is also performed to assesses any changes in reasoning and knowledge, comparing the adapter-enhanced model to the original. The study demonstrates adapter-based fine-tuning as an efficient, privacy-preserving approach for rapid task adaptation leveraging
