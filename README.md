# Statistical Inference and Data Mining Final Project

Welcome to the repository for our final project in the course on Statistical Inference and Data Mining. This project involves participating in the Kaggle competition "Feedback Prize 2021." The competition focuses on solving a Named Entity Recognition (NER) problem using the provided dataset.
###This project was done together with Chanel Michaeli.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Notebook Outline](#notebook-outline)
  - [Data Analysis](#data-analysis)
  - [Problem Definition and Tools](#problem-definition-and-tools)
  - [Preprocessing](#preprocessing)
  - [Model Building and Training](#model-building-and-training)
  - [Evaluation](#evaluation)
  - [Submission](#submission)
- [Usage](#usage)


## Introduction

In this project, we participate in the Kaggle competition "Feedback Prize 2021." The objective of the competition is to solve a Named Entity Recognition (NER) problem using Natural Language Processing (NLP) techniques. Our goal is to locate and classify named entities in text and assign them to predefined categories representing the discourse elements.

## Dataset

The dataset for this project is provided by Kaggle and can be accessed through the competition link: [Feedback Prize 2021](https://www.kaggle.com/c/feedback-prize-2021). It includes a collection of text documents with corresponding annotations for named entities. The task is to build a model that accurately identifies and classifies these entities based on the provided training data.

## Notebook Outline

Our notebook follows a general outline to tackle the competition task effectively. The main sections of the notebook are as follows:

### Data Analysis

Perform exploratory data analysis (EDA) to gain insights into the provided dataset. This involves analyzing the characteristics of the text data, examining the distribution of named entities, and identifying any patterns or trends that can guide our model development process.

### Problem Definition and Tools

Define the NER problem and outline the tools and techniques we plan to use to solve it. In our case, we adopt Transformers, a library of state-of-the-art pre-trained models for Natural Language Processing (NLP). These models have achieved exceptional performance on various NLP tasks, including NER.

### Preprocessing

Prepare the labels and input data for the NER task. This step involves preprocessing the text data, converting it into a suitable format for training the model and creating appropriate label representations for the named entities. Preprocessing techniques such as tokenization, padding, and label encoding may be employed.

### Model Building and Training

Build and train the Long Former model for NER using the Transformers library. Long Former is a state-of-the-art model that captures long-range dependencies in text, making it particularly effective for NLP tasks. We fine-tune the pre-trained model on our NER dataset to enhance its performance.

### Evaluation

Evaluate the performance of our trained model using appropriate evaluation metrics for NER. Common metrics for NER include precision, recall, and F1 score. These metrics will help us assess the accuracy and effectiveness of our model in identifying and classifying named entities.

### Submission

Create the submission file in the required format specified by the competition. This file will contain the predictions for named entities in the test set. Ensure that the submission adheres to the competition guidelines and submit it through the Kaggle platform.

## Usage

To use the code and reproduce the results of this project, follow these steps:

1. Clone the repository: `git clone https://
