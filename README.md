# NLP Exercise Project

Welcome to the NLP Exercise project! In this project, you'll be exploring and experimenting with state-of-the-art NLP pre-trained models such as BERT, GPT-2, and others. Let's break down the key components of your project:

### Project Overview
### Project Title: NLP Exercise
### Author: Maxwell Ernst
### Date: 18/04/2023

## Project Objectives

- Theoretical Understanding: Gain a basic theoretical understanding of the elements in an NLP pipeline.
- Practical Application: Apply theoretical knowledge by working with state-of-the-art NLP pre-trained models, specifically BERT and its derivatives, GPT-2, etc.
- Fine-tuning: Explore fine-tuning a Transformer model with a limited dataset (around 10-100 examples) using the Hugging Face Transformers library.
- Inference Pipeline: Implement the proper inference pipeline and experiment with prompts using Hugging Face Transformers.

Deliverables

- Link/HTML/PDF of your (Colab) notebook.
- Documented code with explanations of each step.

Steps Taken

Data Loading:

- Attempted to load the Yelp Review Full dataset using the Hugging Face Datasets library.
- Encountered a timeout issue while downloading data from the external source.

Tokenizer and Preprocessing:
- Created a tokenizer using the AutoTokenizer from the Hugging Face Transformers library.
- Defined a tokenize_function to preprocess the dataset using the tokenizer.

Model Loading:
Loaded a sequence classification model using AutoModelForSequenceClassification from the Hugging Face Transformers library.

Evaluation:
Utilized the 🤗 Evaluate library to compute accuracy as a metric.

Challenges:
Faced challenges during data downloading due to a timeout issue. Consider exploring alternative methods to access or preprocess data.

Future Work:

- Continue exploring and experimenting with different models and tasks.
- Address challenges related to data downloading or consider alternative datasets.
- Visualizations
- Image of a Graph (Visualize the graph here)
- Feature Vector Visualization (Provide insights or visualizations)

Conclusion
In conclusion, this project serves as a practical exercise in working with NLP pre-trained models. Despite encountering challenges in data downloading, the project demonstrates steps to tokenize, fine-tune, and evaluate a model. Future work involves addressing challenges and further experimentation with different models and tasks.
