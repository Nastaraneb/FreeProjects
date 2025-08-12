# Article Summarization with PEGASUS

This project uses **PEGASUS**, a transformer-based model from Hugging Face, to summarize articles in a dataset. The workflow includes data cleaning, extractive summarization, and abstractive summarization using PEGASUS.

## Table of Contents

1. [Overview]
2. [Setup]
3. [Data Preprocessing]
4. [Results]
5. [Dependencies]

## Overview

The goal of this project is to summarize articles in a dataset using two methods:
- **Extractive summarization** (selecting important sentences from the text)
- **Abstractive summarization** (generating new sentences that capture the key ideas)

We use the **PEGASUS** model, a state-of-the-art model for abstractive summarization, pre-trained on large datasets and fine-tuned on news articles.

## Setup

1. **Install dependencies:**

   You will need the following Python libraries:

   ```bash
   pip install torch tqdm transformers pandas

## Data Preprocessing

In this section, we prepare the data for summarization.

1. **Text Cleaning:**  
   The `clean_text()` function performs the following steps:
   - Removes missing values from the dataset
   - Eliminates extra spaces between words
   - Strips leading and trailing spaces

2. **Summarizing Articles in Batches**

   To avoid memory issues, the articles are processed in batches. 
   Each batch is tokenized and passed through the PEGASUS model to generate summaries.
   -Tokenizes the batch of articles
   -Generates summaries using the PEGASUS model
   -Decodes the summaries back into readable text

## Result

After applying the PEGASUS model, the summaries are generated and added to the dataset in a new column called "summary". 

## Dependencies

   -torch: PyTorch library for deep learning and model handling
   -tqdm: For showing a progress bar during batch processing
   -transformers: Hugging Face library for working with transformer-based models
   -pandas: For data manipulation and handling datasets

This README provides an overview of the project, the setup steps, and detailed instructions on how to use the code for summarizing articles. 
