# SMS Spam/Ham Feature Engineering & Classification

## Overview
This project focuses on the machine learning phase of Natural Language Processing (NLP). It explores how different feature representations and selection techniques impact the performance of text classification. Using a custom modular preprocessing script, the project builds, trains, and evaluates a spam detection model to accurately classify SMS messages as Spam or Ham.

## Key Features
* **Modular Preprocessing:** Utilizes a standalone `pre_processing.py` script to cleanly handle data ingestion and text cleaning (tokenization, stemming, stopword removal) before modeling.
* **Feature Extraction & Vectorization:** Implements and compares different vector-based and statistical feature extraction techniques for text data (e.g., TF-IDF, Count Vectorization).
* **Feature Selection:** Applies selection methodologies to optimize the feature space, reducing dimensionality while aiming to improve classification accuracy.
* **Model Training & Evaluation:** Trains a text classification model on the processed dataset and strictly evaluates its performance using standard classification metrics.
* **Model Interpretability:** Analyzes and interprets feature importance scores to understand the underlying behavior and decision-making process of the model.

## Project Structure
* `epl499_assignment 2.ipynb`: The main Jupyter Notebook containing the vectorization, model training, evaluation, and feature interpretation.
* `pre_processing.py`: A reusable Python module containing the custom text-cleaning pipeline. 

## Tech Stack
* **Language:** Python
* **Libraries:** Scikit-Learn, NLTK, Pandas, Matplotlib
* **Environment:** Jupyter Notebook
