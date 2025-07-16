# 🔬 Bangla Physics MCQ Solver using Unsloth (Qwen3-14B)

A fine-tuned language model that solves Bangla medium Physics multiple-choice questions (MCQs) with step-by-step reasoning. This project leverages [Unsloth](https://github.com/unslothai/unsloth) for fast low-RAM finetuning of the Qwen3-14B model using LoRA adapters.

---

## 🚀 Features

- Translates Bangla physics questions to English with correct terminology.
- Performs chain-of-thought reasoning before answering.
- Fine-tuned using Unsloth’s optimized Qwen3-14B with LoRA adapters.
- Supports both training and inference modes.
- Achieves **macro F1-score: 0.72** on the evaluation set.
- Easily exportable to HuggingFace, GGUF, or Ollama formats.

---

## 🧰 Tech Stack

- 🐍 Python
- 🤗 HuggingFace Transformers & Datasets
- 🔥 PyTorch + CUDA 12.4
- 🦥 Unsloth
- 📦 LoRA (Low-Rank Adaptation)
- 📊 pandas, scikit-learn (for evaluation)

---

