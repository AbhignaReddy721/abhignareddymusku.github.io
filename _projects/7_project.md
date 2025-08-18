---
layout: page
title: Dry Beans Multiclass Classification
description: ML models built from scratch to classify 7 types of dry beans based on physical characteristics
img: /assets/img/projects/drybeansclassification.png
importance: 2
# category: work
---

## Project Overview

Built classification models from scratch to accurately identify and classify 7 types of dry beans based on their physical characteristics and properties. This project demonstrates deep understanding of machine learning fundamentals by implementing algorithms without using high-level libraries.

## The Challenge

Dry beans are an important food source worldwide, and accurate classification is crucial for agricultural quality control and pricing. The goal was to develop models that could automatically classify beans based on features like shape, size, and other physical properties – all while implementing the algorithms from scratch to truly understand their mechanics.

## Implementation

Developed three classification algorithms completely from scratch without Scikit- Learn:

* **Logistic Regression** – Implemented multiclass classification using one-vs-all approach with gradient descent optimization

* **Support Vector Machines (SVM)** – Built SVM classifier with kernel methods for non-linear decision boundaries

* **Neural Networks** – Created a fully-connected neural network with backpropagation for deep learning classification

## Dataset

Used the [UC Irvine Machine Learning Repository's Dry Bean Dataset](https://archive-beta.ics.uci.edu/dataset/602/dry+bean+dataset) containing:
- 13,611 samples of dry beans
- 16 features (12 dimensional + 4 shape features)
- 7 distinct classes of beans

## My Contribution

I took the lead on comprehensive technical documentation and analysis for this project. My work involved:

- Created a comprehensive technical report explaining how all three models (Logistic Regression, SVM, and Neural Networks) work and their implementation details
- Conducted comparative analysis across models, documenting accuracy metrics
- Documented key findings from exploratory data analysis, including feature correlations and class imbalance issues
- Provided strategic recommendations on model selection based on the accuracy-speed tradeoff analysis

The report serves as a complete reference for understanding the project's approach and results.

## Repository

##### [🔗 View the code on GitHub]([link-to-github](https://github.com/abhignareddymusku/dry-beans-classification))

## Documentation

##### [📄 Read the full technical report](/assets/pdf/Projects/drybeansreport.pdf)