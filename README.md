# AI-Powered Knowledge System for SpaceX Falcon 9 Launch Analysis

## Overview

This repository contains the capstone project for the **Generative AI and its Applications** course (UE22CS342BA9). The project implements an AI-based knowledge system focused on analyzing SpaceX Falcon 9 rocket launch data to predict first-stage landing success. It integrates techniques from natural language processing (NLP), prompt engineering, retrieval-augmented generation (RAG), multimodal inputs, fine-tuning with LoRA, and evaluation frameworks, following the guidelines outlined in the project documentation.

The system uses publicly available data from Wikipedia and the SpaceX API, processed with Python libraries like Pandas, NumPy, Scikit-learn, and Folium. The project is structured into a comprehensive notebook, phase-specific notebooks, and a summary presentation, showcasing a full data science workflow from data collection to model evaluation.

## Project Structure

- **Capstone.ipynb**: A single Jupyter notebook with the complete implementation, covering all phases:
  - Data collection, preprocessing, and EDA.
  - Model development and fine-tuning.
  - Evaluation and insights.
- **phase_notebooks/**: A folder containing separate notebooks for each phase:
  - `phase1_nlp.ipynb`: Basic NLP tasks (preprocessing, POS tagging, embeddings).
  - `phase2_prompt_engineering.ipynb`: Prompt engineering (CoT, ToT, GoT).
  - `phase3_rag.ipynb`: Retrieval-augmented generation setup.
  - `phase4_multimodal.ipynb`: Agents with multimodal inputs.
  - `phase5_finetuning.ipynb`: Fine-tuning with LoRA/QLoRA.
  - `phase6_evaluation.ipynb`: Evaluation frameworks.
- **summary_slides.pdf**: A concise presentation summarizing the project’s methodology, results, and insights.
- **data/**: Directory for raw and processed datasets (e.g., CSV files, API data).
- **images/**: Folder for visualizations (e.g., launch site maps, model performance plots).
- **README.md**: This file.

## Methodology

### Phase 1: Basic NLP Tasks
- Preprocessed textual data from Wikipedia and API sources.
- Applied POS tagging and created word embeddings (e.g., Word2Vec) to analyze launch-related terms.
- Visualized embeddings to identify relationships between key concepts.

### Phase 2: Prompt Engineering
- Implemented Chain of Thought (CoT) for step-by-step reasoning on launch success factors.
- Used Tree of Thought (ToT) to explore decision pathways based on launch conditions.
- Mapped relationships with Graph of Thought (GoT) for launch site and payload correlations.

### Phase 3: Retrieval-Augmented Generation (RAG)
- Built a knowledge base from launch data and articles.
- Integrated a retrieval system (e.g., FAISS) with a generative model to provide context-aware answers.

### Phase 4: Agents with Multimodal Inputs
- Designed agents for text-based query handling (e.g., "What affects landing success?").
- Planned extensions for voice and image inputs (e.g., OCR for launch images).

### Phase 5: Fine-Tuning Using LoRA
- Fine-tuned a pre-trained model (e.g., BERT or T5) with LoRA to optimize for launch prediction.
- Trained low-rank matrices with small learning rates, keeping original weights frozen.

### Phase 6: Evaluation Frameworks
- Evaluated model performance using metrics like Accuracy, F1-Score, BLEU, and ROUGE.
- Compiled a detailed report on strengths, weaknesses, and recommendations.

## Requirements

- Python 3.7+
- Required libraries (install via `pip`):
