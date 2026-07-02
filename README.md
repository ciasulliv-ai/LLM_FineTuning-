Fine-Tuning Transformers for Sequence Classification
This repository contains a pipeline for fine-tuning pre-trained transformer models on sequence classification tasks using Hugging Face and PyTorch. The code demonstrates data tokenization, hardware management, and training configurations.

Features
Hugging Face Integration: Uses transformers, datasets, and the Trainer API for model training.

Data Preprocessing: Implements batched tokenization with padding and truncation.

Device Management: Automatically detects and utilizes CUDA when a GPU is available, with a fallback to CPU.

Clean Logs: Explicitly manages environment variables to suppress tokenizer parallelism warnings and unneeded logging overhead.
