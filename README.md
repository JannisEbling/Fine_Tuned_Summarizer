# General Text Summarization with Retrieval-Augmented Generation (RAG)
This repository provides an end-to-end pipeline for summarizing general text content using a Retrieval-Augmented Generation (RAG) approach. Built with FastAPI for API access, the pipeline consists of data ingestion, transformation, model training, and evaluation steps.

## Objective
The objective of this project is to provide an effective solution for summarizing large volumes of text by:

Ingesting, processing, and transforming datasets for training.
Fine-tuning a transformer model to generate coherent summaries from input text.
Evaluating model performance using standardized metrics, enabling effective feedback and improvement.
This application is suitable for tasks such as content summarization, news aggregation, and document review in various domains.

## Pipeline Overview
The project uses a modular pipeline comprising the following classes:

DataIngestion: Downloads and extracts raw datasets.
DataTransformation: Tokenizes and preprocesses data for training.
ModelTrainer: Fine-tunes a transformer-based model on the preprocessed dataset.
ModelEvaluation: Evaluates the model performance using the ROUGE metric.

## Tech Stack
FastAPI
HuggingFace
Langchain