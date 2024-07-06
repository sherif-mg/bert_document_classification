# BERT Document Classification on BBC Full Text Document Dataset

This repository demonstrates how to use BERT (Bidirectional Encoder Representations from Transformers) for document classification using the BBC Full Text Document dataset.

## Table of Contents

1. [Introduction](#introduction)
2. [Dataset Description](#dataset-description)
3. [Data Preprocessing](#data-preprocessing)

## Introduction

This project uses BERT for classifying BBC news articles into predefined categories. BERT is a powerful NLP model capable of understanding the context and semantics of text, making it ideal for document classification tasks.

## Dataset Description

The BBC Full Text Document dataset contains 2,225 news articles from the BBC website, categorized into five topics:
- Business
- Entertainment
- Politics
- Sport
- Tech

The dataset is structured in folders where each folder name corresponds to a category. The dataset is available [here](http://mlg.ucd.ie/datasets/bbc.html).

## Data Preprocessing

The data preprocessing involves several steps to prepare the text data for input into the BERT model. The steps include:

1. **Loading the Dataset**: Read the text files and their corresponding labels.
2. **Cleaning the Text Data**: Remove special characters, punctuation, and convert text to lowercase to ensure uniformity.
3. **Tokenizing the Text**: Use the BERT tokenizer to convert text into tokens that BERT can understand.
4. **Creating Input IDs and Attention Masks**: Convert tokens to input IDs and create attention masks to indicate which tokens should be attended to.
