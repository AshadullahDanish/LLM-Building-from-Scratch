# 🚀 Building an LLM from Scratch

Welcome to my repository! This project is all about developing a Large Language Model (LLM) from scratch using PyTorch, covering everything from tokenization to fine-tuning. Let's dive into the details! 🔥

## 📌 Features Implemented

### 🧩 Tokenization
- Implemented **Byte Pair Encoding (BPE)** using `tiktoken`.
- Created **Token Embeddings**.
- Designed **Positional Embeddings** to encode word positions.

### 🔥 Attention Mechanism
- Implemented a **simplified attention mechanism**.
- Built **self-attention with trainable weights**.
- Explained why we divide by `sqrt(d_model)`.
- Developed a **compact self-attention class in Python**.
- Applied **masking and dropout to attention weights**.
- Created a **causal attention class** for autoregressive behavior.
- Extended **single-head attention to multi-head attention**.
- Detailed **multi-head attention implementation**.

### 🤖 GPT Model Implementation
- Built a **dummy GPT model class**.
- Implemented **feedforward neural network** with GELU activation.
- Assembled the **entire GPT model architecture**.
- Implemented **text generation using output tokens**.
- Calculated **cross-entropy loss and perplexity** for evaluation.
- Developed a **DataLoader** for training.
- Implemented a **training loop for the LLM**.

### 🎯 Decoding Strategies
- Implemented **temperature scaling**.
- Implemented **Top-k sampling**.
- Merged **temperature scaling and Top-k sampling**.

### 💾 Model Saving & Loading
- Implemented **saving and loading of model weights in PyTorch**.
- Explored **loading pretrained weights from OpenAI**.

### 🛠️ Fine-tuning & Classification
- Fine-tuned the model for **classification tasks**.
- Initialized a model with **pretrained weights**.
- Added a **classification head**.
- Calculated **classification loss and accuracy**.
- Fine-tuned the model on **supervised data**.
- Used the LLM as a **spam classifier**.

### 🏆 Instruction Fine-Tuning
- Converted **instructions into Alpaca format**.
- Created **Dataloaders for an instruction dataset**.
- Loaded a **pretrained LLM**.
- Fine-tuned the LLM on **instruction data**.
- Extracted and saved **responses**.
- Evaluated the **fine-tuned LLM**.

## 🔥 What's Next?
- Implementing **LoRA and QLoRA for efficient fine-tuning**.
- Exploring **Reinforcement Learning with Human Feedback (RLHF)**.
- Optimizing training with **FSDP and DeepSpeed**.
- Experimenting with **different decoding techniques**.

## 🚀 How to Use
```bash
# Clone the repo
git clone https://github.com/AshadullahDanish/LLM-Building-from-Scratch
```

## 📜 License
This project is open-source and available under the MIT License. Feel free to contribute! 🤝

---
✨ **Star this repo if you find it useful!** 🌟

