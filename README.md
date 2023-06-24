# georgian-distilbert-mlm

This repository contains the code for conducting experiments and exploring different approaches in natural language processing (NLP). The code is organized in a chaotic manner as it represents a collection of experimental scripts and notebooks.

## Contents

The repository consists of the following files and directories:

- `full-model-building-cycle.ipynb`: Code for Model base, a custom NLP model.
- `training-fast-tokenizer.ipynb`: Jupyter notebook showcasing Model pre, another NLP model with its tokenizer.
- `compare-models.ipynb`: Code for loading and comparing different models.

## Models and Tokenizers

Both models are trained the same way, difference between them is that tokenizer of model_pre is trained on cleaned dataset and using whole word collator instead of a single token collator like in model_base.

## Demo, Documentation, and Usage

For a demonstration of the models and detailed documentation on how to use them, please visit the following Hugging Face model repository:

[Georgian DistilBERT MLM - Hugging Face Model Repository](https://huggingface.co/Davit6174/georgian-distilbert-mlm)

On the model repository page, you will find usage examples, sample code, and guidelines for incorporating the models into your NLP workflows.
