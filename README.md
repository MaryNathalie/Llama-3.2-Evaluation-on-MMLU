# Llama 3.2 Model Evaluation on Massive Multitask Language Understanding

### Overview
This project evaluates the performance of the ME4-LLaMA32 model on the Massive Multitask Language Understanding (MMLU) benchmark using 5-shot learning. It implements structured prompt formatting, batch inference, and macro-averaged accuracy calculations to assess model performance.

### Features
- 5-Shot Learning Evaluation: Uses few-shot learning to test model performance on MMLU.
- Batch Inference with Hugging Face: Utilizes AutoTokenizer and pipeline for efficient text generation.
- Prompt Truncation: Ensures input size remains within the model’s maximum token limit.
- Output Parsing: Extracts and processes multiple-choice answers to compute macro-averaged accuracy.
