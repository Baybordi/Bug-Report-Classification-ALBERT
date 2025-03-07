﻿# LLM-Driven Bug Report Classification and Assignment 🚀

## Overview

This project explores the automation of **bug report classification and assignment** using **Large Language Models (LLMs)** and **Machine Learning (ML)** techniques. By leveraging **LLM-based ALBERT embeddings** for feature extraction and combining them with traditional classifiers like **Random Forest** and **Support Vector Machine (SVM)**, the study aims to enhance the efficiency of **bug triaging** in software maintenance.

## Key Features

- ✅ **LLM-Based ALBERT for Feature Extraction**: Utilizes pre-trained transformer-based embeddings to capture semantic features from bug reports.
- ✅ **Machine Learning Models**: Implements Random Forest, SVM, and Grid Search Optimized RF for classification.
- ✅ **Imbalanced Data Handling**: Analyzes performance across major and minor bug severity classes.
- ✅ **Performance Evaluation**: Compares models using **Precision**, **Recall**, and **F1-score** metrics.
- ✅ **Efficient Local Execution**: Conducted experiments on a **16GB RAM, Intel Core i7-6700HQ** system using **Python 3.12** and **Jupyter Notebook**.

## Technologies Used

- Python 3.12
- Large Language Models (LLMs)
- ALBERT (A Lite BERT for Self-supervised Learning of Language Representations)
- Random Forest, SVM, and Grid Search CV
- NumPy, Pandas, Scikit-Learn

## Results & Insights

- 📌 **LLM-Based ALBERT + Random Forest** demonstrated superior accuracy in handling major bug classes.
- 📌 **Class imbalance** remained a challenge, highlighting the need for **data augmentation** or custom loss functions.
- 📌 **Optimized models** showed improved precision-recall trade-offs, aiding in effective bug assignment.

## Future Work

- 🔹 Incorporate **deep learning-based classifiers** for further performance improvements.
- 🔹 Explore **synthetic data generation** to handle class imbalance.
- 🔹 Develop a **real-time bug triaging system** for industry applications.

## Installation

### Prerequisites

- Python 3.x
- pip (Python package installer)

### Steps

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Baybordi/Bug-Report-Classification-ALBERT
