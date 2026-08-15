"# GENAI Lab Collection

A hands-on repository of Generative AI experiments and lab notebooks covering transformers, fine-tuning, prompting, memory-based chat, embeddings, semantic retrieval, and chunking workflows.

Student: Bhargav Limbani  
Roll Number: 92301733029

<div align="center">

![Python](https://img.shields.io/badge/Python-3.10%2B-blue?style=for-the-badge&logo=python)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge&logo=jupyter)
![PyTorch](https://img.shields.io/badge/PyTorch-Deep%20Learning-red?style=for-the-badge&logo=pytorch)
![LLM](https://img.shields.io/badge/GenAI-LLM%20Labs-green?style=for-the-badge)

</div>

## Overview

This repository contains a collection of GenAI lab notebooks developed during the course. Each folder focuses on a practical implementation of modern AI workflows, from foundational transformer concepts to real-world LLM interaction and embedding-based systems.

## Repository Structure

- [92301733029_Lab_1](92301733029_Lab_1) — English to Hindi transformer-based implementation notebook
- [92301733029_Lab_2](92301733029_Lab_2) — Shoolini pretraining experiment using a GPT-style model
- [92301733029_Lab_3](92301733029_Lab_3) — Fine-tuning a GPT-2 model on the Dr. Patient dataset
- [92301733029_Lab_4](92301733029_Lab_4) — Groq API basics and LLM experimentation
- [92301733029_Lab_5](92301733029_Lab_5) — Interactive chatbot built with Groq
- [92301733029_Lab_6](92301733029_Lab_6) — Memory-based chat conversation workflow with LangChain
- [92301733029_Lab_7](92301733029_Lab_7) — Prompt template and prompt engineering concepts
- [92301733029_Lab_8](92301733029_Lab_8) — Chat prompt template and domain-specific conversational design
- [92301733029_Lab_9](92301733029_Lab_9) — BGE-M3 embeddings and recommendation system examples
- [92301733029_Lab_10](92301733029_Lab_10) — Embedding experiments and semantic similarity tasks
- [92301733029_Lab_11](92301733029_Lab_11) — Chunking strategies for text processing and LLM pipelines

## Lab Overview

### Lab 1: English to Hindi Transformer
Explores a transformer-based neural machine translation workflow for English-to-Hindi text generation.

### Lab 2: Shoolini Pretraining
Covers GPT-style model pretraining on a custom corpus with tokenization, configuration, and training workflow.

### Lab 3: Fine-tuning Dr. Patient
Demonstrates domain-specific fine-tuning of GPT-2 for text generation tasks.

### Lab 4: Groq API Basics
Introduces direct integration with Groq-hosted LLMs using API calls and prompt execution.

### Lab 5: Groq Chatbot
Builds a simple conversational chatbot using Groq models in an interactive loop.

### Lab 6: Memory-based Chat
Uses LangChain memory to maintain conversation history and build context-aware chat behavior.

### Lab 7: Prompt Templates
Focuses on structured prompt creation using LangChain prompt templates.

### Lab 8: Chat Prompt Template
Shows how to combine system prompts, history, and human inputs for domain-specific conversation design.

### Lab 9: BGE-M3 Embeddings
Explores embeddings for semantic similarity and embedding-based recommendation objectives.

### Lab 10: Embedding / Semantic Matching
Extends embedding-based experimentation for text comparison and intelligent retrieval tasks.

### Lab 11: Chunking
Introduces text chunking methods for working with large documents in LLM and retrieval pipelines.

## Tech Stack

- Python
- Jupyter Notebook
- PyTorch
- Hugging Face Transformers
- LangChain
- Groq API
- SentencePiece
- BGE-M3 / Flag Embedding
- NumPy
- Pandas
- NLTK

## Prerequisites

Before running the notebooks, ensure Python and Jupyter are installed, and prepare a GPU-enabled environment when possible for heavier model training.

```bash
pip install notebook jupyter
pip install torch transformers datasets sentencepiece langchain langchain-groq langchain-community accelerate
pip install numpy pandas nltk
pip install FlagEmbedding
```

## How to Clone This Repository

```bash
git clone https://github.com/<your-username>/<your-repository-name>.git
cd <your-repository-name>
```

For example:

```bash
git clone https://github.com/bhargav/GENAI-Lab-Collection.git
cd GENAI-Lab-Collection
```

### Project Path Structure

```text
GENAI-Lab-Collection/
├── README.md
├── 92301733029_Lab_1/
├── 92301733029_Lab_2/
├── 92301733029_Lab_3/
├── 92301733029_Lab_4/
├── 92301733029_Lab_5/
├── 92301733029_Lab_6/
├── 92301733029_Lab_7/
├── 92301733029_Lab_8/
├── 92301733029_Lab_9/
├── 92301733029_Lab_10/
├── 92301733029_Lab_11/
└── .git/
```

## How to Generate a Groq API Key

Follow these steps to create your Groq API key:

1. Open the official Groq website: https://console.groq.com
2. Sign up or log in to your account.
3. Go to the API Keys section in the dashboard.
4. Click on Create API Key.
5. Copy the generated key and save it securely.
6. Use it in your Python notebook as follows:

```python
from groq import Groq

client = Groq(api_key="YOUR_GROQ_API_KEY")
```

> Important: Do not expose your API key in public repositories. Store it in a local environment variable or a secure config file.

## How to Use

1. Clone the repository.
2. Open the project folder in VS Code or Jupyter Notebook.
3. Navigate to any lab folder.
4. Open the corresponding notebook and run the cells in order.
5. For Groq-based labs, replace the sample key with your own generated API key.
6. If needed, use Google Colab or a GPU-enabled system for heavier training tasks.

## Important Notes

- Some notebooks require external data files or model downloads.
- Groq-based experiments require internet access and a valid API key.
- Training-intensive notebooks work best with GPU support.
- Some tasks may take time depending on model size and dataset volume.

## License

This project is intended for academic and learning purposes only.

---

This repository is a practical collection of GenAI experiments covering the foundations and modern workflows used in large language model applications.

## Future Improvements

- Add screenshots and outputs for each lab
- Add a proper project structure diagram
- Include installation notes for Google Colab
- Add a final report summarizing all lab learnings" 
