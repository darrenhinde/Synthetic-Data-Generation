# PACE Workshop:  Synthetic Data

This workshop demonstrates how to effectively evaluate and improve Retrieval-Augmented Generation (RAG) systems using synthetic data and Phoenix for observability.

## Workshop Overview

In this workshop, you'll learn how to:

1. **Generate Synthetic Test Data**: Create realistic product reviews and question-answer pairs to evaluate your RAG system.
2. **Build a Basic RAG Pipeline**: Implement a retrieval system that answers consumer questions based on product reviews.
3. **Measure RAG Performance**: Use Phoenix to track key metrics and identify areas for improvement.
4. **Iterate and Improve**: Apply changes to your retrieval pipeline and measure their impact.

## Notebook Sequence

The workshop consists of three main notebooks:

1. **`make_product_reviews.ipynb`**: Generates synthetic product reviews for a fictional hardware product (Sawzall PX-1000). This creates our document corpus for retrieval.

2. **`make_synthetic_questions.ipynb`**: Creates synthetic question-answer pairs based on the product reviews. These serve as our evaluation dataset to measure RAG performance.

3. **`metrics.ipynb`**: Implements a basic search approach and calculates performance metrics. This provides a baseline you can improve upon during the workshop.

Throughout the workshop, you'll use Phoenix to visualize and analyze your RAG system's performance, helping you make data-driven improvements to your retrieval strategy.
