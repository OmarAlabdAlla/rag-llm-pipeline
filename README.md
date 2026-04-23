# Course Recommendation System: RAG vs Fine-tuning

A project comparing Retrieval-Augmented Generation (RAG), LoRA fine-tuning, and hybrid approaches for question answering over university course data.

## Overview
This system processes 1,388 courses and answers natural language queries such as:
- "Find machine learning courses"
- "What is DAT465?"
- "7.5 credit courses about robotics"

The project evaluates multiple approaches across 210 test queries.

## Systems
- **Baseline LLM** – no external knowledge
- **RAG** – retrieval + generation
- **LoRA fine-tuned model** – trained on Q&A pairs
- **Hybrid** – combines retrieval and fine-tuning

## Key Result
RAG provides the best overall performance across most query types, while fine-tuning performs better for specific lookups.

## Tech Stack
- LLaMA 3.1 (8B)
- LoRA (PEFT)
- ChromaDB
- Sentence Transformers
- Python

## How to run
```bash
pip install -r requirements.txt
jupyter notebook main.ipynb
