🧠 GPT-2 from Scratch (PyTorch)


A complete implementation of a 124M Parameter GPT-2 Large Language Model, built from the ground up in PyTorch. This project covers the entire lifecycle of an LLM: architecture design, pre-training on custom datasets, loading official OpenAI weights, and fine-tuning for downstream tasks like spam classification.

🚧 Status: Completed & Functional 💻 Hardware: Optimized for Consumer GPUs (Tested on NVIDIA RTX 2060, 6GB VRAM)

🌟 Key Features
Custom Architecture: Full implementation of MultiHeadAttention, FeedForward, TransformerBlock, and LayerNorm without relying on Hugging Face's transformers library for the model structure.

Training from Scratch:

Trained on TinyShakespeare for character-level generation (Shakespearean text).

Trained on TinyStories for coherent storytelling capabilities.

Smart Weight Loading: Scripts to download and inject official OpenAI GPT-2 (124M) weights into the custom architecture.

Fine-Tuning: specialized head for Spam Classification (Spam vs. Ham).

Memory Optimization: Implemented Gradient Accumulation and dynamic batch sizing to train a 124M model on just 6GB VRAM without OOM crashes.
