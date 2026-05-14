# Course Recommendation System: RAG vs Fine-tuning

A comprehensive research project comparing Retrieval-Augmented Generation (RAG), LoRA fine-tuning, and hybrid approaches for question answering over university course catalogs.

## 📋 Overview

This system processes and indexes 1,388 university courses to answer natural language queries with high accuracy. The project provides a rigorous comparative analysis of multiple LLM augmentation techniques across 210 diverse test queries.

### Example Queries
- "Find machine learning courses"
- "What is DAT465?"
- "7.5 credit courses about robotics"

## 🎯 Approach

The project evaluates four distinct methodologies:

| Approach | Description |
|----------|-------------|
| **Baseline LLM** | Unaugmented language model without external knowledge |
| **RAG** | Retrieval-Augmented Generation with semantic search |
| **LoRA Fine-tuning** | Parameter-efficient fine-tuning on Q&A pairs |
| **Hybrid** | Combined retrieval and fine-tuning approach |

## 📊 Key Findings

**RAG demonstrates superior performance** across most query types, providing the optimal balance between accuracy and efficiency. Fine-tuning excels for specific course code lookups and structured queries.

## 🛠️ Technology Stack

- **Language Model**: LLaMA 3.1 (8B parameters)
- **Fine-tuning Framework**: LoRA (PEFT)
- **Vector Database**: ChromaDB
- **Embeddings**: Sentence Transformers
- **Environment**: Python 3.10+

## 🚀 Getting Started

### Prerequisites
- Python 3.10 or higher
- pip or conda

### Installation

```bash
pip install -r requirements.txt
```

### Usage

```bash
jupyter notebook main.ipynb
```

## 📁 Project Structure

```
├── requirements.txt          # Project dependencies
├── main.ipynb               # Primary analysis notebook
├── data/                    # Course datasets
├── models/                  # LoRA checkpoints
└── results/                 # Evaluation metrics
```

## 📖 Documentation

For detailed methodology, results, and analysis, please refer to the main notebook.

## 📝 License

[Add your license information here]

## 👤 Author

[Your name]

---

**Last Updated**: 2026-05-14
