# Literature Review Assistance and Summarization Using RAG Approach

This project demonstrates the application of the Retrieval-Augmented Generation (RAG) technique using AI2's OLMo-1B language model to assist in literature reviews and summarization tasks.

## Features

- **Contextual Document Retrieval**: Utilizes the Qdrant Vector Database to retrieve relevant scientific documents for enhanced text generation.
- **Text Generation**: Implements OLMo-1B for generating coherent summaries, abstract completions, and answers to questions based on retrieved context.
- **Comparative Analysis**: Compares outputs generated with and without the RAG approach to evaluate improvements in context and accuracy.
- **Date Filtering**: Provides functionality to filter documents based on publication dates, allowing for targeted literature reviews.

## Methodology

1. **Dataset Acquisition**: Uses the ArXiv dataset, focusing on the astrophysics category.
2. **Data Preparation**: Preprocesses abstracts for compatibility with the model and database.
3. **Document Embedding**: Embeds documents into the Qdrant Vector Database using a pre-trained language model.
4. **Text Generation**: Generates text using OLMo-1B based on retrieved documents.
5. **Evaluation**: Analyzes the effectiveness of generated summaries and literature reviews.

## Requirements

- Python 3.8+
- Necessary libraries:
  - Hugging Face Transformers
  - Langchain
  - Qdrant
  - Sentence Transformers
