# Advanced NLP Tasks - Natural Language Processing Project

## Repository Overview

This repository contains a set of Jupyter notebooks that demonstrate advanced Natural Language Processing (NLP) techniques, applied to real-world challenges in the sustainability domain. The following tasks are covered, utilizing two distinct datasets:

- For tasks 1, 2, and 3, a dataset containing 1.6 million tweets from Twitter (now X) was used. Sustainability-related tweets were extracted by filtering the dataset based on specific keywords to enable sentiment analysis, topic modeling, and named entity recognition. [Link](https://www.kaggle.com/datasets/kazanova/sentiment140)

- Task 4 leverages a separate dataset of BBC news articles and their corresponding human-written summaries. This dataset enabled the fine-tuning of a text summarization model to generate concise and coherent summaries. [Link](https://www.kaggle.com/datasets/pariza/bbc-news-summary)


### 1. Sentiment Analysis
In this notebook, I build a sentiment analysis model using RoBERTa, fine-tuned on a dataset of tweets to classify sentiments as positive, negative, or neutral. The model's performance is evaluated on sustainability-related tweets using precision, recall, and F1-score.

### 2. Topic Modeling
In this task, I apply Latent Dirichlet Allocation (LDA) to identify key topics within a dataset related to sustainability. Text preprocessing techniques such as tokenization and stopword removal were used, and the final output includes a summary of the key topics discussed in the dataset.

### 3. Named Entity Recognition (NER)
This notebook focuses on extracting named entities such as organizations, products, and locations from sustainability-related text using a pre-trained spaCy NER model. The task includes preprocessing, entity extraction, and visualization using displaCy.

### 4. Text Summarization
In this task, I fine-tuned a pre-trained language model to generate concise summaries of sustainability-related text. The notebook demonstrates the model's ability to summarize longer texts and discusses the challenges faced during the fine-tuning and evaluation phases.

## Installation

To run these notebooks, you'll need the following dependencies:
- Python 3.7+
- Jupyter Notebook
- spaCy
- Gensim
- Hugging Face Transformers
- RoBERTa pre-trained model

You can install the required libraries using the following command:
```bash
pip install -r requirements.txt
```

# Usage

### 1. Clone this repository:

```bash
git clone https://github.com/aurag-fouad/Advanced-NLP
```

### 2. Navigate to the repository:
```bash
cd Advanced-NLP
```

### 3. Run the Jupyter notebooks:

```bash
jupyter notebook
```

## Contributions

Contributions to this project are welcome! If you have suggestions for improvements, bug fixes, or new features, feel free to fork the repository and submit a pull request. Please ensure that your contributions align with the project's goals and follow best practices for coding and documentation. For major changes, it is recommended to open an issue first to discuss your ideas. Contributions to expand the datasets, improve model performance, or add new NLP tasks would be greatly appreciated.

