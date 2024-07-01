# RAG-Based AI with AES Encryption

## Overview

This project leverages the power of Retrieval-Augmented Generation (RAG) and Advanced Encryption Standard (AES) to provide a sophisticated AI system capable of generating text based on a vast corpus of information, while ensuring the security of the data through robust encryption methods.

## Features

- **Text Generation**: Utilizes the RAG model for generating text based on the input prompts and retrieved documents.
- **Document Processing**: Supports processing of both DOCX and PDF documents, allowing for a wide range of input formats.
- **Data Encryption**: Implements AES encryption to secure the data at rest and during processing, ensuring confidentiality and integrity.

## Technology Stack

- **Llama-Index & Transformers**: For leveraging state-of-the-art natural language processing models.
- **Accelerate**: Simplifies running machine learning models on multi-GPU setups.
- **BitsandBytes**: Optimizes memory usage and computational efficiency.
- **Docx2txt**: A lightweight converter that transforms DOCX documents into plain text.
- **PyPDF**: A Pure-Python library built as a PDF toolkit.
- **Cryptography & Pycryptodome**: Provides cryptographic functions and primitives for securing data.

## Installation

To set up the project environment, run the following commands in your terminal:

```bash
pip install llama-index transformers accelerate bitsandbytes
pip install llama-index-llms-huggingface
pip install docx2txt
pip install pypdf==4.0.1
pip install cryptography
pip install llama-index-embeddings-huggingface
pip install pycryptodome
