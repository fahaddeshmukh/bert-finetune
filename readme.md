# Named Entity Recognition with DistilBERT Fine-Tuning

## Overview
This project fine-tunes the DistilBERT model for Named Entity Recognition (NER), a crucial task in natural language processing. NER involves identifying and classifying named entities within unstructured text, such as people's names, organizations, locations, dates, and more.

## Features
- **DistilBERT Fine-Tuning:** Utilizes the DistilBERT model architecture to perform NER, leveraging pre-trained representations to achieve accurate entity classification.
- **Tokenization and Alignment:** Implements tokenization and alignment techniques to prepare input data for fine-tuning, ensuring proper alignment of labels with tokenized inputs for accurate model training.
- **Evaluation and Metrics:** Incorporates evaluation metrics computation using the seqeval library to assess model performance. Metrics such as precision, recall, F1-score, and accuracy provide comprehensive insights into model effectiveness and capabilities.

## Libraries Used
- Hugging Face Transformers: For accessing pre-trained DistilBERT model and facilitating model fine-tuning.
- Hugging Face Datasets: For accessing and preprocessing datasets required for model training and evaluation.
- seqeval: For computing evaluation metrics such as precision, recall, F1-score, and accuracy for NER tasks.

## Getting Started
To get started with this project, follow these steps:
1. Install the required libraries: `pip install transformers datasets seqeval`
2. Fine-tune the DistilBERT model using your dataset.
3. Evaluate the model performance using the provided evaluation metrics.

## Directories

The project contains one directory:

- **bin**: 

  - `NER-Bert-FineTune.ipynb`: This notebook contains the code for running this project and alo provides narrative.

## Contributors
- Fahad Deshmukh
- deshmukh@uni-potsdam.de

