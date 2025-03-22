# Llama 3.2 Model Evaluation on Massive Multitask Language Understanding

### 📌 Overview
This project evaluates the performance of the [Meta's Llama 3.2 model](https://ai.meta.com/blog/llama-3-2-connect-2024-vision-edge-mobile-devices/) on the Massive Multitask Language Understanding (MMLU) benchmark using 5-shot learning. It implements structured prompt formatting, batch inference, and macro-averaged accuracy calculations to assess model performance.

### 🎯 Features
- 5-Shot Learning Evaluation: Uses few-shot learning to test model performance on MMLU.
- Batch Inference with Hugging Face: Utilizes AutoTokenizer and pipeline for efficient text generation.
- Prompt Truncation: Ensures input size remains within the model’s maximum token limit.
- Output Parsing: Extracts and processes multiple-choice answers to compute macro-averaged accuracy.

### 🏭 Data Sources
MMLU (Massive Multitask Language Understanding): [Hugging Face – cais/mmlu](https://huggingface.co/datasets/cais/mmlu)
<p align="center">
<img src="https://github.com/MaryNathalie/Llama-3.2-Evaluation-on-MMLU/blob/main/images/question_per_subject.png" width=80% height=80%>
</p>

### 🚀 Usage
Run the evaluation script:
```python
python evaluation.ipynb
```

### 📊 Results
Model Accuracy: **49.2%**  
META Baseline Accuracy: **49.3%**  
<p align="center">
<img src="https://github.com/MaryNathalie/Llama-3.2-Evaluation-on-MMLU/blob/main/images/accuracy_per_category.png" width=50% height=50%>
</p>
<p align="center">
<img src="https://github.com/MaryNathalie/Llama-3.2-Evaluation-on-MMLU/blob/main/images/accuracy_per_subject.png" width=80% height=80%>
</p>
